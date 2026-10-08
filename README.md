# Mascot Generator — demo

A quick look at an open-source mascot generator in the making: build a 3D mascot from ready-made parts, then let any AI
pick it up, pose it and animate it for videos, games and apps.

**Live:** https://p-diego.github.io/mascot-demo/ — the editor, built from the real project:

- **Create**: presets, Randomize, the body (shape, width, height, tilt), color and finish (the outline with its color,
  and the body taking the color of its state), face, character, 17 moves, **Copy link** (the whole mascot in the
  address) and **Export .glb** (skeleton plus every move).
- **Scene**: a scene with its timeline (play, pause, scrub, drag to turn), scene links and **Export .glb**.
- **Library**: it needs the local editor of the project (`mascot editor`), which reads your folder, so it is off here.

`index.html` and `dist/editor.js` are a copy of the project's editor. The old addresses under `/editor/` open the main
page, with their mascot or scene link.

**The first prototype** (October 2026), hand-made in a single page: https://p-diego.github.io/mascot-demo/classic/ —
a 10-second scene with two styles, Create with 13 moves, and a Library of seven sets (cushion shapes and finishes, paper
styles). Links can open a mode directly: `classic/#create`, `classic/#library/paper-solid`.
