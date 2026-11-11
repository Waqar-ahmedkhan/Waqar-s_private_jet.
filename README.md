# Aero Noir — The quiet above the storm

A single-file cinematic private-jet site with a WebGL cloud field, an interactive 3D aircraft, and procedural cabin sound.

## Run locally

Open `index.html` directly in a browser, or serve the folder:

```bash
npx serve .
```

## Controls

- **Scroll / arrow keys** — move through the five aircraft stages.
- **Pace** — the slider at the bottom of the hero adjusts the cloud and flight speed.
- **Sound** — on by default. Browsers require one interaction before audio can start.

## Files

- `index.html` — production entry point (self-contained; textures and the GLB are embedded).
- `Aero Noir — The quiet above the storm (1).html` — working copy of the same page.
- `charter.mp4` — charter reference clip.

## Deploy

Hosted on Vercel. Push to `main` and redeploy with:

```bash
vercel --prod
```
