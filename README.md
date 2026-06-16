# WebGL Demos

Eleven self-contained WebGL / Canvas demos in a single page, switchable via the top tabs.

**Live:** https://seongilp.github.io/particla/

## Demos

- **◍ Particles** — GPU particle system (ping-pong float textures), up to 1M particles. Modes: Swirl, Flow Field (curl noise), Cluster (density-gradient N-body), Warp, and a full Solar System tour.
- **≈ Fluid** — real-time Navier–Stokes fluid (Jos Stam stable-fluids: advection → vorticity → Jacobi pressure → projection). Drag to stir ink.
- **☄ Voyager 1** — NASA mission-control tracker. Launch → Jupiter/Saturn gravity assists → heliopause crossing into interstellar space, with live telemetry.
- **◉ Black Hole** — raymarched gravitational lensing with a doppler-shifted accretion disk.
- **❋ Mandelbulb** — raymarched 3D fractal with orbit-trap coloring and volumetric glow.
- **✦ Galaxy** — GPU N-body galaxy collision (~1M stars, two gravitating cores).
- **≋ Ocean** — Gerstner-wave ocean with fresnel sky reflection, sun glitter, and crest foam.
- **⬡ Reaction** — Gray-Scott reaction-diffusion (organic Turing patterns). Drag to seed, cycle presets.
- **🦠 Slime** — Physarum slime-mold simulation (~270k GPU agents forming vein networks).
- **▦ Cloth** — Verlet cloth with wind, grab, and tear.
- **♫ Audio** — radial frequency visualizer (built-in synth, optional microphone).

## Files

- `index.html` — the single self-contained build (each demo runs in an isolated `srcdoc` iframe). **This is the only file you need.** Deep-link a demo with `#name`, e.g. `#blackhole`.
- `*.html` (particles, fluid, voyager, …) — the standalone source of each demo.

Plain HTML + WebGL2 / Canvas 2D, no build step, no dependencies. Requires a WebGL2-capable browser.
