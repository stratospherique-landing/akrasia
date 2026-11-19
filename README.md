# INNERSELF V6 — Sculptural & Quiet

## Contenu
- `index.html` : V5 preserved with actual WebGL Three.js parametric sculptural film, pointer interaction, slow breathing, 4 morphing states.
- `mentions.html` and `conditions.html`: placeholders **not ready for live commerce**.

## Preview
Open `index.html` in Chrome with internet access. Prefer a simple local HTTP server (`python3 -m http.server 8000`) for best results. The real 3D engine is loaded from jsDelivr at runtime, so an internet connection is required for 3D. If unavailable, the original animated SVG appears automatically.

## Hosting
Deploy entire folder to GitHub Pages. No server build required. HTTPS automatically serves the module.

## Interactions
- Floating translucent double membrane rotates and breathes.
- Pointer movement tilts sculpture.
- Method buttons change shape with smooth transitions.
- Scroll progresses hero depth effect.
- Mobile automatically uses lighter geometry and lower framerate.
- Prefers-reduced-motion keeps original static SVG.

## Before selling
Set real Stripe Payment Links, private delivery after payment, legal notices/CGV and privacy policies. Stripe buttons are placeholders.

## Technical note
Uses Three.js 0.160.1 (external CDN). Without network 3D cannot start; V5 SVG fallback remains. 3D tested for syntax/static integration; real browser external CDN and devices still need validation after deployment.
