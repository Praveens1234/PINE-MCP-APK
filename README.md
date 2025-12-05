# TradingView Pine Script Validator (Android)

## 📱 The "No PC" Build Instructions

Since this is a mobile-first project and you don't have a PC to build the APK, we use **GitHub Actions** to build it for you in the cloud.

### Step 1: Upload to GitHub
1. Create a new repository on GitHub (you can do this from your phone browser).
2. Upload all the files in this folder to that repository.
   - If you downloaded a zip, unzip it first, then upload the contents.

### Step 2: Automatic Build
1. Once uploaded, go to the **"Actions"** tab in your repository.
2. You will see a workflow named **"Build Android APK"** running (yellow circle).
3. Wait for it to turn green (Success).

### Step 3: Download APK
1. Tap on the successful workflow run.
2. Scroll down to the **"Artifacts"** section.
3. Tap **"app-release"**.
4. GitHub will download a zip file containing your APK.
5. Extract it and install `app-release.apk` on your phone!

## 🚀 Features

- **Butter Smooth UI:** Built with Flutter for 60fps performance.
- **Glassmorphism Design:** Modern dark theme with neon accents.
- **Headless Automation:** Runs a hidden Desktop browser to interact with TradingView's compiler.
- **Mobile First:** Designed specifically for touch screens.

## 🛠️ Tech Stack

- **Framework:** Flutter (Dart)
- **Engine:** `flutter_inappwebview` (Headless Chromium)
- **State Management:** Provider
- **Automation:** Custom JavaScript Injection (Ported from Playwright)
