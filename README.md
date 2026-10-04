# KARDS HTML

A browser-based WWII collectible card game (KARDS-style). Open
`https://williamweiyangwu.github.io/kards-html/` and play.

## Play
- **LOCAL**: two players hot-seat on one screen.
- **ONLINE**: host a room, share the 5-letter code, and a friend joins from anywhere.
  Online uses a free public MQTT relay (no server or sign-in required).

## Build
It's a single self-contained `index.html` (HTML/CSS/JS). No install, no build.

Also in the source folder (not part of the site): `server.py` + `run_server.cmd`
provide a local static page server if you ever want to open it from another
device on your Wi-Fi.