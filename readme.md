# Munim+ POS — Releases

This repository hosts official releases of **Munim+**, a desktop Point-of-Sale application for multi-franchise businesses.

> Source code is maintained in a private repository. This repo is used exclusively for distributing builds and enabling in-app auto-updates.

---

## Download

Go to the [Releases](../../releases) page and download the installer for your platform.

| Platform | File | Notes |
|----------|------|-------|
| Windows | `munim-plus-x.x.x-setup.exe` | NSIS installer, creates desktop shortcut |
| Linux (Debian/Ubuntu) | `munim-plus_x.x.x_amd64.deb` | Install with `sudo dpkg -i` |

---

## Installation

### Windows

1. Download `munim-plus-x.x.x-setup.exe`
2. Run the installer and follow the prompts
3. Launch **Munim+** from the desktop shortcut or Start Menu

### Linux (Debian / Ubuntu)

```bash
sudo dpkg -i munim-plus_x.x.x_amd64.deb
```

Then launch from your application menu or run:

```bash
munim-plus
```

---

## Auto-Updates

Munim+ checks for updates automatically on startup and via the **Check for Updates** button in the sidebar. When a new version is available, a notification is shown inside the app.

---

## Requirements

| | Minimum |
|---|---|
| OS (Windows) | Windows 10 or later (64-bit) |
| OS (Linux) | Ubuntu 20.04 / Debian 11 or later (64-bit) |
| RAM | 2 GB |
| Disk | 300 MB free space |
| Network | Required for API connectivity |

---

## Support

For issues or support, contact your system administrator or the Netset Software Solutions team.
