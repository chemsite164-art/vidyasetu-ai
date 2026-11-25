# VidyaSetu AI — One-Click Cloud APK Builder (GitHub Actions)

This project wraps the verified **VidyaSetu AI** educational platform (`app/src/main/assets/index.html`) into a native Android WebView application with file-upload support, Android Print/PDF support, and automatic cloud `.apk` compilation via GitHub Actions.

## How to Get Your Installable APK (No Android Studio Needed)
1. Unzip `vidyasetu-apk-builder.zip` on your computer or phone.
2. Create a new repository on [GitHub](https://github.com/new) (public or private).
3. Upload all files inside `vidyasetu-apk-builder/` (make sure the `.github/workflows/build-apk.yml` folder is included) and commit to the `main` branch.
4. Open the **Actions** tab in your GitHub repository — the **Build Android APK** workflow starts automatically (or click **Run workflow**).
5. After ~2–3 minutes, open the completed workflow run and download **VidyaSetu-AI-Debug-APK** under **Artifacts**.
6. Extract `app-debug.apk`, transfer it to your Android phone, and install it (enable *Install unknown apps* when prompted).

## Local Build Option (Android Studio)
Open the `vidyasetu-apk-builder/` folder directly in Android Studio and select **Build → Build Bundle(s) / APK(s) → Build APK(s)**.
