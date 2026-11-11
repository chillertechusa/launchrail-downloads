# LaunchRail downloads

Public download host for the **LaunchRail** Windows installer, by Chiller Tech Support LLC.

LaunchRail lives at **https://chillertechsupport.com/launchrail**. This repository exists for one
reason: GitHub Releases can serve the 108&nbsp;MB installer publicly and for free, so the
"Download for Windows" button on the site has somewhere real to point.

## What's here
- **Releases** — each release carries one asset: `LaunchRail-Setup-<version>.exe`.
  The site's `DOWNLOAD_URL` points at the latest one.
- Nothing else. No source code, no secrets, no config. The app's source is private
  (`chillertechusa/LaunchRail`); this repo is only a public shelf for the finished installer.

## Current status
Installer not published yet — the first release is on its way.

## How a release is made
1. Build the installer in the LaunchRail repo: `npm run installer` → `dist-installer/LaunchRail-Setup-<version>.exe`.
2. Create a GitHub Release here tagged `v<version>` and attach that `.exe`.
3. Set `DOWNLOAD_URL` in the LaunchRail site's `site/config.live.js` to the release asset URL.

---
© 2026 Chiller Tech Support LLC.
