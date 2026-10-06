# Mascot Generator — demo

A quick look at an open-source mascot generator in the making: build a 3D mascot from ready-made parts, then let any AI
pick it up, pose it and animate it for videos, games and apps.

**Live demo:** https://p-diego.github.io/mascot-demo/

The page has three tabs, and each one builds its 3D content only when you open it:

- **Intro**: two styles in one scene. A soft cushion mascot wakes up, and a paper mascot on long legs walks in. They say
  hi, jump together and celebrate.
- **Make your own**: shape, color, finish, arms and legs, 13 moves, and a `.glb` download (skeleton plus two baked
  moves) that opens in Blender, Godot, Unity or any glTF viewer.
- **Styles**: seven sets, each loaded on its own.
  - Cushion styles: shapes and finishes.
  - Paper styles: solid, outline, shape-shifting, cartoon moves, and the cushion shapes on long legs with knees.

It is a single `index.html` with [three.js](https://threejs.org) from a CDN: no build step. Links can open a tab
directly: `#make`, `#styles`, `#styles/paper-solid`. Early prototype, October 2026.
