# Study OS

A calm, distraction-free study timer and tracker. Installable PWA that works offline.

## Features
- Focus timer that keeps running when you switch tabs
- Subjects and chapters, with session history grouped by each
- Daily study goal, progress bar and study streak
- Light and dark themes
- Optional Spotify playback (Premium account required)
- All data stays in your browser: no account, no server

## Use it
Open the live site: https://YOUR-USERNAME.github.io/studyos/
Install via the browser's Install button, or Add to Home Screen on a phone.

## Run locally
`python3 -m http.server 8765`, then open http://127.0.0.1:8765/

## Spotify (optional)
Create an app at developer.spotify.com, paste its Client ID in the Music tab, and add the Redirect URI shown there to your Spotify app settings. Uses PKCE, so no client secret is needed.
