# AppForceps Releases

Public distribution channel for **AppForceps** — an iOS Data Container Editor built with Tauri.

The source code lives in a private repository
(`kusumotoa/AppForceps`). This repository hosts the public release artifacts
(DMG, `latest.json`) so they can be installed via Homebrew or downloaded
directly.

## Install

### Homebrew (recommended)

```bash
brew tap kusumotoa/tap
brew install --cask appforceps
```

### Manual download

Pick the latest tag from
[Releases](https://github.com/kusumotoa/AppForceps-releases/releases) and grab
the `.dmg` asset.

## Updates

The Tauri updater reads `latest.json` from the latest release tag here and
prompts the user when a newer version is available.

## License

AppForceps is released under the [MIT License](./LICENSE). The compiled binary
links against many open-source libraries; their notices are listed in
[NOTICE.md](./NOTICE.md).
