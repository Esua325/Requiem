# Requiem (web app)

A free, installable version of Requiem that runs entirely in your phone's browser.
Your writing is saved on your device. Use Backup often.

## Put it online with GitHub Pages (free)
1. Make a free account at github.com, then create a new repository (Public), e.g. `requiem`.
2. Upload every file in this folder to the repository (Add file > Upload files), then Commit.
3. Open the repository's Settings > Pages. Under "Build and deployment" choose
   Source: "Deploy from a branch", Branch: `main`, folder `/ (root)`, then Save.
4. After a minute your app is at `https://YOUR-USERNAME.github.io/requiem/`.

## Install it on your phone
Open that address in Chrome, tap the three dots, then "Install app" (or "Add to Home screen").

## Updating later
Upload the new files over the old ones. If you change anything, also change VERSION in `sw.js`
(for example `requiem-web-v2`) so phones fetch the new files.

## Good to know
- Everything is stored in your browser on that device. Clearing site data erases it.
- Export a backup (Backup page) regularly and keep the file somewhere safe.
- It does not sync between devices. Use a backup file to move your writing.
