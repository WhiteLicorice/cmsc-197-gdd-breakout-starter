# Breakout Starter

This project is the starting point for the CMSC 197 GDD Breakout workshops. It
carries the assets and the engine settings for the two-session series. It
carries no gameplay.

## What already works

- The project opens in Godot 4.7.2.
- The project imports every file in `assets/`.
- The project runs `scenes/main.tscn`, which draws a title label.
- The viewport is 1280 by 720. The renderer is GL Compatibility.

## What the workshops build

The Breakout manual adds the game in two sessions.

- Session 1 builds the paddle, the ball, player input, and the wall bounce.
- Session 2 builds the bricks, collision, score, lives, and restart.

The manual is the authority for each step. This project does not contain the
answer.

## Open and run

1. Install Godot 4.7.2.
2. Open `project.godot`.
3. Wait for the import to finish.
4. Press F5 to run the placeholder scene.

Do not commit `.godot/`. The editor rebuilds that folder.

## Where the licences sit

The project code is MIT-licensed. See `LICENSE`.

`ASSETS.md` lists every file with its pack, publisher page, archive hash, and
licence. `CREDITS.md` lists the packs for your own release. All packs are
CC0 1.0.

The folder layout under `assets/` matches the source packs. A later re-download
lines up with the same paths.
