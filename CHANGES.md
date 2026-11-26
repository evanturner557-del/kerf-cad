# Changes Made for Kerf (Apache-2.0 §4(b) Notice)

Kerf is a rebranded, browser-first distribution of DabbleCAD (Copyright © 2026 DJMcNewgent, licensed under the Apache License, Version 2.0).

## Modified & Added Files
- `src/renderer/index.html`: Updated page title, favicon, Google Fonts, CSP header, and mounted `kerf-shell.css` and `kerf-shell.js`.
- `src/renderer/ui/dashboard.js`: Updated top-left dashboard wordmark to `Kerf`.
- `src/renderer/ui/dialogs.js`: Updated welcome tour title to `Welcome to Kerf` while preserving full Apache-2.0 copyright and attribution notice in the About dialog.
- `src/renderer/kerf-shell.css` & `src/renderer/kerf-shell.js`: Added non-breaking Kerf browser studio landing overlay, quick-start fabrication guide, optional Pro Maker Vault offer, and affiliate gear links.
- `package.json`: Removed Electron desktop packaging devDependencies for pure static web build.

All original Apache-2.0 `LICENSE` and `NOTICE` files are preserved verbatim.
