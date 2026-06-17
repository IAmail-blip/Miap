# Mi Agenda Personal

A personal life manager Progressive Web App (PWA) built as a single HTML file. Designed for daily use on Android mobile devices.

## Features

- 🚂 **Travel** — Track BlaBlaCar and train trips with templates for recurring routes
- 🌅 **Morning checklist** — Daily preparation tasks
- 🌙 **Night checklist** — Evening preparation tasks with "mark all" option
- 🗓️ **Events** — Calendar events with categories, recurrence and urgency highlight
- 📚 **Study topics** — Track study progress by subject with statistics
- 🏥 **Medical appointments** — Upcoming and past appointments
- 🛒 **Shopping** — Pharmacy, personal care and general items with pending-to-buy flag
- 📝 **Notes** — Quick notes with color coding
- 🔊 **Sounds** — Audio feedback on actions (toggleable)
- 💾 **Backup** — Export and import data as JSON

## Technical details

- Single HTML file — no frameworks, no dependencies except Google Fonts
- Data stored in `localStorage` — fully private, never sent anywhere
- Service Worker (`sw.js`) for offline use and caching
- PWA installable from Chrome on Android

## Files

| File | Description |
|------|-------------|
| `index.html` | Main application |
| `sw.js` | Service Worker for offline support |

## How to update

1. Open `index.html` in the repository
2. Click the pencil icon ✏️
3. Select all (`Ctrl+A`) and paste the new code
4. Also update the version number in `sw.js` (e.g. `v4` → `v5`)
5. Commit changes

## Install as PWA on Android

1. Open the GitHub Pages URL in Chrome
2. Tap the menu ⋮ → **Install app** or **Add to home screen**
3. Once installed, the app works fully offline

## Privacy

All data is stored locally on the device via `localStorage`. No server, no database, no tracking.
