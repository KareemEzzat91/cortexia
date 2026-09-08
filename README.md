# cortexia

A beautiful Flutter app — UI-first, designed for rapid iteration.

![App preview](docs/screenshots/screen1.png)

---

## Overview

Cortexia is a Flutter application scaffold. This README contains usage instructions, development tips, and placeholders for screenshots that you can upload to the repository so the README shows your app's visual identity.

## Features

- Clean, responsive UI built with Flutter
- Fast hot-reload workflow
- Ready for Android & iOS
- Screenshots and showcase section (update images in `docs/screenshots/`)

## Screenshots

Add your screenshots to the `docs/screenshots/` folder and name them `screen1.png`, `screen2.png`, `screen3.png` (or use .jpg/.webp). Once uploaded, this README will display them automatically.

![Screenshot 1](docs/screenshots/screen1.png)

![Screenshot 2](docs/screenshots/screen2.png)

![Screenshot 3](docs/screenshots/screen3.png)

Tip: Use a GIF for interactive previews and name it `demo.gif` in the same folder.

## Quick Start

1. Clone the repo

   git clone https://github.com/KareemEzzat91/cortexia.git
   cd cortexia

2. Install dependencies

   flutter pub get

3. Run on an emulator or device

   flutter run

4. Create screenshots

   - On Android: Use `adb exec-out screencap -p > screen1.png`
   - On iOS Simulator: Use `xcrun simctl io booted screenshot screen1.png`

5. Upload screenshots to `docs/screenshots/` using the GitHub web UI or add them and push via git.

## Development

- Use `flutter analyze` and `flutter test` as part of CI.
- Keep UI assets optimized (prefer webp for smaller size).

## Contributing

PRs welcome — please open issues for major changes. Keep commits small and add a screenshot if your change affects UI.

## License

MIT
