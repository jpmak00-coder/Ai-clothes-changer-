# AI Clothes Changer

Flutter starter project for an AI clothes-changing app.

## Features
- Photo picker from gallery/camera
- Outfit category selector
- Clothing description input
- Generate screen with mock processing state
- Before/after-style result placeholder
- Clean Material 3 UI

## Important
The project is intentionally API-provider neutral. Connect your preferred virtual try-on/image-editing backend in `lib/services/try_on_service.dart`.

For a production app, the AI API key must stay on your server/backend, never inside the Flutter app.

## Run
1. Install Flutter.
2. Run `flutter pub get`.
3. Run `flutter run`.

This is a starter app; the AI generation endpoint is a stub until you connect a provider.
