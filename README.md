
<<<<<<< HEAD
## Expense Tracker (Flutter)
=======
# Expense_Tracker

A simple, responsive expense tracking app built with Flutter. Add expenses with title, amount, date, and category; view a list of expenses and a summary chart. Dark mode is supported via system theme.

### Features

- **Add expenses**: Title, amount (validated), date picker, and category selection
- **Responsive UI**: Adapts layout for wide screens
- **Dark mode**: Honors system theme with custom color schemes
- **Summary view**: Chart components to visualize spending (see `widgets/chart`)
- **Stateful form**: Inline validation and friendly error dialogs

### Tech Stack

- **Framework**: Flutter (Material 3)
- **Language**: Dart
- **Packages**: `intl`, `uuid`, `cupertino_icons`

### Project Structure

```
lib/
  main.dart                # App entry, themes, routes
  models/expense.dart      # Expense model and categories
  widgets/
    expenses.dart          # Main screen
    new_expense.dart       # Add expense bottom sheet/dialog
    expenses_list/         # List and list items
    chart/                 # Chart and chart bars
```

## Getting Started

<<<<<<< HEAD
### Prerequisites

- Flutter SDK installed and on PATH (`flutter --version`)
- A recent Android Studio or Xcode for platform tooling (as needed)
- Device or emulator/simulator

### Install dependencies

```bash
flutter pub get
```

### Run the app

```bash
flutter run
```

Select your target device when prompted, or preselect one:

```bash
flutter devices
flutter run -d <device_id>
```

## Build

### Android (APK)

```bash
flutter build apk --release
```

### iOS (IPA)

```bash
flutter build ios --release
```

Open the Xcode workspace for code signing if needed.

### Web

```bash
flutter build web --release
```

### Desktop

```bash
# Windows
flutter build windows --release

# macOS
flutter build macos --release

# Linux
flutter build linux --release
```

## Testing

Run widget and unit tests:

```bash
flutter test
```

## Code Style

- Lints: configured via `analysis_options.yaml` (uses `flutter_lints`)
- Format all Dart files:

```bash
dart format .
```

## Configuration

Key settings live in `pubspec.yaml`:

- App name: `my_app`
- Version: `1.0.0+1`
- SDK: Dart `^3.8.0`

## Screenshots

Add screenshots to `my_app/web/icons` or a new `assets/screenshots/` folder and reference them here.

## Troubleshooting

- **Android Gradle issues**: Run `flutter clean && flutter pub get` and try again.
- **iOS CocoaPods**: From `ios/`, run `pod install` after `flutter pub get`.
- **Windows PowerShell policy**: If scripts are blocked, run PowerShell as Administrator and execute:

```powershell
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
```

- **Stuck builds**: Ensure only one emulator/simulator/device is attached and rerun `flutter run -v` for verbose logs.


