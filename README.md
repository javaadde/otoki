# Otoki

Otoki is an offline-first Android app for pairing an image with a short voice clip and sharing the result.

## MVP

- Import and crop an image into a regular 512×512 WebP sticker.
- Record or import audio, trim it to a short clip, and preview it with the image.
- Save projects locally.
- Export a playable MP4 or add a regular sticker pack to WhatsApp.
- Keep native sound-sticker export disabled unless an officially supported integration is verified.

## Project status

Initial project scaffold in progress. Product requirements, architecture, and design notes are in `docs/`. This project currently has no backend, accounts, analytics, or cloud processing.

## Build

The Android app uses Kotlin, Jetpack Compose, Material 3, Room, and AndroidX media components. Once the Gradle wrapper is available:

```sh
./gradlew assembleDebug
```

See [docs/PRD.md](docs/PRD.md), [docs/architecture.md](docs/architecture.md), and [docs/design.md](docs/design.md) for scope and implementation decisions.
