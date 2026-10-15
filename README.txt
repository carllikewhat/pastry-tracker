CRUMB & CO. — PASTRY TRACKER PWA
=================================

Files:
- index.html: the tracker, including localStorage saving
- manifest.json: app name and install settings
- service-worker.js: offline cache
- icon-192.png and icon-512.png: recommended app icons
- icon.svg: extra scalable icon

ANDROID-ONLY SETUP (GitHub Pages):
1. Download and extract pastry_pwa_files.zip using your phone's Files app.
2. In Chrome, open https://github.com and sign in/create an account.
3. Tap +, choose New repository. Name it pastry-tracker, choose Public, and create it.
4. In the repository, use Add file > Upload files (or the equivalent menu).
5. Upload ALL FOUR files from the extracted folder: index.html, manifest.json, service-worker.js, icon.svg.
   Important: index.html must be in the repository root, not inside another folder.
6. Commit/upload the files.
7. Open repository Settings > Pages. Under Build and deployment, choose Deploy from a branch.
8. Select branch main and folder /(root), then Save.
9. Wait a few minutes. In Settings > Pages, open the published site link. It will look like:
   https://YOUR-USERNAME.github.io/pastry-tracker/
10. Open that link in Chrome on Android. Wait for the page to finish loading.
11. Chrome menu ⋮ > Add to Home screen > Install (wording may vary).
12. Open the new home-screen icon and test adding a pastry, closing the app, then reopening it.

DATA SAVING:
- Pastry changes save to localStorage in the same browser/device.
- Do not clear Chrome's site data if you want to keep the saved pastries.
- localStorage does not sync to another phone/browser and is not a cloud backup.
- The "Reset demo" button deliberately restores the sample pastries.
- If you change the website files later, refresh the site. A service-worker update may take a moment.

TROUBLESHOOTING:
- If Pages does not show a site link yet, wait a few minutes and refresh Settings > Pages.
- If the page opens as plain HTML text or files are missing, make sure all four files are in the repository root and index.html is named exactly that.
- Installability can vary by Chrome version. The site must be opened through the HTTPS GitHub Pages link, not from the file:// location.
