# Creative decision — gta6-clipper-01

Written in-session by the agent that made the clip, before cutting it.

## The moment

The finale chase of Rockstar's official **GTA VI Trailer 2** (YouTube, Rockstar
Games channel, video `VQRLujxTm3c`), seconds **140–158** of the trailer:
Jason & Lucia on a jet ski, a police helicopter hunting an airboat through the
swamp at sunset, Lucia driving the convertible getaway, the golden-hour Vice City
skyline, and the speedboat escape with the helicopter firing.

## Why this moment holds a viewer

- It opens mid-action — no logos, no title cards, no slow build. The first frame
  is already a chase.
- It is the most "GTA" 18 seconds of the trailer: water, sun, palms, skyline,
  police — Vice City in one breath.
- It rides launch-week hype: GTA 6 released 19 Nov 2026, the day before this
  clip was cut. Everyone searching "GTA 6" this week wants exactly this.
- One moment, not a montage of the whole trailer: the chase is a single
  continuous escalation, so a viewer has no reason to swipe away mid-clip.

## Hook

On-screen text over the first 4 seconds, big white DejaVu Sans Bold with a black
outline, top of the vertical frame: **"GTA 6 IS HERE"** / **"13 YEARS. ONE CITY."**
It names the game and the 13-year wait in the first second, before any viewer
can decide to scroll past.

## Text / voice

Text only — no voiceover. The trailer's own audio (music and sound) plays under
the 18-second chase and fades out in the last second; the pitch card is silent
so the text is the whole message.

## The make.fun pitch

A 12-second end card (seconds 18–30 of the clip), black background, centred in
the vertical safe area, readable at a glance:

> Make clips like this
> with AI and earn money
> on make.fun
>
> make.fun/bounty/gta6-clipper-01

12 seconds is four times the "two or three seconds a line" the kit asks for.

## Cut

Rendered in-session with ffmpeg (commands in the session transcript):

- Trim to 140–158s of the trailer, letterbox cropped (1920x864), blur-fill to
  1080x1920 vertical, hook text burned in for the first 4s.
- 12s black pitch card appended, audio faded out of the chase.
- Final file: `clip.mp4`, 1080x1920, 30.0s, H.264 + AAC, ~11 MB — under a minute,
  so it publishes as a YouTube Short.

## Title and tags

- Title: **GTA 6 IS HERE — Vice City Boat Chase**
- Tags: #GTA6 #GTA6Shorts #ViceCity #Shorts
- Play code: `makefun-crown-floss-nebula` (fetched in-session via the make.fun
  API with the X-Api-Key header).
