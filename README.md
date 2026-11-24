JAYANTH ROUTINE OS — ANDROID PWA

FILES
- index.html: the app
- manifest.webmanifest: install details
- sw.js: offline cache
- icon.svg: app icon

IMPORTANT
A Progressive Web App must be served from HTTPS (or localhost) to install and use offline features. Opening index.html directly from a file manager is only a preview, not a full PWA installation.

EASIEST PUBLISHING METHOD: GitHub Pages
1. On a computer, sign in to GitHub and create a new public repository, for example jayanth-routine.
2. Upload all four files (index.html, manifest.webmanifest, sw.js, icon.svg) to the repository's main branch, in its root folder.
3. Open repository Settings > Pages.
4. Under Build and deployment, choose Deploy from a branch, select main and /(root), then Save.
5. Wait for GitHub Pages to publish the site. Open the published HTTPS address on your Android phone in Chrome.
6. In Chrome, open the menu (three dots) and choose Install app or Add to Home screen.
7. Open Routine OS from your home screen.

APP USE
- Tick tasks as you complete them. Progress is saved on this device.
- Select reminder checkboxes for the activities you want.
- Tap Enable notifications and allow permission.
- Use Test sound to check audio.
- Use Reset today's checks to clear today's checklist.

ALARM LIMITATION
This version checks reminder times while the app page is running. Android may suspend a PWA in the background, and notifications may not fire if the app is closed or the phone is asleep. It does not provide guaranteed background alarms. For guaranteed alarms, a native Android app with scheduled notifications is needed.

DATA
Checklist and reminder settings are stored locally in the browser on this device. Clearing browser site data will erase them. Streak increments when every item in a day is completed.
