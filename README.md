# PrecisionLightingApp (GitHub Actions - Debug APK)

## How to build on GitHub (no Android Studio needed)
1. Create a new **private** repo on GitHub (e.g., PrecisionLightingApp)
2. Upload the **contents** of this folder (not the zip itself)
3. Go to **Actions** → run **Android APK (Debug)** workflow
4. After it finishes, download **PrecisionLighting-APK** artifact → install `app-debug.apk` on your device

## Local build (optional)
- Open in Android Studio
- Build → Build APK(s) → app/build/outputs/apk/debug/app-debug.apk