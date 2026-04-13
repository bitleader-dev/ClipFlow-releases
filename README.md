<p align="center">
  <img src="assets/icon-256.png" width="128" alt="ClipFlow Icon" />
</p>

<h1 align="center">ClipFlow</h1>

<p align="center">
  <strong>A modern clipboard manager for Windows 11</strong>
</p>

<p align="center">
  <a href="https://github.com/bitleader-dev/ClipFlow-releases/releases/latest">
    <img src="https://img.shields.io/github/v/release/bitleader-dev/ClipFlow-releases?style=flat-square" alt="Latest Release" />
  </a>
  <a href="https://github.com/bitleader-dev/ClipFlow-releases/releases/latest">
    <img src="https://img.shields.io/github/downloads/bitleader-dev/ClipFlow-releases/total?style=flat-square" alt="Downloads" />
  </a>
  <img src="https://img.shields.io/badge/platform-Windows%2011-blue?style=flat-square" alt="Platform" />
  <img src="https://img.shields.io/badge/.NET-9.0-purple?style=flat-square" alt=".NET" />
</p>

<p align="center">
  <a href="README.ko.md">🇰🇷 한국어</a>
</p>

---

## About

ClipFlow is a lightweight clipboard manager that lives in your system tray. It automatically captures everything you copy — text, images, files, and more — and lets you access, search, and reuse your clipboard history instantly.

Built with WinUI 3 for a native Windows 11 experience.

## Features

- **Clipboard History** — Automatically saves text, images, files, and rich content
- **Strip Card UI** — Visual card-based interface for quick browsing
- **Pin & Favorites** — Keep important items always accessible
- **Tags & Search** — Organize and find clips with tags and full-text search
- **Drag & Drop** — Drag any clip directly into other apps
- **Multi-format Support** — Text, RTF, HTML, images, file lists, and more
- **OCR** — Extract text from images (powered by Windows OCR)
- **Paste Stack** — Queue multiple items and paste them in sequence
- **Rules Engine** — Auto-tag or auto-pin clips based on custom rules
- **Keyboard Shortcuts** — Global hotkeys for quick access
- **Auto-update** — Seamless background updates via Velopack

## Screenshots

<!-- TODO: Add screenshots -->
<!--
<p align="center">
  <img src="assets/screenshot-main.png" width="600" alt="ClipFlow Main UI" />
</p>
-->

## Installation

### Installer (Recommended)

1. Download **`ClipFlow-win-Setup.exe`** from the [latest release](https://github.com/bitleader-dev/ClipFlow-releases/releases/latest)
2. Run the installer — no admin required
3. ClipFlow installs to `%LocalAppData%\ClipFlow\` and creates shortcuts on Desktop and Start Menu

### Portable

1. Download **`ClipFlow-win-Portable.zip`** from the [latest release](https://github.com/bitleader-dev/ClipFlow-releases/releases/latest)
2. Extract to any folder
3. Run `ClipFlow.exe`

> **Note:** The portable version does not support auto-updates.

<!--
### Microsoft Store

<a href="https://apps.microsoft.com/store/detail/TODO">
  <img src="https://get.microsoft.com/images/en-us%20dark.svg" width="200" alt="Get it from Microsoft Store" />
</a>
-->

## System Requirements

- Windows 11 22H2 or later (Build 22621+)
- x64 processor
- ~150 MB disk space

## Uninstall

- **Installer version**: Settings > Apps > Installed apps > ClipFlow > Uninstall
- **Portable version**: Simply delete the folder

App data is stored in `%LocalAppData%\ClipFlow\` — delete this folder to remove all settings and history.

## Support

Found a bug or have a feature request? Please open an [issue](https://github.com/bitleader-dev/ClipFlow-releases/issues).

## Legal

- [Privacy Policy](docs/PRIVACY.md)
- [Terms of Service](docs/TERMS.md)
- [License](LICENSE)

---

<p align="center">
  &copy; 2026 BitLeader inc. All rights reserved.
</p>
