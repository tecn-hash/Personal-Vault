# Personal Vault

A single-file personal digital notebook and handwritten-page archive built for capturing, organizing, reading, and backing up photos of handwritten pages in one place.

## Features

- **Photo Capture & Multi-Page Upload:** Snap photos of handwritten pages or select multiple images at once to keep multi-page entries grouped together.
- **Fullscreen Zoom Reader:** Open any entry to flip between pages and zoom in on handwritten notes.
- **Categories, Pinning & Search:** Group notes by topic, pin important entries, and search across your archive.
- **Local Storage & JSON Backup:** Stores data in the browser's `IndexedDB` and supports exporting `.json` backups so you can keep copies outside your current browser session.

## Live Demo & Hosting

If GitHub Pages is enabled on the `main` branch (`/` root) with the main app file named `index.html`, the live app is available at:

`https://tecn-hash.github.io/Personal-Vault/`

## Run Locally

1. Clone or download the repository to your computer.
2. Open `index.html` (or `personal_vault.html`) directly in a modern web browser.

## Data & Backup Note

Entries and attached page images live locally in your browser's `IndexedDB`. Export a `.json` backup regularly—especially before clearing browser data or switching devices.
