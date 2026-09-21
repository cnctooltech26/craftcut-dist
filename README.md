# CraftCut Studio

**Industrial CNC G-code generator for LinuxCNC** — Jali / perforation drilling,
Pocket Milling, Profile Routing and Text Engraving, all in one desktop application.

This repository hosts the **prebuilt installers**. No Python setup required.

---

## ⬇️ Download

Get the latest build from the **[Releases page](../../releases/latest)**:

| Platform | File |
|----------|------|
| Windows 10/11 (64-bit) | `CraftCut-Studio-<version>-windows-x64.exe` |
| Debian / Ubuntu (64-bit) | `craftcut-studio_<version>_amd64.deb` |

---

## Install

### Windows
Download and run the `.exe` — no Python required. If Windows SmartScreen appears,
choose **More info → Run anyway** (the build is unsigned).

### Debian / Ubuntu
```bash
sudo apt install ./craftcut-studio_<version>_amd64.deb
```
Then launch **CraftCut Studio** from your applications menu, or run
`craftcut-studio` in a terminal.

---

## What it does

- **Jali Maker** — decorative grill / jali drilling patterns (Triangular, Rhombus,
  Square) with two-sided fixture pinning and panelisation.
- **Pocket Milling** — spiral pocket toolpaths for rectangular and circular pockets.
- **Profile Routing** — inside / outside / on-line contour cuts with holddown tabs.
- **Text Engraving** — single-stroke toolpaths from 18 built-in Hershey fonts.

Every module has a live toolpath preview and exports LinuxCNC-ready `.ngc` files.

---

## Updates

CraftCut Studio checks this repository's latest release on startup and lets you know
when a newer version is available.

---

## Support

CNCToolTech · support@cnctooltech.info

Released under the GNU General Public License v3.0 (GPL-3.0).
