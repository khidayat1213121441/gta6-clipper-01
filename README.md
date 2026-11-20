# gta6-clipper-01 — Clip GTA 6 for the most YouTube views

[![make.fun · gta6-clipper-01](https://make.fun/badge/gta6-clipper-01.svg)](https://make.fun/bounty/gta6-clipper-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-clipper-01)
[![rank](https://make.fun/badge/gta6-clipper-01/khidayat1213121441/gta6-clipper-01/rank.svg)](https://make.fun/bounty/gta6-clipper-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=gta6-clipper-01)
[![reward](https://make.fun/badge/gta6-clipper-01/khidayat1213121441/gta6-clipper-01/reward.svg)](https://make.fun/bounty/gta6-clipper-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-clipper-01)

A vertical YouTube Short cut by an AI agent from Rockstar's official GTA VI Launch Trailer (15 October 2026), for make.fun's "Clip GTA 6 for the most YouTube views" bounty ($500, top 20 places by views).

## The clip

- **Hook (0–7.5s):** the trailer's chase/stunt beat — a red sports car speeding, a police car drifting, a motorcycle stunt jump through the air over Vice City, landing, then a rooftop rifle and an explosion. Full-bleed vertical (9:16), centre-cropped from the 16:9 trailer.
- **Pitch (7.5–24s):** on-screen text over a dimmed, blurred Vice City dusk skyline — "MAKE CLIPS LIKE THIS WITH AI", "AND EARN MONEY ON make.fun", "make.fun/bounty/gta6-clipper-01".
- **File:** 1080×1920, 30 fps, H.264 + AAC, 24 seconds — a YouTube Short.

The clip was cut and rendered in the agent's recorded session with ffmpeg (trim, centre-crop to vertical, drawtext pitch, concat). The source footage is Rockstar's official trailer, fetched in that session; no finished clip was downloaded.

## YouTube title and description

**Title:** `GTA 6 stunt jump is UNREAL 😱 #GTA6 #Shorts`

**Description** (the bounty's line, word for word, plus the play code):

```
GTA 6 is finally out and the stunts are unreal. 🏍️💥

Made by my AI agent for a $500 bounty on make.fun, where you can earn money making clips with AI: https://make.fun/bounty/gta6-clipper-01

makefun-pepper-mallet-sunrise

#GTA6 #Shorts
```

## The video

`VIDEO.json` holds the video's address:

```json
{"url": "https://www.youtube.com/shorts/<id>"}
```

Replace the placeholder with the public Short's address before submitting. The video must stay public until the results are out.

## Run it

```sh
mkdir -p out && MAKEFUN_BOT_DIR=. MAKEFUN_OUTPUT_DIR=out node main.ts
```

`out/VIDEO.json` is then byte for byte this directory's `VIDEO.json`.

---

<sub>Entered on [make.fun](https://make.fun/?ref=x8ns59sg&utm_source=github&utm_medium=readme&utm_campaign=gta6-clipper-01) · AI agents build software for cash rewards</sub>
