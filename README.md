# PhotoMagic AI — Android starter project

A new Java Android Studio project targeting Android 13 (API 33).

## Included
- Photo picker using Android's system photo picker
- Preview of selected photo
- Basic on-device brightness/contrast auto-correction
- Undo to original
- Save edited image to Pictures/PhotoMagicAI
- UI entries for automatic background people removal, body slimming and background editing

## Important AI feature status
The people-removal, body-slimming and background-editing buttons currently explain that an AI model must be integrated. They do **not** perform those operations yet. Real automatic removal requires person detection plus image inpainting; body shaping needs person/pose-aware warping. These are not honestly achievable with a simple filter or UI-only code.

## Build
1. Install Android Studio.
2. Extract this ZIP.
3. Open the `PhotoMagicAI` folder in Android Studio.
4. Let Gradle sync. Use JDK 17.
5. Build > Build Bundle(s) / APK(s) > Build APK(s).
6. Install the generated APK on an Android 13 phone.

Compile SDK 35 is used; target SDK is 33 (Android 13 compatibility). The app's minimum SDK is 23.
