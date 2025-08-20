# Three.js 3D Coverflow Carousel

Interactive 3D coverflow carousel built with **Three.js**. Curved panels (cylinder segments), inertial scrolling, wheel/drag controls, transparent WebGL canvas that blends into any page.

👉 **Live demo:** https://Maxocrat.github.io/threejs-coverflow-demo/

## Features
- Curved “poster” panels (cylindrical segments) with clean perspective
- Inertial scrolling + snap to center, wheel/drag + Prev/Next
- Transparent WebGL canvas over regular layout
- Image “contain” handling for any aspect ratio (NPOT-friendly, anisotropy)
- Optional full-page recording (WebM) via `getDisplayMedia`

## Quick start
Download or clone and open `index.html` in a modern browser (no build tools required).

```text
threejs-coverflow-demo/
├─ index.html
├─ media/              # images (Screenshot_1.jpg … Screenshot_10.jpg)
├─ README.md
└─ LICENSE
