PLOCKY WEBSITE TEMPLATE
====================

HOW TO RUN
1. Install Node.js 18 or newer.
2. Run `node server.mjs` from this folder.
3. Open http://localhost:8080 in a modern browser.
4. Change `port` in `server-config.mjs` to use a different port.
5. Click Geometry Dash or SKATE 3 to open the embedded game section.
6. Use "Full screen" to make the game window fill the screen. Press Esc to exit.

THUMBNAILS
The assets folder includes simple SVG placeholder thumbnails:
- assets/gd-thumbnail.svg
- assets/skate3-thumbnail.svg

Replace these with your own pictures if desired. If using PNG/JPG files, update the matching <img src="..."> path in index.html.

IMPORTANT EMBEDDING NOTE
Some external sites block being displayed inside another website. If either game does not load inside the frame, click "Open in new tab". The template cannot override another site's embedding/security restrictions. Fullscreen support can also depend on the browser and the embedded site.
