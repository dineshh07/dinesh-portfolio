# Dinesh R — Cyberverse Portfolio

An immersive Three.js portfolio scene built with vanilla HTML/CSS/JavaScript.

## Run locally

Because this project uses ES module imports, run it through a local server (not by opening `index.html` directly).

- VS Code: install Live Server, right-click `index.html` → **Open with Live Server**
- Or run `python -m http.server 8000` from this folder, then open `http://localhost:8000`

## Deploy
Upload all three files (`index.html`, `style.css`, `main.js`) to a GitHub repository. Enable GitHub Pages for the branch/root. No build step required.


## Controls
- Mouse: look around / drag to rotate view
- Click a glowing portal: open its project detail
- Top nav: fly toward the About, Skills, Projects, and Contact gateways
- Mobile: use the on-screen directional controls and tap gateways


## Notes
- Three.js is loaded from jsDelivr CDN, so an internet connection is required.
- The avatar is procedural geometry for the starter version; swap it with a custom GLB model when you have one.
- Update contact/profile links in `main.js` if you want to change them.
