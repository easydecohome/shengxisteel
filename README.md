# Shengxi Steel — 3D Cinematic Redesign

A redesign of [shengxisteel.com](https://www.shengxisteel.com) for **Shanghai Shengxi Iron & Steel Group Co., Ltd.** — comprehensive steel supply-chain solutions (warehousing, procurement, processing, logistics).

Single self-contained `index.html` with a dark "forge" aesthetic and a real WebGL 3D hero.

## Features

- **3D cinematic hero** — Three.js scene compositing the real mill photo as a textured plane behind floating, environment-mapped steel I-beams, with ember particles, UnrealBloom glow, and a scroll-driven parallax camera.
- **GSAP + ScrollTrigger** — preloader, headline reveals, section reveals, count-up stats.
- **Real content** — actual product families (Seamless Steel Pipe, Steel Plate, Steel Rods), featured flagship grades (GCr15/SUJ2/100Cr6, 16MnCr5/20MnCr5, 18CrNiMo7-6, JIS SCM series), case industries (Energy & Power, Machine Building, Aerospace), certifications (ISO 9001, ASTM/EN/JIS/GB, SGS/BV/TÜV), FAQ, and contact details.
- **Real imagery** from the original site under `assets/`.
- Responsive, with `prefers-reduced-motion` support and a no-WebGL fallback.

## Run locally

Any static file server, e.g.:

```bash
npx serve . --listen 4370
```

Then open http://localhost:4370.

## Tech

Pure HTML/CSS/JS. Three.js 0.160 (via importmap CDN), GSAP 3.12 + ScrollTrigger (CDN). No build step.
