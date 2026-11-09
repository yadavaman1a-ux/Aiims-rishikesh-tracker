# AIIMS NEET 2027 Tracker

## What's included
- Daily checklist with custom tasks and suggested template
- PCB chapter status tracker
- Physics/Chemistry/Biology backlog counts and history
- MCQ sessions and calculated accuracy
- Mock-test score history with subject splits and error notes
- Weekly review snapshot and reflections
- Local browser storage, JSON backup/restore
- PWA manifest and service worker for install/offline caching

## Run / install
A Progressive Web App must be served from HTTPS (or localhost) for installation and service-worker offline caching. This project is not automatically published online.

1. Upload the contents of this folder to an HTTPS static host (for example, GitHub Pages).
2. Open the hosted URL in Chrome on your Android tablet.
3. Chrome menu (⋮) -> Install app / Add to Home screen.
4. Open from the home-screen icon. Visit once while online so assets are cached.

## Data and privacy
Study records are stored in localStorage in the browser on the device. They are not uploaded to a server or synced across devices. Export JSON backups regularly. Clearing browser/site data can delete the tracker records.

## Important
The dashboard does not automatically read PW Yakeen data or send weekly reports. Enter your own study data. Weekly review is a local summary of logged entries.
