# Stride

Single-file landing page for a fictional plant protein bar brand. One real-time 3D bar wrapper (Three.js) travels from the hero carousel into a pinned "what's inside" section, spins through its own ingredients, and lands on its card in the shop grid.

## Run

Open `index.html` through any static server (module scripts and the import map need `http://`, not `file://`):

```
python3 -m http.server 4173
```

then visit http://localhost:4173/.

## Notes

- Everything is in `index.html`: CSS, JS, and the four latin WOFF2 fonts (Archivo Black, Inter, DM Mono) as base64.
- Hosts used at runtime: `images.higgs.ai` and `d8j0ntlcm91z4.cloudfront.net` (wrapper sheet and intro clip), `cdn.jsdelivr.net` (Three.js 0.160.0).
- Honors `prefers-reduced-motion`. Layouts for desktop and phone (< 820 px).
