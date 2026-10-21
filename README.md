# Daymark

**A calm, private daily planner for small wins, focused work, and better routines.**

Daymark is a dependency-free, mobile-friendly web app. It keeps the useful bits of a daily planner together without requiring an account or sending your notes anywhere.

## Features

- **Today's focus:** add tasks, mark them done, filter the list, and carry unfinished tasks forward.
- **Focus room:** a 25-minute focus timer with pause, resume, reset, and a daily session count.
- **Gentle habits:** track four small daily routines without streak-shaming.
- **Daily note:** jot down a thought or reminder; it saves automatically on this device.
- **Progress at a glance:** completed tasks, focus minutes, and activity streak.
- **Backup:** export all local app data to a JSON file.
- **Offline support:** once hosted over HTTPS and loaded successfully, the app shell can be cached for later offline visits.
- **Installable:** supported browsers can add Daymark to the home screen.

## Run it

No package manager, build step, API key, server, or third-party JavaScript is required.

1. Open index.html in a modern browser for a local preview.
2. For install and offline functionality, serve the folder from localhost or a static HTTPS host. Service workers do not run from ordinary file URLs.
3. To publish with GitHub Pages, open the repository's **Settings → Pages**, choose **Deploy from a branch**, select main and the root folder, and save. After GitHub publishes the site, open the Pages URL and load it once while online.

## Privacy and data

Daymark saves tasks, habits, focus-session counts, daily notes, and activity history in this browser's localStorage. The app has no analytics, advertising, account system, backend, or network calls for personal data. The service worker only caches the app shell.

**Important:** browser storage is not a cloud backup. Clearing site data or using a different browser/device can remove or hide your planner. Use **Export backup** to keep a copy. The export contains your notes and planner data, so store it somewhere private.

## Files

- index.html — app UI, styles, and client-side logic
- manifest.webmanifest — install metadata
- icon.svg — app icon
- sw.js — offline app-shell cache

## License

The repository owner may add a license of their choice. Until a license is added, standard copyright rules apply.