# Mascot Generator — demo

A quick look at an open-source mascot generator in the making: build a 3D mascot from ready-made parts, then let any AI
pick it up, pose it and animate it for videos, games and apps.

**Live demo:** https://p-diego.github.io/mascot-demo/

**New editor (work in progress, Create mode only):** https://p-diego.github.io/mascot-demo/editor/ — built from the
real project: presets, Randomize, shape, finish, color, face, 17 moves, **Copy link** (the whole mascot in the address)
and **Export .glb** (skeleton plus every move).

The page works like a small editor with three modes, and each mode builds its 3D content only when you open it:

- **Scene**: two styles in one 10-second scene, with a timeline you can pause and scrub. A soft cushion mascot wakes up,
  and a paper mascot on long legs walks in. They say hi, jump together and celebrate.
- **Create**: shape, finish, color, arms and legs, 13 moves, and **Export .glb** (skeleton plus two baked moves). The
  file opens in Blender, Godot, Unity or any glTF viewer.
- **Library**: seven sets, each loaded on its own.
  - Cushion styles: shapes and finishes.
  - Paper styles: solid, outline, shape-shifting, cartoon moves, and the cushion shapes on long legs with knees.

It is a single `index.html` with [three.js](https://threejs.org) from a CDN: no build step. Links can open a mode
directly: `#create`, `#library`, `#library/paper-solid`. Early prototype, October 2026.
