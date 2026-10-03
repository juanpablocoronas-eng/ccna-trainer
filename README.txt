CCNA Adaptive Trainer — PWA package

Files
- index.html              Main application
- manifest.webmanifest    PWA metadata
- sw.js                   Offline service worker
- icons/                  App icons

Deployment requirement
Serve the complete folder over HTTPS. Do not rename or separate the files unless you also update their paths.

Recommended simple deployment
1. Upload the contents of this folder to any static HTTPS host (for example GitHub Pages, Netlify or Cloudflare Pages).
2. Open the resulting HTTPS URL in Safari on iPhone.
3. Share > Add to Home Screen > enable "Open as Web App" > Add.
4. Launch "CCNA Trainer" from the iPhone Home Screen.
5. Open it once while online so the service worker can cache the application.
6. Test offline by enabling Airplane Mode and reopening it.

Progress
- Study progress is stored locally on the device/browser.
- Use Settings > Export Progress regularly for backup.
- Use Settings > Import Progress to restore or move progress.
