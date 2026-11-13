# ScholarSparkHub Android wrapper

This Android project opens the existing ScholarSparkHub app in a native Android WebView.

Website: https://scholar-spark-hub-99.lovable.app

## Build using GitHub Actions

1. Extract this ZIP on your phone or computer.
2. Open your GitHub repository `ScholarSparkHub-Android`.
3. Choose **Add file → Upload files**.
4. Upload the *contents* of this extracted folder (including the hidden `.github` folder), not the ZIP itself.
5. Commit the files to the `main` branch.
6. Open the repository's **Actions** tab.
7. Select **Build ScholarSparkHub APK** and tap **Run workflow** if it has not started automatically.
8. When the run completes, open it and download the artifact named `ScholarSparkHub-debug-apk`.
9. Extract the downloaded artifact ZIP; install `app-debug.apk` on your Android phone.

## Notes

- This is a WebView wrapper, not a copy of the Lovable website source code.
- The website and its login/backend remain hosted by Lovable, so an internet connection is required.
- GitHub Actions creates a debug-signed APK for testing and personal installation. A Play Store/release build needs a separately managed signing key.
- Never upload passwords, API secrets, or signing keys to this repository.
