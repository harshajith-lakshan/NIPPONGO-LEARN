NIPPONGO LEARN - final package
================================
Files: index.html (whole app), manifest.webmanifest, sw.js (offline cache), icon-192.png, icon-512.png

RUN LOCALLY
  python3 -m http.server 8080      then open http://localhost:8080

DEPLOY (any static host, HTTPS required for install on Android)
  GitHub Pages / Netlify / Cloudflare Pages: upload this folder as-is.
  Chrome on Android: open the URL > menu > Install app.

DATA
  Progress is stored in the browser (localStorage), per site address.
  Settings > backup (JSON) / import to move or protect your progress.

NOT INCLUDED YET
  Stroke-order animation (no verified data), JLPT N5/N4 modules, formal exam system,
  IndexedDB storage, native-speaker audio (audio = browser text-to-speech).
