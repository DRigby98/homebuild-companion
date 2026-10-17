# HomeBuild Companion — iPhone-first personal web app

## What's included
- Dashboard with estimated budget, recorded expenses, open tasks and selections
- Editable budget estimates and expense log
- Selections tracker with category and status
- Task list with due dates, priority and status
- Project details, notes and document/link references
- JSON export/import backup
- Responsive layout, web-app manifest, app icon and service worker for offline app shell

## Important
This first version saves data in the browser's local storage on the device. It does not sync automatically between devices, and it does not upload or store actual documents. Add links to files stored in iCloud Drive or another cloud service. Export a JSON backup regularly.

## Put it on your iPhone Home Screen (no Mac needed)
A Home Screen web app needs to be served from an HTTPS website. Easiest no-cost path is GitHub Pages:

1. If needed, create a GitHub account in Safari.
2. Create a new public repository named `homebuild-companion`.
3. Upload all four files in this folder (`index.html`, `manifest.json`, `sw.js`, `icon.svg`) to the repository root using GitHub's website.
4. In the repository, open **Settings → Pages**. Under build/deployment, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
5. Wait for GitHub Pages to publish. The site URL will look like `https://YOUR-USERNAME.github.io/homebuild-companion/`.
6. Open that URL in Safari on your iPhone. Tap **Share → Add to Home Screen**. If offered, enable **Open as Web App**, then tap Add.
7. Open the HomeBuild icon from your Home Screen and test it.

GitHub's menus may shift over time. Never upload private contracts, personal details, credentials or secrets into a public repository. This repository contains the app code only; the app's project data is saved locally in your browser.

## Basic use
- Start on Home, then use the bottom navigation.
- Tap Edit in Budget to change the sample estimates.
- Tap + Add on Tasks, Selections or expenses to create records.
- Open More to change project name/stage, keep notes, add document links and export/import backup.
- Delete or change the sample entries as you like.

## Limits of this starter version
- Local-only storage; no login or cloud sync.
- Document section stores references/links, not uploaded files.
- No push notifications or calendar integration.
- Treat all starter budget values as sample estimates and review them before relying on them.
