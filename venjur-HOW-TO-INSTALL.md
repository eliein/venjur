# Venjur PWA — Installation Guide

## What's in this folder

| File | Purpose |
|------|---------|
| habit-tracker.html | The app itself |
| manifest.json | Tells Android/Chrome this is an installable app |
| sw.js | Service worker — enables offline use |
| icon-192.png | App icon (home screen) |
| icon-512.png | App icon (splash screen) |

---

## How to install on Android

A PWA must be served from a web server — it cannot be installed by opening
the file directly from your phone's file manager. The easiest free option
is GitHub Pages (same as the Tasks app).

### Option A — New repository (fresh install)

1. Go to https://github.com and log in
2. Create a new **public** repository, e.g. "venjur"
3. Upload all 5 files from this folder
4. Go to Settings → Pages → Source: "main" branch, "/ (root)" → Save
5. Your app will be live at:
   https://YOUR-USERNAME.github.io/venjur/habit-tracker.html

### Option B — Same repository as Tasks (keep everything together)

If you already have a GitHub Pages repo for the Tasks app, you can just
upload these 5 files into a subfolder called "venjur":

1. Go to your existing repository
2. Click "Add file" → "Upload files"
3. Upload all 5 files — GitHub will place them in the root
   (or create a subfolder if you prefer)
4. Your URL will be:
   https://YOUR-USERNAME.github.io/my-tasks/habit-tracker.html

### Step — Install on Android

1. Open Chrome on your Android phone
2. Go to your GitHub Pages URL
3. Tap the three-dot menu (⋮) → "Install app" or "Add to Home screen"
4. Tap "Install" — done!

---

## Keeping your data safe

Use the Export button inside the app to download a backup .json file.
Store it in Google Drive or email it to yourself.
Use Import to restore on any device.

---

## Troubleshooting

**"Install app" not appearing?**
Make sure you are using Chrome and visiting the https:// GitHub Pages URL.

**Data not showing after reinstall?**
Use the Import button and load your backup .json file.
