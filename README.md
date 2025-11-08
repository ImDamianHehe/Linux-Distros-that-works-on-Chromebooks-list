# Linux-Distros-that-works-on-Chromebooks-list
This is a list of which Linux Distros works on Chromebook, including audio, and boot (Tested on Google Snappy intel CPU, x86_64)


# Chromebook Linux Guide

Welcome to the **Chromebook Linux Guide** — your hub for testing Linux distros on Chromebooks with Full ROM firmware.

---

## 🖥 Tested Hardware
- Chromebook: Google Snappy (Intel CPU)
- Firmware: **MrChromebox Full ROM required**
- Note: Some fixes may not work on all models

---

## 🔹 What This Project Covers
- Tested distros & desktop environments (KDE, GNOME, XFCE)
- Audio fixes for Ubuntu 24.04
- Boot compatibility with Full ROM
- Known limitations and warnings
- Links to original tutorials and scripts (all credit given)

---

## ✅ Tested Distros
| Distro | Desktop | Boot | Audio |
|--------|--------|------|-------|
| Pop!_OS | GNOME | ✅ | ✅ Auto |
| Arch | KDE | ✅ | ✅ Auto |
| Kubuntu | KDE | ✅ | ✅ Auto |
| Ubuntu | GNOME | ✅ | ❌ Fix Available |

---

## 🎧 Ubuntu Audio Fix (24.04)
- Original tutorial: [AskUbuntu](https://askubuntu.com/questions/1486278/how-to-install-chromebook-audio-drivers-in-ubuntu)
- Script by: [WeirdTreeThing](https://github.com/WeirdTreeThing/chromebook-linux-audio)
- Step-by-step guide included in `/docs/ubuntu-audio-fix.md`

---

## ⚠ Important Notes
- Full ROM is required — normal Chromebook firmware may not work
- Windows 10/11: Not recommended — audio and drivers do not work
- KDE distros usually detect audio automatically, but sometimes manual selection is required
- Always check the tested distros list before installation

---

## 🔗 Useful Links
- [MrChromebox Firmware Guide](https://mrchromebox.tech/#fwscript)
- [AskUbuntu Audio Tutorial](https://askubuntu.com/questions/1486278/how-to-install-chromebook-audio-drivers-in-ubuntu)
- [Chromebook Linux Audio Script](https://github.com/WeirdTreeThing/chromebook-linux-audio)
