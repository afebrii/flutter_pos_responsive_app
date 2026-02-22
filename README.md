# Flutter POS Responsive App

A Flutter POS (Point of Sale) application with a responsive UI layout.

## Prerequisites

- Flutter SDK (Dart SDK compatible with `sdk: ^3.10.8`)
- Android Studio / VS Code (optional)

## Setup

```bash
flutter pub get
```

## Run

```bash
flutter run
```

## Build

```bash
flutter build apk
```

## Project Structure

```text
lib/
  core/
  data/
  presentation/
    auth/
    history/
    home/
    order/
    setting/
    tablet/
  main.dart
assets/
  icons/
  images/
  logo/
```

## Notes

- Entry point: `lib/main.dart`
- Default home: `LoginPage` (`lib/presentation/auth/pages/login_page.dart`)
