# ScholarSparkHub Android wrapper

This project opens the existing ScholarSparkHub website in an Android WebView.

Website: https://scholar-spark-hub-99.lovable.app

## Build APK using only your phone (GitHub Actions)

1. Create a new **public or private** GitHub repository named `ScholarSparkHub-Android`.
2. Extract this ZIP on your phone using Files/ZArchiver.
3. In the repository on GitHub, use **Add file > Upload files** and upload the *contents* of this folder (not the ZIP itself). Include the hidden `.github` folder if your file manager shows it.
4. Commit the files to the `main` branch.
5. Open the repository's **Actions** tab. If GitHub asks, enable Actions.
6. Select **Build ScholarSparkHub APK** and tap **Run workflow** (or wait for the first push build).
7. When the run finishes successfully, open it and download the artifact named `ScholarSparkHub-debug-apk`.
8. Extract the artifact ZIP and install `app-debug.apk` on your Android phone. If Android blocks it, allow your browser/file manager to install unknown apps.

## Important

- This is an online WebView wrapper; an internet connection is required.
- The website and its login/backend remain hosted by Lovable.
- The GitHub Actions workflow creates a **debug-signed APK** for testing and personal installation. A release APK for public distribution needs a separately managed signing key.
- Never share your GitHub password or signing key.
