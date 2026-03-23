# SigFlow

A touch-friendly signal flow diagrammer for audio/video rigs. Built for pub karaoke and TikTok live streaming setups.

**[Open SigFlow →](https://wolfclostermann.github.io/sigflow/)**

---

## Features

- Infinite canvas with pan, pinch-zoom, and scroll-to-zoom
- Node categories: audio, video, compute, network, camera, output
- Draw connections between nodes with directional chevrons
- Attach photos to nodes (resize with drag handle)
- Export to PNG or PDF (landscape A3)
- Auto-saves to browser localStorage
- Import/export JSON to back up or share your rig layout

## Usage

**Add a node** — tap a category in the palette at the bottom

**Connect nodes** — tap the port dot on the right edge of a node, then tap the left edge of another

**Move nodes** — drag

**Context menu** — long-press a node

**Reverse a connection** — single-tap the line

**Delete a connection** — double-tap the line

**Zoom** — pinch, scroll wheel, or tap the % badge for presets

## Deployment

The app is a single HTML file with no build step. GitHub Pages serves it from the `main` branch root.

`default-rig.json` is Wolf's current rig layout. Visiting users with a saved local state will see an update banner when this file's `version` field changes.
