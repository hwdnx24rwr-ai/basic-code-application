# Android APK Setup

This project now includes a Capacitor Android wrapper so the billing app can run on a phone.

## Project files

- `capacitor.config.json`
- `android/`
- `app/pages/index.html`

## After editing the billing pages

Run:

```powershell
cd "C:\Users\popla\OneDrive\Desktop\hotle billing"
npm run android:sync
```

## Open Android Studio

Run:

```powershell
cd "C:\Users\popla\OneDrive\Desktop\hotle billing"
npm run android:open
```

## Build APK

Inside Android Studio:

1. Wait for Gradle sync to finish
2. Open `Build`
3. Click `Build Bundle(s) / APK(s)`
4. Click `Build APK(s)`

The APK will be created inside the Android project build output folder.

Typical output path:

`android\app\build\outputs\apk\debug\app-debug.apk`

## Important

This machine still needs Android Studio / Java to actually compile the APK.
