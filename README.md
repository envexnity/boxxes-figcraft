# BOXXES — FigCraft Design Source & Comments

This repository contains the complete **BOXXES** website design exported from [`Untitled.figcraft`](Untitled.figcraft), including all **34 design/animation comments** (33 open, 1 resolved) and **12 replies**, rendered previews for all **17 frames**, unpacked JSON/PNG sources, version snapshots, and the local background video asset.

## Repository Contents

| Path | Description |
|---|---|
| [`Untitled.figcraft`](Untitled.figcraft) | Original, unmodified `.figcraft` project archive |
| [`COMMENTS.md`](COMMENTS.md) | All 34 comments & replies verbatim, grouped by frame in scroll order, with text layers, image links, and external component URLs |
| [`comments.json`](comments.json) | Machine-readable comment dataset with resolved frame IDs, anchor/coordinate metadata, timestamps, and replies |
| [`previews/`](previews/) | Rendered `1280px`-wide PNG previews of all 17 frames (`frame-01-id2.png` through `frame-17-id208.png`) |
| [`assets/boxxes-ad.mp4`](assets/boxxes-ad.mp4) | Background video referenced in Comment #16 (bundled here for web builds) |
| [`unpacked/document.json`](unpacked/document.json) | Extracted FigCraft document tree (nodes, transforms, fills, typography, comments) |
| [`unpacked/images/`](unpacked/images/) | All 13 embedded PNG images extracted with `.png` extensions + [`IMAGE_INDEX.json`](unpacked/images/IMAGE_INDEX.json) |
| [`unpacked/versions/`](unpacked/versions/) | 16 historical design snapshots + `index.json` |
| [`unpacked/thumbnail.png`](unpacked/thumbnail.png) | Project thumbnail from the `.figcraft` archive |

## Using with Google AI Studio

Paste this prompt into Google AI Studio after connecting/importing this repository:

```text
Read COMMENTS.md and inspect all 17 frame previews in previews/frame-01-id2.png through previews/frame-17-id208.png along with unpacked/document.json and unpacked/images/*.png.
Build the complete BOXXES scroll-driven website matching the design across every frame, using assets/boxxes-ad.mp4 for the Comment #16 background video and implementing every single comment and reply listed in COMMENTS.md (including all animations, color inversions, flickering typography, interactive 3D ASCII box, 21st.dev components, and pricing section).
```
