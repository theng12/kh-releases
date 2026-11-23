# KH Studio apps

Free macOS apps for video production, media, music and storage. No account, no telemetry, no payment.

## Install

1. Open **[Releases](../../releases)** and download the newest `.dmg` for the app you want.
   (While a build is being prepared, an app may not have a download yet — it appears here when it does.)
2. Open the `.dmg` and drag the app into **Applications**.
3. The first time, **right-click the app → Open**, then confirm **Open** once.

That right-click is a one-time step per app on each Mac. After that the app opens normally.

## Updates

Each app updates itself. It checks the published releases and installs the new version between
jobs — no download, no re-install, no right-click again.

## Why the right-click, and why not Apple notarization

Notarization is Apple's paid stamp for distributing Mac software: Developer ID membership, about
$99 a year, plus a review of every build. These apps are free and made in-house, so they are
signed with a local certificate instead. macOS therefore has never seen the app before and asks
you to confirm once.

The app, its signature and its updates are verified by whoever installs them from the signed
release — nothing runs or updates that does not match its published SHA-256.

## Apps

| App | What it does |
|---|---|
| Story Studio KH | Long-form video production |
| Hub Studio KH | Render fleet and model jobs |
| Gateway Studio KH | Models, routing and provider keys |
| Relay Studio KH | Job relay and scheduling |
| Media Studio KH | Image and video generation |
| Music Studio KH | Music and audio |
| Library Studio KH | Channel and content library |
| Storage Studio KH | Disk and archive management |
| Printer Studio KH | Print jobs |
| Studio Launcher KH | Installs and updates the apps |
| Update Studio KH | The light updater that ships with Studio Launcher KH |

Versions, notes and download links are on the Releases page.
