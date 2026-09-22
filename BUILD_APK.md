# Build Foqus v6 APK

## Android Studio
1. Open this folder as an Android Studio project.
2. Let Gradle sync.
3. Select `app`.
4. Choose `debug` for a test APK or `release` for a release build.
5. Build APK from the Build menu.

## Command line
If Gradle/Android SDK are installed:

Linux/macOS:
`./gradlew :app:assembleDebug`

Windows:
`gradlew.bat :app:assembleDebug`

Debug APK:
`app/build/outputs/apk/debug/app-debug.apk`

Release APK:
`app/build/outputs/apk/release/app-release.apk`

A release APK should be signed with your own keystore before distribution.

## Device permissions
After installation, Foqus needs explicit user activation for:
- Accessibility Service
- Usage Access (statistics)
- Notification Access (notification blocking)

## Infinix/XOS
For reliable long-running blocking, check the device's battery/background settings and allow Foqus to run without aggressive background restriction.
