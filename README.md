# Shelf

Shelf is a small reading app that retells the key ideas of well-known books as short, stand-alone stories. Each story takes a few minutes to read and ends with an everyday example and a one-line takeaway.

- 964 books, 12,836 stories
- Six families of shelves: Mind, Heart, Spirit, Craft, World and Music
- Save stories or whole books, write private reflections, and review saved stories later
- Light and dark themes, read-aloud, export and restore
- Installs on your phone and works offline after the first visit

**Open it:** https://djsumd.github.io/The-Shelf/

## Install on your phone

- **Android (Chrome):** open the link, tap the ⋮ menu, then **Add to Home screen** or **Install app**.
- **iPhone (Safari):** open the link, tap **Share**, then **Add to Home Screen**.

The first visit downloads all the stories (about 7 MB compressed), so do it on wifi. After that Shelf opens instantly and works without a connection.

Your progress and reflections are stored only on your own device. Use **Saved → Keep a copy** to export a backup.

## Files

| File | What it is |
|---|---|
| `index.html` | The whole app: layout, styles and code |
| `stories-0.js` to `stories-2.js` | The story text, split into files of about 7 MB |
| `manifest.webmanifest`, `icons/` | What lets the app install to a home screen |
| `sw.js` | The service worker that makes it work offline |

When you update any file, change `VERSION` at the top of `sw.js` so installed copies pick up the new version.

## About the stories

The stories were written and fact-checked with the help of AI. A lot of care went into accuracy, but mistakes will remain. Treat each story as a doorway into the book, not a substitute for it. Nothing here is medical, legal or financial advice.

All rights in the original works belong to their authors and publishers. Shelf is not affiliated with or endorsed by any of them.

**Corrections and removal requests:** if you spot an error, or you hold rights in a book and want it removed, please [open an issue](https://github.com/DjSumd/The-Shelf/issues) and it will be dealt with promptly.

## Licence

The app code is released under the MIT Licence (see `LICENSE`). The licence does not cover the original books or grant any rights in them.
