# HYROX Doubles Training Tracker — PWA

This is a standalone Progressive Web App based on the supplied HYROX 8-Week Doubles Programme PDF.

## Files
- `index.html` — app
- `data.js` — complete programme text extracted from the supplied PDF
- `manifest.webmanifest` — installable PWA metadata
- `sw.js` — offline service worker
- `icon.svg` — app icon

## Run locally
A service worker/PWA requires HTTPS or localhost. The simplest local option is: `python3 -m http.server 8000` from this folder, then open `http://localhost:8000`.

## Host online
Upload the contents of this folder to any static HTTPS host. Open the resulting URL on Android Chrome and choose **Install app / Add to Home screen**.

Training logs are stored locally in the browser/device using localStorage.
