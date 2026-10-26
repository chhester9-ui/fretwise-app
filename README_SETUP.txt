FRETWISE / 90 — iPhone home-screen app

FILES: Upload ALL files in this folder to the root of an HTTPS website.

EASIEST FREE HOSTING: GitHub Pages
1. Sign in at github.com and create a NEW repository (for example, fretwise-app).
2. Set repository visibility to PUBLIC if you want free GitHub Pages on a free account. IMPORTANT: Public means the files and lessons are visible to anyone who finds the URL. Do not put private information in these files. Your journal stays locally on your device.
3. Use Add file > Upload files and upload the six app files from this folder (index.html, manifest.webmanifest, service-worker.js, icon-192.png, icon-512.png, apple-touch-icon.png). Commit.
4. Repository Settings > Pages > Build and deployment > Deploy from a branch > main > /(root) > Save.
5. Wait for the HTTPS Pages link (typically https://USERNAME.github.io/fretwise-app/).
6. On iPhone, open that link in SAFARI, tap Share, choose Add to Home Screen, then Add. Launch from the new icon.
7. Open once while online; after the first successful visit and service-worker installation, the core course is cached for offline use. Test by enabling Airplane Mode and opening the Home Screen app.

IMPORTANT DATA NOTES
- Completion tracking and practice journal are stored in browser localStorage on this device, not synced across devices.
- The original downloaded HTML file and this hosted app may have different storage areas: old progress will not automatically transfer.
- Use Export Progress periodically. Exported JSON is a backup/reference, not an importable restore in this version.
- iOS can clear site storage. Save progress exports to Files or iCloud Drive regularly.
- To publish updates, replace the files on the hosting service; offline cached versions may persist until refreshed.
- Do not open index.html directly from Files expecting offline installation: the service worker needs HTTPS hosting.
