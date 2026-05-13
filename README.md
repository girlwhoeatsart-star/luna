# Luna – Period & PMDD Tracker

A lightweight PWA for tracking your period and PMDD symptoms. Works offline, installs to your home screen.

## Files
- `index.html` – the entire app
- `sw.js` – service worker (offline support)
- `manifest.json` – PWA metadata
- `icon-192.svg` / `icon-512.svg` – app icons

## Deploy to GitHub Pages (free, ~5 minutes)

1. Go to [github.com](https://github.com) and sign in (or create a free account)
2. Click **+** → **New repository**
3. Name it `luna` (or anything you like), set it to **Public**, click **Create repository**
4. Click **uploading an existing file**, drag all 5 files in, click **Commit changes**
5. Go to **Settings** → **Pages** → under Source select **Deploy from a branch** → choose `main` → `/ (root)` → **Save**
6. Wait ~1 minute, then your app is live at: `https://YOUR-USERNAME.github.io/luna/`

## Install on your phone

**iPhone (Safari):**
1. Open the URL above in Safari
2. Tap the Share button → "Add to Home Screen"
3. Tap Add — Luna appears as an app icon

**Android (Chrome):**
1. Open the URL in Chrome
2. Tap the banner that says "Add Luna to home screen", or tap ⋮ → "Add to Home Screen"

## Your data
All data is stored locally on your device in `localStorage`. Nothing is sent anywhere.
