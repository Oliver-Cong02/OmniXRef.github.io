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

- **Paper / Code / arXiv buttons** — paste the URLs into `window.LINKS`; empty entries show as "coming soon".
- **Demo video** — `assets/video/OmniXRef_Demo_Video.mp4` (poster: `assets/video/demo_poster.jpg`). Replace the file to update it; the path lives in `window.DEMO_VIDEO`.
- **Method name** — change `window.NAMES`; every mention on the page, including the title wordmark, follows it.
