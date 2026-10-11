PROGRAM WARDROBE V4.0 — PWA PACKAGE

This is the web-app version of Program Wardrobe V4.0.
It is a website/PWA project, not an APK.

WHAT'S INCLUDED
- index.html: the app interface and features
- manifest.json: installable web-app settings
- sw.js: offline cache support
- icons/: app icons

IMPORTANT
For the install prompt and offline support to work, host these files on an HTTPS website.
Opening index.html directly from the phone's file manager is useful for a quick test, but PWA installation/service workers require HTTPS (or localhost).

EASIEST PHONE-FRIENDLY ROUTE: GITHUB PAGES
1. Sign in to https://github.com/ and create a new public repository named program-wardrobe.
2. Upload the CONTENTS of this folder (index.html, manifest.json, sw.js, and icons folder) to the repository root.
3. Open the repository's Settings -> Pages.
4. Under Build and deployment, choose Deploy from a branch, select main and /(root), then Save.
5. Wait for GitHub Pages to publish the site. Open the published HTTPS URL in Chrome on Android.
6. In Chrome, tap ⋮ and choose Install app or Add to Home screen.

DATA / BACKUPS
- Programs are stored in the browser's local storage on that device/browser.
- Use Settings -> Export Backup regularly. Import the JSON backup if you switch browsers or devices.
- Hosting the app does not automatically sync your programs between devices.

If GitHub's mobile interface looks different, use the repository's Add file -> Upload files option and upload the four items/folder contents.
