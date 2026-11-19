FinPulse — updated app package

FILES
- Finpulse.html: updated app. The existing Overview, History, Budget and Accounts tabs are unchanged.
- manifest.webmanifest: PWA install metadata.
- sw.js: service worker for caching the app shell so the installed app can reopen offline.
- icons/: FinPulse launcher icons (192 px, 512 px and 180 px Apple touch icon).

INSTALL ON ANDROID
1. Upload every file and folder in this package to the same directory on an HTTPS website (for example, a GitHub Pages site).
2. Open the Finpulse.html page in Chrome on Android.
3. Use Chrome's menu and choose Install app or Add to Home screen.

MULTI-DEVICE BACKUP / RESTORE
1. On the first device, open the cloud icon or Settings > Backup & Restore.
2. Enter a GitHub Personal Access Token with the gist permission. Leave the Gist ID blank for the first backup, then tap Back up now.
3. Copy the generated Gist ID.
4. On each additional device, open Settings > Backup & Restore and enter the same token and Gist ID, then save credentials.
5. FinPulse checks the Gist when it opens and highlights the cloud icon when a newer backup is available. Tap Restore from Cloud to download it.

Cloud transfer is a manual backup/restore flow, not live simultaneous editing. Restoring replaces the current data on that device; export any unsynced changes before restoring if you need to preserve them. The GitHub token is stored in that browser's local storage, so only use a token you are comfortable saving on the device.

App identity: FinPulse
Home-screen / launcher icon: custom gold rupee coin with green growth arrow.
For Android installation, host this folder over HTTPS and use the browser Install app / Add to Home screen option. The manifest supplies the FinPulse name and 192px/512px icons.
