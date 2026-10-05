# HonestHands website

A static site (no build step) for downloading the HonestHands Mac app.

- `index.html`, `scenes.css`, `art.js`: the page and its animated illustrations
- `HonestHands.dmg`: the installer. Replace it with a new build (`./build.sh` in the app repo) and push to update the download. Keep it under 100 MB (Vercel and GitHub both reject larger files).

Deploy: import this repo in Vercel (Framework: Other, no build command, output directory: the root).
