# Shelf

Famous books as short, stand-alone stories. One idea per page, no waffle, no streaks.

731 books and 10,257 stories, with a daily story, reflections, saved stories, spaced review, and backup and restore. It installs on a phone like an app and works offline.

**Live app:** `https://<your-username>.github.io/shelf/`

## Publish with GitHub Pages

1. Create a new **public** repository called `shelf` on GitHub (free GitHub Pages needs a public repository).
2. Click **Add file > Upload files** and drag in everything in this folder, so `index.html` sits at the top level: `index.html`, `stories-0.js`, `stories-1.js`, `stories-2.js`, `manifest.webmanifest`, `sw.js`, the four icon files and this README. Each file is under GitHub's 25 MB web-upload limit. Commit.
3. Go to **Settings > Pages**, set **Source** to *Deploy from a branch*, choose `main` and `/ (root)`, and save.
4. After a minute or two it's live at `https://<your-username>.github.io/shelf/`.

## Install it on a phone

- **iPhone:** open the link in Safari (not inside Instagram, Facebook or another app's browser), tap Share, then **Add to Home Screen**.
- **Android:** open the link in Chrome, tap the three-dot menu, then **Install app** or **Add to Home screen**.

The first visit downloads about 19 MB once; after that it opens from the phone, online or not.

On an iPhone, the home-screen app keeps its own storage, separate from Safari. Always open it from the icon, or your saved stories and reflections will seem to be missing.

## Your reading history

Each person's saved stories, reflections and progress live only in their own browser, so sharing the link shares the books, not your notes. To move your own history into this version, use **Full backup** in the version you've been using, then **Restore** here.

Writing new books with Claude only works in the Claude version, so those buttons are hidden here.

## Updating

Upload the changed files and commit. Installed copies check for updates whenever they open with a connection and switch to them the time after. If you add or rename files, or change the icons, also change `VERSION` at the top of `sw.js` (for example `shelf-v2`) and add any new files to the list below it.
