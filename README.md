# 8D Inventory — downloads

Public APK downloads for **8D Inventory**, the Android wrapper Trevor runs on his Pixel.

App source and the Capacitor shell live in the private [trevordauc/projects](https://github.com/trevordauc/projects) repo. This repository is downloads only: release metadata and signed APKs. It is not the app source.

**Install on a Pixel:** open [8DInventory-1.5.68-b4.apk](https://github.com/trevordauc/8DInventory-releases/releases/download/android-1.5.68-b4/8DInventory-1.5.68-b4.apk) on the phone (or grab it from [Releases](../../releases/latest)). Android will offer it as an update over an older 8D Inventory install. Same signing key; do not uninstall first.

The in-app header and Settings show the live web app version (currently 1.5.68). `versionCode` 4 is the Android build counter used for updates.

Settings → **Check for updates** in the app reads [`releases/app-version.json`](releases/app-version.json) from this public repo and can download a newer APK from the matching GitHub release.
