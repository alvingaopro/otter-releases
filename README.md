# Otter downloads

Official compiled releases of Otter. This repository contains distribution files;
Otter source code and build workflows are maintained separately.

[Download the latest release](https://github.com/alvingaopro/otter-releases/releases/latest).

- **Mac app:** `Otter_<version>_macos_arm64.dmg` for Apple silicon. Drag Otter to Applications.
- **Command-line tools:** `otter-<version>-<platform>.tar.gz` contains `otter` and `otterd`.
- **Claude runtime:** platform-specific worker archives and SHA-256 checksums, installed by Otter.
- **App updates:** `latest.json` names the signed `.app.tar.gz` update and its signature.

New app builds check this repository for updates without a GitHub login. Apps built
with the previous private repository endpoint need a one-time manual installation
of the first release built with this public endpoint. The initial mirrored
v0.7.126 build still uses the previous endpoint.

The Mac app is not yet notarized. On first launch, macOS may require
System Settings → Privacy & Security → Open Anyway.
