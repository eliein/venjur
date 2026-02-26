# Tasks PWA — Installation Guide

## What's in this folder

| File | Purpose |
|------|---------|
| 4-todo.html | The app itself |
| manifest.json | Tells Android/Chrome this is an installable app |
| sw.js | Service worker — enables offline use |
| icon-192.png | App icon (home screen) |
| icon-512.png | App icon (splash screen) |

---

## How to install on Android

A PWA must be served from a web server — it cannot be installed by opening the file
directly from your phone's file manager. The easiest free option is GitHub Pages.

### Step 1 — Create a free GitHub account
Go to https://github.com and sign up (free).

### Step 2 — Create a new repository
1. Click the "+" icon → "New repository"
2. Name it anything, e.g. "my-tasks"
3. Set it to **Public**
4. Click "Create repository"

### Step 3 — Upload the files
1. Click "uploading an existing file"
2. Drag and drop ALL five files from this folder:
   - 4-todo.html
   - manifest.json
   - sw.js
   - icon-192.png
   - icon-512.png
3. Click "Commit changes"

### Step 4 — Enable GitHub Pages
1. Go to your repository → Settings → Pages
2. Under "Source", select "Deploy from a branch"
3. Choose branch: "main", folder: "/ (root)"
4. Click Save
5. Wait ~1 minute, then your app is live at:
   https://YOUR-USERNAME.github.io/my-tasks/4-todo.html

### Step 5 — Install on Android
1. Open Chrome on your Android phone
2. Go to your GitHub Pages URL above
3. Tap the three-dot menu (⋮) in the top right
4. Tap "Add to Home screen" or "Install app"
5. Tap "Install" — done!

The app will appear on your home screen with its own icon, open
full-screen without browser bars, and work offline.

---

## Keeping your data safe

Use the Export button inside the app regularly to download a backup .json file.
Store it somewhere safe (Google Drive, email to yourself, etc.).
If you ever reinstall the app or switch phones, use the Import button to restore.

---

## Troubleshooting

**"Add to Home screen" option not appearing?**
Make sure you are using Chrome (not Firefox or Samsung Browser) and that you are
visiting the https:// GitHub Pages URL, not a local file.

**App not updating after you change the HTML?**
In Chrome, go to Settings → Site Settings → find your URL → Clear & reset.
Then reload the page and reinstall.
