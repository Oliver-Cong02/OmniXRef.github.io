# OmniXRef — Project Page

Project page for **OmniXRef: A Unified Framework for Multimodal Multi-Reference Video Editing**.

Website: https://oliver-cong02.github.io/OmniXRef.github.io/

## Layout

- `index.html` — the whole page (single file, no build step)
- `assets/omnixref/`, `assets/gallary/`, `assets/comparison/` — result videos and posters
- `assets/video/` — demo video and its poster
- `assets/fonts/` — self-hosted Inter (SIL Open Font License, see `Inter-OFL-LICENSE.txt`)

## Updating

Everything editable sits in the config block at the top of `index.html`:

- **Paper / Code / arXiv buttons** — paste the URLs into `window.LINKS`. Empty Paper/arXiv show as "Soon"; the Code button stays hidden until its URL is filled in.
- **Demo video** — `assets/video/OmniXRef_Demo_Video.mp4` (poster: `assets/video/demo_poster.jpg`). It autoplays and loops while on screen with sound on by default; browsers that refuse sound before any interaction start it muted and turn sound on at the visitor's first click/tap/key. In `window.DEMO_VIDEO`, `sound: false` always starts muted and `autoplay: false` gives click-to-play. Replace the file to update it.
- **Method name** — change `window.NAMES`; every mention on the page, including the title wordmark, follows it.
