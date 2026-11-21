# Sudoku Duo

A 9x9 sudoku web app for playing together: live co-op, live races, challenge links and shared times, plus step-by-step hints that explain the logic.

- `index.html`: the whole app (puzzle generator, hint solver and UI in one file)
- `database.rules.json`: Firebase Realtime Database rules (paste into the Firebase console → Realtime Database → Rules)

Live features need `window.FIREBASE_CONFIG` filled in inside `index.html`; everything else works without it.
