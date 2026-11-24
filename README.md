# KH Studio apps

Free macOS apps for video production, media, music and storage. No account, no telemetry, no payment.

## Install

**Easiest: install Studio Launcher KH.** It installs every app and keeps them up to date —
[download it here](https://github.com/theng12/update-studio-kh/releases).

**One app on its own:** open that app's own repository from the table below, then its
**Releases** page, and download the newest `.dmg`. Open the `.dmg`, drag the app into
**Applications**, then the first time **right-click the app → Open** and confirm **Open** once.

That right-click is a one-time step per app on each Mac. After that the app opens normally.

## Updates

Each app updates itself. It reads [`release.json`](./release.json) — the signed feed in this
repository — and installs the new version between jobs. No download, no re-install, no right-click
again. Every download is checked against the SHA-256 in that feed before anything runs.

This repository holds **only the feed**. It carries no installers of its own: each app's build is
published on that app's own repository, and the feed points at it.

## Why the right-click, and why not Apple notarization

Notarization is Apple's paid stamp for distributing Mac software: Developer ID membership, about
$99 a year, plus a review of every build. These apps are free and made in-house, so they are
signed with a local certificate instead. macOS therefore has never seen the app before and asks
you to confirm once.

The app, its signature and its updates are verified by whoever installs them from the signed
feed — nothing runs or updates that does not match its published SHA-256.

## Apps

| App | What it does | Download |
|---|---|---|
| Studio Launcher KH | Every KH Studio app, installed and kept up to date. | [releases](https://github.com/theng12/update-studio-kh/releases) |
| Story Studio KH | Turns an idea into a finished, upload-ready YouTube episode. | [releases](https://github.com/theng12/story-studio-kh/releases) |
| Business Studio KH | Product photos, labels and catalogs, from one product library. | [releases](https://github.com/theng12/business-studio-kh/releases) |
| Hub Studio KH | Runs AI models on this Mac for your other apps. | [releases](https://github.com/theng12/hub-studio-kh/releases) |
| Gateway Studio KH | One address in front of your Macs and cloud models. | [releases](https://github.com/theng12/gateway-studio-kh/releases) |
| Relay Studio KH | Keeps browser accounts signed in and paired with Gateway. | [releases](https://github.com/theng12/relay-studio-kh/releases) |
| Music Studio KH | Music and audio. | [releases](https://github.com/theng12/music-studio-kh/releases) |
| Library Studio KH | Channel and content library. | [releases](https://github.com/theng12/library-studio-kh/releases) |
| Storage Studio KH | Keep your drives, NAS shares and archives mounted and tidy. | [releases](https://github.com/theng12/storage-studio-kh/releases) |
| File Studio KH | Tidy a messy folder without touching a file until you confirm. | [releases](https://github.com/theng12/file-studio-kh/releases) |
| Printer Studio KH | Print from any device to a USB-only printer. | [releases](https://github.com/theng12/printer-studio-kh/releases) |
| Wire Studio KH | Posts one caption to your social accounts. | [releases](https://github.com/theng12/wire-studio-kh/releases) |
| Displays Studio KH | Set the brightness of external monitors from the menu bar. | [releases](https://github.com/theng12/displays-studio-kh/releases) |

Versions, sizes and checksums for every app are in [`release.json`](./release.json).
