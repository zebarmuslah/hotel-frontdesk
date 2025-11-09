# Front Desk Board — v4 Upgrade (Settings + PIN + PWA)

## What's new
- Owner **Settings**: Hotel name, Currency label, PIN, Tax %, Service %
- **PIN gate** on load (default 0000) and before opening Settings
- Invoice shows **Hotel name** and **optional Tax/Service** lines
- PWA: install to phone and work offline

## How to deploy (Netlify)
1. Go to Netlify → **Add new site → Deploy manually**.
2. Upload the **contents** of this folder.
3. Open your public URL. On your phone, **Add to Home Screen**.

## Quick use
- Default PIN: `0000` → change it in **Settings** (top-right).
- Change **Hotel name** and **Currency** in Settings.
- **Export/Import JSON** to transfer data between devices.
- Note: PIN here protects the panel; for real authentication across devices, request the cloud backend version.

## Optional
- Edit `sw.js` / `manifest.webmanifest` if you want to change app name or colors for PWA.
