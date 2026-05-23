# Kiaro Pro — Releases

This repository hosts the download artifacts (installers, AppImages, and
auto-update metadata) for [Kiaro Pro](https://kiaro.pro).

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

## Community

Join the Kiaro Pro community on [**Discord**](https://discord.gg/Rv2yJv2e) to
share workflows, request features, get installation help, and talk to other
users. The fastest way to influence the roadmap is to show up there.

[![Join the Discord](https://img.shields.io/discord/1507854118189011165?label=community&logo=discord&logoColor=white&color=5865F2)](https://discord.gg/Rv2yJv2e)

## Reporting issues

Please file bugs at [kiaro.pro/contact](https://kiaro.pro/contact) or ask in
[Discord](https://discord.gg/Rv2yJv2e). This repo exists only to host
downloadable artifacts and doesn't accept issues or PRs.

## License

The Kiaro Pro binaries hosted here are proprietary. See the
[End User License Agreement](https://kiaro.pro/terms) for the full terms.
