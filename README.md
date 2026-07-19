# The Daily Docket

A card-catalog styled personal task planner — install it on your phone like a real app, no download from an app store required.

**Live app:** https://sumayya-md.github.io/Planner-for-Mobile-Application/

## Features

- Add tasks with a due date, priority (Low / Medium / High), and category
- Check off, edit, or delete tasks
- Filter by All / Open / Closed / Overdue
- Search across your tasks
- Live progress stats and a completion bar
- Works fully offline once installed
- Installable on both Android and iPhone as a home-screen app (PWA)

## Install it on your phone

**Android (Chrome):** open the live link → tap ⋮ → **Add to Home screen** / **Install app**

**iPhone (Safari):** open the live link → tap the Share icon → **Add to Home Screen**

## How it saves your data

Tasks are stored locally in your browser on your device (no account, no server, no sign-in). This means:

- Your tasks stay private to your device
- Tasks don't sync between your phone and laptop, or between different people
- Uninstalling the app / clearing browser data will clear your tasks

## Built with

Plain HTML, CSS, and JavaScript — no frameworks, no build step. Packaged as a Progressive Web App (PWA) with a manifest and service worker for installability and offline support.

## Files

| File | Purpose |
|---|---|
| `index.html` | The app itself |
| `manifest.json` | App name, icons, and colors used when installing |
| `service-worker.js` | Caches the app so it works offline |
| `icon-192.png` / `icon-512.png` | App icons |
| `icon-maskable-192.png` / `icon-maskable-512.png` | Icons with safe-zone padding for Android's adaptive icon shapes |
| `apple-touch-icon.png` | Home screen icon for iPhone |
| `splash-*.png` | Launch screens shown while the app opens on iPhone |
