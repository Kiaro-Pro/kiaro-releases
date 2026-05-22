# Kiaro Pro — Releases

This repository hosts the **public download artifacts** (installers, AppImages, and
auto-update metadata) for [Kiaro Pro](https://kiaro.pro).

The application source code lives in a separate private repository.

## Where to download

Official downloads with installation instructions live at
[**kiaro.pro/download**](https://kiaro.pro/download).

You can also grab raw binaries directly from the
[**Releases**](https://github.com/Kiaro-Pro/kiaro-releases/releases) tab on this
repository.

## What's in each release

Every tagged release ships three platform builds:

| Platform | Files |
|----------|-------|
| macOS    | `.dmg` (universal) and `.zip` |
| Windows  | `.exe` (NSIS installer) and a portable `.exe` |
| Linux    | `.AppImage` and `.deb` |

`latest-mac.yml`, `latest.yml`, and `latest-linux.yml` are auto-update manifests
read by the in-app updater. Don't edit them by hand — they're produced by CI.

## Reporting issues

Please file bugs at [kiaro.pro/contact](https://kiaro.pro/contact). This repo
exists only to host downloadable artifacts and doesn't accept issues or PRs.

## License

The Kiaro Pro binaries hosted here are proprietary. See the
[End User License Agreement](https://kiaro.pro/terms) for the full terms.
