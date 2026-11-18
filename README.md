# EVERMORE

**One life. Endless possibilities.**

A free, mobile-first, browser-based life simulator. This repository contains the first playable prototype (v0.1).

## Play
Open the GitHub Pages website for this repository.

## Features in v0.1
- Character creation with name, country, birth era, difficulty
- Glassmorphic mobile UI, life event feed and filters
- Age-up progression with monthly income/cost simulation
- Choice events and attributes
- Basic career, finance, people and world pages
- Browser autosave and JSON export/import

## Deployment
Upload `index.html`, `style.css`, and `game.js` to the repository root. GitHub Pages should be set to deploy from `main` and `/(root)`.

## Important
Saves use localStorage and are separate on each device/browser. Back up using **More → Export save backup**. This is a prototype, not the completed simulation.


## v0.3 — Welcome screen on every launch
The welcome screen appears on every fresh page load, even with a saved life. Use **Continue Life** to resume or **Start New Life** to create a new character (with an overwrite warning). You can return to the welcome screen via More or Settings. Saves remain in the same localStorage key as previous releases.
