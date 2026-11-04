# Oulim Player

**Your videos, on any device.**

Clips on your phone, movies on your NAS, series collected on your PC — one app plays them all on phone, tablet, TV and desktop.

This repository hosts the **Windows and macOS installers** of Oulim Player. It contains no source code.

[한국어](README.ko.md)

## Download

| Platform | File | |
|---|---|---|
| Windows 10 / 11 (64-bit) | `OulimPlayer-windows-x64.msi` | Coming soon |
| macOS | `OulimPlayer-macos.dmg` | Coming soon |

All versions and release notes: [Releases](https://github.com/Raonworks2026/OulimPlayer/releases)

Phones, tablets and TVs get Oulim Player from their app store (Google Play · App Store), not from here.

## What it does

- **Plays almost anything** — opens with your device's decoder first; if that fails, it switches to FFmpeg and keeps playing from the same spot.
- **One library** — folders from this PC, your NAS and other PCs, sorted into movies, series and music, with posters and Continue watching.
- **Straight from your NAS** — SMB, SFTP, WebDAV and DLNA, played directly. No downloading, no transcoding.
- **Your PC as a NAS** — leave Oulim Player running and your phone and TV can watch this PC's videos, even away from home, with no relay server.
- **Your history stays yours** — watch history, resume points and NAS passwords stay on this device. No account, no cloud, no analytics.

## Install

### Windows

1. Download `OulimPlayer-windows-x64.msi` and run it.
2. If Windows shows **"Windows protected your PC"**, click **More info → Run anyway**.
   The installer is not code-signed yet, so SmartScreen does not recognise it.
3. On first launch, pick the folders you want in your library. To let your phone or TV watch this PC, turn on the media server and allow Oulim Player on **Private networks** when the Windows Firewall asks.

### macOS

Coming soon.

### Updates

Oulim Player for desktop checks once a day whether a newer version is out — it asks only for the latest version number and sends no device information. If there is one, it shows a link to the release here. It never installs anything by itself, and you can turn the check off with **Settings › Privacy & lock › Check for updates automatically**.

## Free and Pro

Oulim Player is free to use. Pro adds more — see the homepage for what is included.
Pro is bought separately on each platform. A Pro phone, tablet or TV that you have registered with your PC can also unlock Pro on that PC.

## Questions and problems

- **Something went wrong?** In the app, open **Settings › About & Pro › Help › Report a problem**. You see exactly what will be sent before you press Send, and nothing is sent until you do.

## Open source

Oulim Player uses [FFmpeg](https://ffmpeg.org) under the LGPL v2.1. Each release includes `ffmpeg-<version>-source.tar.xz` — the FFmpeg source and build settings we used. The full list of open-source licenses is in the app under **Settings › About & Pro › Open-source licenses**.

---

© 2026 Raonworks
