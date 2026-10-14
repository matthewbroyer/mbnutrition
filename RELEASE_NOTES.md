# Release notes · Nutrition (mbnutrition.online)

Newest first. One entry per release, in plain words a user would understand.

## 1.0 · 2026-10-14

First release in the mb app family style. Earlier internal builds (service worker cache v5) had no version number on screen.

- New look that matches the other mb apps: avocado-green accent, a new avocado logo, a sidebar on computers and a bottom bar on phones, and light or dark mode (it opens light unless you picked dark).
- New Data menu at the top: Save backup now (Ctrl+S), Export All (JSON), Import Backup (JSON), Export All (CSV) and Clear all data. In Chrome and Edge you can pick one backup file and Save backup now keeps it up to date.
- A backup status chip shows when you last backed up, and a dot on Data means a backup is due.
- Importing a backup now shows what's in it and lets you Merge (skips anything you already have) or Replace. Importing the same file twice no longer matters.
- If this browser stops saving (private mode, full storage), a banner says so and offers an export.
- New Help page with common questions and the sources and methods behind the numbers.
- Share a hydration day or a summary of your week as an image. Amounts stay off the card unless you turn them on.
- Install card and About card at the bottom of Settings. Press / to search foods from anywhere.
- A short welcome screen for first-time visitors (shown once).
- Fixed: a duplicated "Daily targets" box in Settings; imported backups are checked before anything is shown.
- The app no longer loads fonts from Google; it uses your system font and makes no outside requests.
- Your existing log, foods, drinks, recipes, supplements and settings carry over unchanged (same storage key). Data saved by older builds under the previous keys is still read, and a copy of it is kept.
