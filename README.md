# Holy Rosary Companion — Installable PWA package

This package includes the verified Mystery-name lookup fix plus basic PWA installation/offline shell support.

## Publish with GitHub Pages
1. Extract this ZIP.
2. Upload the **contents** of `holy-rosary-companion` directly into the root of your existing GitHub repository (including `index.html`, `manifest.webmanifest`, `sw.js`, and the `icons` folder).
3. Commit the changes and wait for GitHub Pages to deploy.
4. Open the HTTPS GitHub Pages URL on a supported device.

## Install
- Android: open in Chrome and use the browser menu's Install app / Add to Home screen option when available.
- iPhone/iPad: open in Safari, tap Share, then Add to Home Screen.
- Desktop: use the browser's install option if available.

## Offline notes
The service worker caches the app shell after the first successful online visit. It must be served over HTTPS or localhost; opening index.html directly from a file manager will not enable service workers.
This is basic offline shell caching only. Test on each target device before relying on it offline.

## Limitations
- This is a PWA, not an APK or an App Store app.
- It is not guaranteed to install identically on every device/browser.
- No native push notifications, cloud sync, user accounts, or recorded audio are included.
- Prayer texts and Filipino translations still need qualified Catholic review before public release.

## Footer
The app footer displays: © 2026 PCANetwork. All Rights Reserved.
