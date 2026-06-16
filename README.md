# WebGL Demos

Three self-contained WebGL / Canvas demos in a single page, switchable via the top tabs.

**Live:** https://seongilp.github.io/particla/

## Demos

- **◍ Particles** — GPU particle system (ping-pong float textures). 5 behaviors: Swirl, Flow Field (curl noise), Cluster (N-body density-gradient approximation), Warp (hyperspace), and a Solar System tour (sun, 8 planets with shading + Saturn's ring, comet, asteroid belt, moons, orbit lines, constellations, mouse-controlled camera). Up to 1M particles.
- **≈ Fluid** — real-time Navier–Stokes fluid (Jos Stam stable-fluids: advection → vorticity confinement → Jacobi pressure solve → projection). Drag to stir ink.
- **☄ Voyager 1** — NASA mission-control style tracker. Launch → Jupiter/Saturn gravity assists → termination shock → heliopause crossing into interstellar space, with live telemetry and an event log.

## Files

- `index.html` — the single self-contained build (each demo runs in an isolated `srcdoc` iframe). **This is the only file you need.**
- `particles.html` / `fluid.html` / `voyager.html` — the standalone source of each demo.

Everything is plain HTML + WebGL2 / Canvas 2D, no build step and no dependencies. Requires a WebGL2-capable browser.
