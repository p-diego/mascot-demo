# Mascot Generator — demo

A quick look at an open-source mascot generator in the making: build a soft 3D mascot from ready-made parts, then let
any AI pick it up, pose it and animate it for videos, games and apps.

**Live demo:** https://p-diego.github.io/mascot-demo/

What the page shows:

- two mascots meeting (walk, wave, high five, celebrate, hug), driven by the same skeleton and moves;
- a small configurator: shape, color, finish, arms and legs, 13 moves, and a `.glb` download (skeleton plus two
  baked moves) that opens in Blender, Godot, Unity or any glTF viewer;
- every body inflated from a flat 2D silhouette, and finishes from vinyl to flat drawing.

It is a single `index.html` with [three.js](https://threejs.org) from a CDN: no build step. Early prototype,
October 2026.
