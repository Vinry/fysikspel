# Physics sandbox

A small browser experiment using **p5.js** for drawing and **Matter.js** for rigid-body physics. It displays a ball, a box, and a fixed ground surface, with a mouse constraint intended for dragging objects.

This is a historical learning experiment, not a complete game. The original implementation is preserved and is not actively maintained.

## Open the demo

Open `index.html` in a browser. An internet connection is required because the page loads p5.js `0.10.2` and Matter.js `0.14.2` from external CDNs. There is no package installation or build step.

## Files

- `sketch.js` initializes and updates the physics world.
- `ball.js`, `box.js`, and `ground.js` define the displayed objects.
- `leapfrog.js` is a separate numerical-integration exercise; `index.html` does not load it.

## Known limitations

There are no game objectives, controls guide, or automated tests. The canvas mouse options are constructed but not passed to the mouse constraint. The displayed ball diameter also differs from its physics body. The original dependency versions have not been modernized, and browser interaction needs manual verification before this is treated as a finished demo.
