# Three.js 3D Coverflow Carousel

Interactive 3D coverflow carousel built with **Three.js**. Curved panels (cylinder segments), inertial scrolling, wheel/drag controls, transparent WebGL canvas that blends into any page.

👉 **Live demo:** https://Maxocrat.github.io/threejs-coverflow-demo/

## Features
- Curved “poster” panels (cylindrical segments) with clean perspective
- Inertial scrolling + snap to center, wheel/drag + Prev/Next
- Transparent WebGL canvas over regular layout
- Image “contain” handling for any aspect ratio (NPOT-friendly, anisotropy)
- Optional full-page recording (WebM) via `getDisplayMedia`


## Quick start (local)

No build tools needed, but open the page via a local HTTP server (browsers block
WebGL textures when opening files from `file://`).

Option A — VS Code:
1) Install the “Live Server” extension.
2) Right-click `index.html` → “Open with Live Server”.
3) The app will open at something like http://127.0.0.1:5500/

Option B — Python (preinstalled on most systems):
Windows:  py -m http.server 8000
macOS/Linux:  python3 -m http.server 8000
Open http://localhost:8000/

Option C — Node:
npx http-server@14 . -p 5173
Open http://localhost:5173/


```text
threejs-coverflow-demo/
├─ index.html
├─ media/              # images (Screenshot_1.jpg … Screenshot_10.jpg)
├─ README.md
└─ LICENSE
