# Gather — Event Management Website

A responsive event discovery and registration website built with HTML5, CSS3 and vanilla JavaScript.

## Features
- Responsive layout for mobile, tablet and desktop
- Event cards with dates, venues, categories and descriptions
- Live event search and category filters
- Event details modal
- Registration form with JavaScript validation
- Registration records saved in browser Local Storage
- Light/dark theme toggle with saved preference
- Mobile navigation and interactive UI

## Run locally
Open `index.html` in a modern browser. No build tools or dependencies are required.

## Customize
Edit the `events` array near the top of `script.js` to add, remove or update events. Change colours and layout in `style.css`.

## Deploy with GitHub Pages
1. Open repository Settings → Pages.
2. Under Build and deployment, choose Deploy from a branch.
3. Select the `main` branch and `/(root)` folder.
4. Save and wait for the deployment URL to appear.

## Important note
This is a frontend demonstration. Registrations are stored only in each visitor's browser using Local Storage. A production system would need a backend and database to collect registrations centrally.