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

## Persistence

Your layout auto-saves to `localStorage` in the browser — it'll be there when you return. Use **↓ JSON** to export a backup or share your rig, and **↑ JSON** to restore it.

The `default-rig.json` in this repo is Wolf's current rig. If you've visited before and have a saved layout, a banner will appear when Wolf pushes an updated version — you can load it or dismiss and keep your own.

## Make it yours

Fork this repo, replace `default-rig.json` with your own exported layout, and enable GitHub Pages — you'll have a shareable diagram of your own AV rig at `https://your-username.github.io/sigflow/`.

## Deployment

The app is a single HTML file with no build step. GitHub Pages serves it from the `main` branch root.
