# Carpooling 🚗

A Flutter app for sharing a car trip between several passengers — browse a trip, see the driver and co-passengers, and review past rides.

## Features

- **Trip details** — route (home → workplace), car details and driver information
- **Ride details** — co-passenger list and ride breakdown
- **History** — previously taken rides
- **Responsive layouts** that hold up across phone sizes
- **Local persistence** so state survives app restarts

## Tech Stack

| Layer | Choice |
|---|---|
| Framework | Flutter (Dart) |
| State management & routing | [GetX](https://pub.dev/packages/get) |
| Local storage | [GetStorage](https://pub.dev/packages/get_storage) |
| Responsive sizing | [flutter_screenutil](https://pub.dev/packages/flutter_screenutil) |

## Project Structure

```
lib/
├── main.dart
├── trip_details/          # trip screen + car / route widgets
│   ├── trip_details_screen.dart
│   └── widgets/
├── ride_details/          # ride screen
├── history/               # past rides
└── widgets/               # shared widgets (driver, co-passenger, history cards)
```

## Getting Started

```bash
flutter pub get
flutter run
```

Requires Flutter with Dart SDK `>=2.19.4 <3.0.0`.

## Screenshots

<!-- Add 3–4 screenshots here — this is the first thing anyone looks at -->

---

Built by [Youssef Ali Emam](https://github.com/YOUSSEFALIEMAM)
