# Marginalia — EPUB reader

A single-file, mobile-first EPUB reader (`index.html`). It renders DRM-free `.epub` files with epub.js and keeps the library, reading position, highlights, bookmarks and settings in the browser (IndexedDB for book files, localStorage for everything else).

- Chrome follows Apple Books: full-bleed text, a floating menu card, bottom sheets for themes, contents, search, and bookmarks.
- Reading features follow Kindle: tap zones and swipes, pages left in chapter, time-left estimate, four-colour highlights with notes, dictionary lookup, bookmark ribbon, resume to the exact position.
- Six themes: Original, Quiet, Paper, Bold, Calm, Focus.

The file is written for the claude.ai Artifact skeleton (it has no `<html>`/`<head>` wrapper of its own); to host it elsewhere, wrap it in a document with a `viewport-fit=cover` viewport meta.
