# Vigyan Coaching Center - Android (Kotlin)

This ZIP contains a ready-to-open Android Studio project scaffold for the 'বিজ্ঞান কোচিং সেন্টার' app.
**I could not build the APK here** because this environment doesn't have the Android SDK / Gradle build tools.

## What is included
- Minimal Gradle Kotlin DSL files (build.gradle.kts)
- `app` module with Kotlin MainActivity, layout, and AndroidManifest
- Sample dependencies and placeholders for Room, Firebase etc. (you should add google-services.json for Firebase)

## How to build the APK (on your machine)
1. Install Android Studio and open this project directory (`File -> Open`).
2. Let Android Studio sync Gradle (it will download required SDKs & dependencies).
3. If prompted, install missing SDK components.
4. (Optional) Add `google-services.json` into `app/` if you want Firebase functionality.
5. Build -> Build Bundle(s) / APK(s) -> Build APK(s).
6. The generated APK will be in `app/build/outputs/apk/debug/app-debug.apk` (for debug builds).

## To automate APK builds (GitHub Actions)
- I can provide a GitHub Actions workflow that builds the APK on push, signs it, and uploads the artifact.
- Let me know and I'll add the workflow YAML file.

## Notes
- This scaffold is minimal to keep the ZIP small. It includes a basic MainActivity with navigation placeholders.
- For full features (Room, Firestore sync, WorkManager, Hilt), add the dependencies and files shown in the canvas.

