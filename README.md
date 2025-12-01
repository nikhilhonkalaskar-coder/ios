TBI Attendance - Flutter WebView wrapper
=======================================

What this is
-------------
A minimal Flutter project that opens https://tbiattendance.tusharbhumkar.com/ inside a WebView.

How to use
----------
1. Install Flutter SDK: https://flutter.dev/docs/get-started/install
2. (Optional) In Android Studio, choose 'Open an existing Android Studio project' and point to this folder.
3. Run: flutter pub get
4. Run on Android: flutter run -d <your-android-device-or-emulator>
5. To build an Android APK: flutter build apk --release
6. To build for iOS you will need access to macOS / Xcode or use a cloud build service (e.g. Codemagic).

Notes
-----
- This project uses the webview_flutter package.
- iOS: You may need to add keys to ios/Runner/Info.plist if accessing non-secure content (not required here as site is HTTPS).
- Android: Ensure your AndroidManifest.xml declares internet permission (the standard Flutter generated project includes it).

If you want, I can:
 - add a launcher icon,
 - add a splash screen,
 - create a full flutter project with ios/android folders (larger ZIP),
 - or prepare Codemagic configuration for building iOS in cloud.