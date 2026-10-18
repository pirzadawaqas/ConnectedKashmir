# Personal LifeOS — Android APK & Mobile Install Guide

This bundle contains the complete Android WebView project (`com.personal.lifeos`) pre-loaded with your updated **Grid Edition** app (`app/src/main/assets/index.html`), including:
- **Bento Grid UI**
- **Daily Schedule & Time-Blocker**
- **Full Journaling Studio** (date, exact time, mood, energy, weather, templates)
- **Automatic `@Person` Thought Extractor & People Dossier**
- **Money & Expense Tracker**
- **Pomodoro Timer, Tasks & Habit Matrix**
- **Master-Password Encrypted Vault**

## Option 1: Instant Install on Android (No Computer Needed)
1. Copy `app/src/main/assets/index.html` (or `personal-dashboard.html`) to your Android phone.
2. Open it in **Chrome** or **Brave** on Android.
3. Tap the **⋮ Menu** in the top-right corner and select **Add to Home screen** / **Install app**.
4. It will appear on your home screen as **Personal LifeOS** and store all data locally on your device.

## Option 2: Compile the Native `.apk` File
### Using Android Studio / Command Line:
1. Extract this `.zip` folder and open it in **Android Studio** (or run `gradle assembleDebug` in terminal).
2. Your installable APK will be generated at:
   `app/build/outputs/apk/debug/app-debug.apk`

### Using GitHub Actions (Zero Local Setup):
1. Upload this folder to a private GitHub repository.
2. Open the **Actions** tab in GitHub — the included `.github/workflows/build-apk.yml` workflow will automatically compile and provide `app-debug.apk` for download.
