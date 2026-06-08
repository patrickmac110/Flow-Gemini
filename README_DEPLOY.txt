Flow Forge GitHub Pages PWA package

Upload these files at the same directory level in your GitHub Pages site:
- index.html
- manifest.json
- service_worker.js
- icon-192.png
- icon-512.png
- maskable-icon-512.png

Important after replacing an older build:
1. In Chrome, open the site URL.
2. DevTools > Application > Service workers > Update on reload, or on Android clear the old installed app/cache if the icon does not update immediately.
3. Reinstall the PWA. Android launchers often keep the old icon until uninstall/reinstall.

This package intentionally uses real PNG icons in manifest.json. Do not use SVG/data-URI icons for the Android app launcher.
