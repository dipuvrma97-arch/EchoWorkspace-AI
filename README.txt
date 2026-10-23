EchoWorkspace AI
================
Files: index.html (the app), manifest.webmanifest + sw.js + icons/ (installable offline app).

Run on your laptop (voice needs localhost or https):
  1. Unzip, open a terminal in this folder
  2. python -m http.server 8000
  3. Open http://localhost:8000 in Chrome or Edge

Publish: push ALL files (keep the icons folder) to a GitHub repo, then Settings > Pages > main / root.
After you edit index.html, change CACHE in sw.js (echoworkspace-v1 -> v2) so phones get the update.
Profiles are stored in each person's own browser. There is no server and no password.
