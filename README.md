# Aurum

Zayn's personal planner: daily tasks, HVC Form 5 East timetable, CSEC subjects, workouts, events, lessons and the Locked in streak.

- Live at: https://zayn19-design.github.io/aurum
- Data is synced with Firebase (login + Firestore), so updates to the app never touch your data.
- Install on iPhone: open the link in Safari → Share → Add to Home Screen.
- Works offline; changes sync when you're back online.

## Files
- `index.html`: the whole app
- `firebase-config.js`: your Firebase web settings
- `firestore.rules`: database security rules (paste into Firebase → Firestore → Rules)
- `manifest.webmanifest`, `sw.js`, `icons/`: what makes it installable and work offline
