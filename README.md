# Hegotá Testing Planning

Slides for the Hegotá testing planning session at L1 Days, Devcon 8, Mumbai (Sunday 1 November 2026). Speakers: Pari, Barnabas, Justin, Mario, Dan, Spencer, Guru.

Open `index.html` in a browser. It is a single self-contained file with no build step. The Funnel fonts load from Google Fonts when online; offline it falls back to system fonts.

## Keys

| Key | Action |
| --- | --- |
| Right, Down, Space, Page Down | Next slide |
| Left, Up, Page Up | Previous slide |
| Home / End | First / last slide |
| N | Toggle speaker notes |
| O | Toggle overview grid (click a slide to jump) |
| F | Toggle fullscreen |

Each slide has its own URL (`#1`, `#2`, ...). Swipe works on touch screens. Printing gives one slide per landscape page. Without JavaScript the slides stack vertically.

## Sources

Status on the slides is as of 29 October 2026:

- EELS Hegotá scoping tracker: https://github.com/ethereum/execution-specs/issues/3664
- hegota-devnet-0 release tracker: https://github.com/ethereum/execution-specs/issues/3787
- Test releases: https://github.com/ethereum/execution-specs/releases

The config-drift table is a 19 October snapshot from the ACDT #101 prep. Speaker notes (N) carry the details and links.

## Local preview

```sh
python3 -m http.server 8767 --bind 127.0.0.1
```
