# Road Blaster 2026

A top-down, retro Battle-City-style car-and-blaster defense game built with Three.js.
Drive a blaster car, defend the central core from waves of enemy cars, grab power-ups,
and clear the zone.

**Controls:** Arrow keys to drive · Space to fire · Shift to turbo.

## Tech
- Single static `index.html` (no build step)
- [Three.js](https://threejs.org/) loaded from CDN, with GLB models from
  [Kenney](https://kenney.nl/) asset kits (CC0) under `assets/`
- Top-down orthographic camera, flow-field enemy AI, destructible buildings,
  power-ups (Nuke / Clock / Shield / Steel), and a lives system

## Run locally
Any static file server works, e.g.:

```bash
python3 -m http.server 3000
# then open http://localhost:3000
```

## Deploy
Pure static site — deploys to Vercel with zero configuration (serves `index.html`
from the repo root).
