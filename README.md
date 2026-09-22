# Foqus Blocker v6

APK-ready native Android project.

## v6 focus
- Stable Gradle/Android configuration
- Debug and release build types
- Java 17 / Kotlin JVM target
- Jetpack Compose UI
- Five-tab app structure
- Focus sessions
- App blocking
- Usage statistics
- Scheduled blocking
- Notification blocking
- Biometric/device-credential gate
- Emergency 60-second unlock
- First-run onboarding
- Accessibility enforcement
- GitHub Actions workflow that can build the debug APK remotely

This repository intentionally does not include a signing keystore.

Important Android limitation:
A normal consumer application cannot guarantee absolute anti-bypass enforcement on every Android OEM. Accessibility, Usage Access and Notification Access require explicit user activation.
