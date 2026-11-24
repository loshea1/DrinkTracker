# Dry Days iPhone web app

## Try it
Open `index.html` in a modern browser. Entries are saved in that browser on that device using local storage.

## Put it on your iPhone
To install it as a Home Screen web app, the files need to be hosted on an HTTPS website:
1. Upload `index.html`, `manifest.webmanifest`, and `sw.js` to a static host (for example, a GitHub Pages site).
2. Open the hosted HTTPS address in Safari on your iPhone.
3. Tap Share → Add to Home Screen → Add.

## Features
- Current month calendar with month navigation
- Tap a date to open the drink-count pop-up
- Add/remove drinks
- Blacked-out status overrides the calendar color to black
- Year overview and yearly statistics
- Saves entries locally in the browser on that device

## Privacy and limitations
No account or server is used. Data stays in that browser's local storage and does not automatically sync to other devices. Clearing Safari website data can erase it. The app is not yet published at a public URL; the ZIP contains the complete static web app files.
