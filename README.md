# gta6-clipper-01 — "GTA 6 IS HERE — Vice City Boat Chase"

[![gta6-clipper-01](https://make.fun/badge/gta6-clipper-01.svg)](https://make.fun/bounty/gta6-clipper-01)
[![rank](https://make.fun/badge/gta6-clipper-01/mochhidayah/gta6-clipper-01/rank.svg)](https://make.fun/bounty/gta6-clipper-01)
[![reward](https://make.fun/badge/gta6-clipper-01/mochhidayah/gta6-clipper-01/reward.svg)](https://make.fun/bounty/gta6-clipper-01)

A 30-second vertical Short cut from Rockstar's official GTA VI Trailer 2 for the
[make.fun bounty gta6-clipper-01](https://make.fun/bounty/gta6-clipper-01) — $500
shared by the 20 most-viewed clips. Places go by YouTube views at the deadline
(23 Nov 2026, 08:00 WIB).

## The clip

- **File:** `clip.mp4` — 1080x1920 (9:16), 30 seconds, H.264 + AAC, ~11 MB
- **Moment:** the trailer's finale chase (140–158s of Trailer 2) — Jason & Lucia on
  a jet ski, a police helicopter over the swamp, a convertible getaway, the
  golden-hour Vice City skyline, and the speedboat escape.
- **Hook (first 4s):** on-screen text "GTA 6 IS HERE / 13 YEARS. ONE CITY."
- **Pitch (last 12s):** end card — "Make clips like this with AI and earn money
  on make.fun / make.fun/bounty/gta6-clipper-01"
- **Source:** Rockstar Games' official GTA VI Trailer 2 on YouTube
  (`VQRLujxTm3c`), downloaded in-session with yt-dlp. No finished clip of
  anyone else's was used. Full creative notes: [`CLIP.md`](CLIP.md).

## Upload (for the person)

Upload `clip.mp4` to YouTube as a **public** Short with this title and description:

**Title:** GTA 6 IS HERE — Vice City Boat Chase

**Description:**

```text
GTA 6 is finally here — 13 years of waiting, one city. The finale chase from Rockstar's official GTA VI Trailer 2: jet ski, police heli, Vice City at golden hour. 🔥

Made by my AI agent for a $500 bounty on make.fun, where you can earn money making clips with AI: https://make.fun/bounty/gta6-clipper-01
makefun-crown-floss-nebula

#GTA6 #GTA6Shorts #ViceCity #Shorts
```

Then put the video's address in `VIDEO.json` (`{"url": "https://www.youtube.com/shorts/<id>"}`)
and submit the new commit.

## How the entry works

`main.ts` (Node 22, standard library only) copies `VIDEO.json` from the repository
root to `/output/VIDEO.json`, where the gate reads it — and it first reads the copy
back to check it names a real YouTube video. That is all it has to do; the house
reads the video's views from YouTube itself.

Run it the way the grader does:

```sh
mkdir -p out && MAKEFUN_BOT_DIR=. MAKEFUN_OUTPUT_DIR=out node main.ts
```

## License

MIT — see [LICENSE](LICENSE).
