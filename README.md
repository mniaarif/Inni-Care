# Inni Care Android app

A minimal Android WebView app that opens https://innicare.org.

## Build APK using GitHub Actions (Android phone/tablet)

1. Upload the contents of this project folder into the root of your GitHub repository (not the ZIP file itself).
2. Ensure the default branch is `main`.
3. Open the repository's **Actions** tab.
4. If prompted, enable GitHub Actions.
5. Choose **Build Inni Care APK** and tap **Run workflow** (or push a commit to `main` to trigger a build).
6. Open the completed workflow run, scroll to **Artifacts**, and download `Inni-Care-debug-APK`.
7. Extract the ZIP downloaded from Artifacts; it contains `app-debug.apk`.
8. Open the APK on your Android device to install it. You may need to allow installation from your browser/files app.

This is a **debug APK for testing**, not a Play Store release. It needs internet access to load the website. Website content changes appear automatically because the app loads the live site.

## Notes
- Package ID: `org.innicare.app`
- App label: `Inni Care`
- Uses HTTPS and INTERNET permission.
- External links are sent to the browser; innicare.org stays inside the app.
- Before publishing publicly, test navigation, forms, WhatsApp links, payment flows, and device compatibility.
