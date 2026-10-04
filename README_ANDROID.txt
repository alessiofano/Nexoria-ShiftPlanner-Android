NEXORIA SHIFTPLANNER PRO - ANDROID NATIVE 1.6

Native Android project (Java, no third-party runtime libraries).
Features included:
- Monthly shift calendar
- 5-language selector: IT / EN / ES / FR / DE
- Regular shifts + on-call availability on the same day
- Separate overtime / on-call activation entries
- Vacation fixed at 6 paid hours per day
- Monthly summary
- Offline autosave
- .NSP import/export
- CSV export
- NexoriaLabPro blue/violet branding and app icon

BUILD:
Open this folder in Android Studio, allow Gradle sync, then Build > Generate App Bundles or APKs > Generate APKs.
Minimum Android: 8.0 (API 26). Target/compile SDK: 35.

No INTERNET permission is requested.

AUTOMATED APK BUILD
A GitHub Actions workflow is included at .github/workflows/android-build.yml.
It installs JDK 17 + Android SDK 35 + Gradle 8.9 and compiles an installable signed debug APK.
The artifact produced is app/build/outputs/apk/debug/app-debug.apk.
