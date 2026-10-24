EchoWorkspace AI
================
Files: index.html (the app), manifest.webmanifest + sw.js + icons/ (installable offline app).

Run on your laptop (voice needs localhost or https):
  1. Unzip, open a terminal in this folder
  2. python -m http.server 8000
  3. Open http://localhost:8000 in Chrome or Edge

Publish: push ALL files (keep the icons folder) to a GitHub repo, then Settings > Pages > main / root.
After you edit index.html, change CACHE in sw.js (echoworkspace-v3 -> v4) so phones get the update.
Profiles are stored in each person's own browser. There is no server and no password.

New in this version: calendar, subtasks and notes, drag-and-drop, custom repeats, focus with custom time and task, undo/redo (Ctrl+Z / Ctrl+Y), photo crop, backup export/import, due-time reminders, optional PIN, weekly report print.
Reminders only work while the app is open. A PIN is privacy only, not strong security.

Basic voice assistant (Speak section): add tasks/projects, open your LinkedIn / GitHub / portfolio / resume, open any section, start a focus timer, answer questions about your profile, tasks, streak and focus time. English, Hindi and Hinglish. It uses your saved data and fixed rules, not an AI model.
Set your links in Profile > Edit profile first.
