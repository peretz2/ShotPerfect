# ShotPerfect — Screenshot Design Tool

An iOS app for creating professional, App Store-ready screenshot designs with 17 customizable templates and a liquid glass UI.

<!-- <p align="center">
  <img src="screenshots/screenshot1.png" width="200">
  <img src="screenshots/screenshot2.png" width="200">
  <img src="screenshots/screenshot3.png" width="200">
</p> -->

## Tech Stack

| Layer | Technology |
|-------|-----------|
| **UI** | SwiftUI (Liquid Glass design) |
| **Rendering** | Core Graphics, ImageRenderer |
| **Data** | SwiftData |
| **Payments** | RevenueCat ($6.99 lifetime) |
| **Architecture** | MVVM |

## Key Features

- **17 Professional Templates** — Pre-designed layouts optimized for App Store screenshots
- **Liquid Glass UI** — Translucent, layered surfaces with blur and depth effects
- **Custom Text & Badges** — Add titles, subtitles, and promotional badges
- **Device Frames** — Wrap screenshots in realistic iPhone frames
- **Background Customization** — Gradients, colors, and patterns
- **Export Options** — High-resolution export for App Store (6.5" and 5.5" sizes)
- **One-Time Purchase** — $6.99 lifetime unlock, no subscriptions

## Architecture

```
ShotPerfect/
├── Models/          # Template and project data models
├── Views/           # SwiftUI views with liquid glass styling
├── ViewModels/      # Template rendering and export logic
├── Services/        # RevenueCat, image processing
└── Utils/           # Color extensions, image helpers
```

## Links

- [Support](https://peretz2.github.io/ShotPerfect/support.html)
- [Privacy Policy](https://peretz2.github.io/ShotPerfect/privacy.html)
- [Terms of Use](https://peretz2.github.io/ShotPerfect/terms.html)
