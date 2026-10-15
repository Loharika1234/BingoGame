BINGO — PWA / OFFLINE PHONE APP

Files:
- index.html: game
- manifest.json: installable app settings
- service-worker.js: caches app files for offline use
- icon.svg: home-screen icon

IMPORTANT:
A PWA must be hosted over HTTPS (or localhost) to install and use its service worker. Upload ALL four files/folder contents to a static host such as GitHub Pages, Netlify, or Cloudflare Pages. Then open the HTTPS URL in Chrome, allow it to load once, and choose Chrome menu > Install app / Add to Home screen. Open it once after installing while online so the files are cached; then test Airplane mode.

No backend, login, player connections, contacts, or Bluetooth are used. Each phone runs its own independent board.

Large-board mobile behavior:
15x15–25x25 boards keep cells large enough to tap/read and can scroll horizontally. On a phone, swipe sideways across the white board to see all columns. A 25x25 grid cannot make all 625 cells comfortably readable at once on a narrow phone screen, so horizontal scrolling is intentional.
