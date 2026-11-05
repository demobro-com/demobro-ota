# Demobro desktop updates

Public distribution repository for Demobro desktop OTA updates.

This repository contains only update feeds and downloadable release artifacts.
Application source code and build/signing workflows are maintained separately.

- [Apple Silicon feed](https://raw.githubusercontent.com/Fran-cois/demobro-ota/main/arm64/appcast.xml)
- [Intel feed](https://raw.githubusercontent.com/Fran-cois/demobro-ota/main/x86_64/appcast.xml)
- [Release downloads](https://github.com/Fran-cois/demobro-ota/releases)

The feeds currently contain no releases. A public update is added only after
its Developer ID signature, Apple notarization and Sparkle Ed25519 archive
signature have been verified. Installers must be built with this feed and its
matching public update key to receive updates.

Versioned release downloads are immutable. Builds and signing credentials are
never uploaded to this repository. GitHub's automatically generated source
archives contain only these public distribution files.
