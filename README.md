# dpmux-updates

Update channel for [DPMux](https://gl.x4.vc/root/dpmux) — the terminal built for multitasking, on Windows.

- **Install:** download [DPMuxSetup.exe](./DPMuxSetup.exe) and run it. No admin needed —
  it fetches the latest release below and installs per-user (Chrome-style).
- **`latest.json`** — the update manifest the installer and the in-app updater poll.
  `url` is relative to the manifest so mirrors work.
- **`releases/<version>/`** — one immutable directory per release (package zip +
  frozen manifest).

Published by `scripts/release.mjs` in the app repo.
