# AppForceps Releases

Public distribution channel for **AppForceps** — an iOS / Android App Data
Container Editor.

This repository hosts the public release artifacts
(DMG, `latest.json`) so they can be installed via Homebrew or downloaded
directly.

## Requirements

- **A Mac with Apple Silicon (arm64).** Intel Macs are not supported — the app
  binary is arm64 only, and it will not launch on an Intel Mac.
- macOS 13 (Ventura) or later.
- To work with iOS Simulators: **Xcode** (the full app, not only the Command
  Line Tools), selected with `xcode-select`.
- To work with Android devices / emulators: Android SDK Platform Tools (`adb`).

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
