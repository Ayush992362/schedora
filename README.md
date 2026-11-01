# Schedora

A polished Flutter student companion for courses and assignments. Includes Firebase email/password sign-up and login, Home, expandable course details, interactive assignment completion, and a student profile with logout. Course and assignment sample data remains local.

## Run

Install Flutter and Android Studio, connect an Android device or start an emulator, then run flutter pub get and flutter run.

## Firebase setup

The app initializes Firebase with the FlutterFire generated options in `lib/firebase_options.dart` and uses Firebase Authentication for email/password sign-up and login. Configured platforms are Android and web. To refresh Firebase platform configuration, run `dart pub global run flutterfire_cli:flutterfire configure --project=schedora-f69ea --platforms=android,web` from the project root, then run `flutter pub get`.

Enable **Email/Password** under Firebase Authentication → Sign-in method. Course and assignment sample data remains local.
