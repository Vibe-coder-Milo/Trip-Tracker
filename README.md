# Trip Tracker

Personal travel planner: a world map of where you've been, and for each trip an overview, a day-by-day itinerary with a live map, and a budget.

Live site: https://vibe-coder-milo.github.io/Trip-Tracker/

## Files

- `index.html` is the whole app (HTML, CSS and JavaScript in one file; Leaflet comes from cdnjs).
- `sw.js` lets the app open without internet once it has been opened online.
- `manifest.webmanifest` lets you add it to the iPad home screen as an app.

## Where trips are saved

- Always in the browser on each device (local storage).
- Optionally in a **private** GitHub repo (`Trip-Tracker-data`), so every device matches. Set it up in Settings, Sync. Each device stores its own GitHub token; it never leaves that device and is never in this repo or in a backup file.
- The Google Maps key is kept in the private data repo, never in this repo. Restrict it to `vibe-coder-milo.github.io` in Google Cloud.

Settings, Backups can download one trip or all trips as a file, and load any backup, including ones from the old version of the app.
