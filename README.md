# Lift 15 — PWA

This folder is a complete installable Progressive Web App.

## Files
- `index.html` — Lift 15 workout app
- `manifest.webmanifest` — PWA/app metadata
- `sw.js` — offline service worker
- `icons/` — Android/PWA icons

## Install on Android
1. Upload this entire folder to any static HTTPS host.
2. Open the HTTPS site in Chrome on Android.
3. Use Chrome's menu and choose **Install app** / **Add to home screen** when offered.
4. Launch **Lift 15** from the home screen.

## Important
- Do not open `index.html` directly with `file://` if you want full PWA features.
- HTTPS is required for service workers and the Screen Wake Lock API.
- Audio/vibration still depend on browser/device permissions and settings.
- App data such as weights and workout history is stored locally in the browser's storage for that installed site.
