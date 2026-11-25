# ✈️ TravelMate

A cross-platform travel companion app built with [Flutter](https://flutter.dev).  
Currently in its initial scaffold phase — the foundation is set and ready for features to be built on top.

---

## 📋 Table of Contents

- [About](#about)
- [Project Structure](#project-structure)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Running the App](#running-the-app)
- [Running Tests](#running-tests)
- [Dependencies](#dependencies)
- [Platform Support](#platform-support)
- [Contributing](#contributing)

---

## About

**TravelMate** is a Flutter application intended to serve as a travel companion — helping users plan trips, explore destinations, and manage their travel experience across iOS, Android, Web, macOS, Windows, and Linux.

> **Status:** 🚧 Early development — currently the default Flutter counter scaffold. Feature development is next.

---

## Project Structure

```
travelmate/
├── lib/
│   └── main.dart          # App entry point and root widget
├── test/
│   └── widget_test.dart   # Widget tests
├── android/               # Android-specific configuration
├── ios/                   # iOS-specific configuration
├── macos/                 # macOS-specific configuration
├── web/                   # Web-specific configuration
├── linux/                 # Linux-specific configuration
├── windows/               # Windows-specific configuration
├── pubspec.yaml           # Project metadata and dependencies
└── analysis_options.yaml  # Dart linting rules
```

---

## Prerequisites

Before you begin, ensure you have the following installed:

| Tool | Version | Link |
|------|---------|------|
| Flutter SDK | ≥ 3.x | [Install Flutter](https://docs.flutter.dev/get-started/install) |
| Dart SDK | ^3.11.1 | Bundled with Flutter |
| Xcode (iOS/macOS) | Latest | Mac App Store |
| Android Studio | Latest | [Download](https://developer.android.com/studio) |

Verify your environment is set up correctly:

```bash
flutter doctor
```

---

## Getting Started

### 1. Clone the repository

```bash
git clone <your-repo-url>
cd travelmate
```

### 2. Install dependencies

```bash
flutter pub get
```

---

## Running the App

### On a connected device or emulator

```bash
# List available devices
flutter devices

# Run on a specific device
flutter run -d <device-id>

# Run in debug mode (default)
flutter run

# Run in release mode
flutter run --release
```

### Web

```bash
flutter run -d chrome
```

### macOS

```bash
flutter run -d macos
```

### Hot reload & Hot restart

While the app is running:
- **Hot reload** — press `r` in the terminal (preserves state)
- **Hot restart** — press `R` in the terminal (resets state)

---

## Running Tests

```bash
# Run all tests
flutter test

# Run with verbose output
flutter test --reporter expanded
```

---

## Dependencies

### Production

| Package | Version | Purpose |
|---------|---------|---------|
| `flutter` | SDK | UI framework |
| `cupertino_icons` | ^1.0.8 | iOS-style icons |

### Development

| Package | Version | Purpose |
|---------|---------|---------|
| `flutter_test` | SDK | Widget & unit testing |
| `flutter_lints` | ^6.0.0 | Recommended lint rules |

---

## Platform Support

| Platform | Supported |
|----------|-----------|
| Android  | ✅ |
| iOS      | ✅ |
| Web      | ✅ |
| macOS    | ✅ |
| Windows  | ✅ |
| Linux    | ✅ |

---

## Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin feature/your-feature`
5. Open a Pull Request

---

## Resources

- [Flutter Documentation](https://docs.flutter.dev/)
- [Dart Language Tour](https://dart.dev/language)
- [Flutter Widget Catalog](https://docs.flutter.dev/ui/widgets)
- [pub.dev — Package Repository](https://pub.dev/)
