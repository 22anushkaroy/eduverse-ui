# EduVerse — Flutter UI

Clean and modern Flutter UI for an educational platform.

## Structure
```
lib/
  main.dart
  screens/
    login_screen.dart
    signup_screen.dart
  widgets/
    brand_header.dart
    google_button.dart
```

## Run
```
flutter pub get
flutter run
```

## Notes
- Frontend UI only — no backend, no auth.
- Theme: blue (#4F46E5) + light purple (#A78BFA / #EDE9FE) on a soft background.
- Navigation uses `Navigator.push` (Login → Signup) and `Navigator.pop` (Signup → Login).
