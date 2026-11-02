# ReL Photo Dokumentasi

Android app starter project for creating offline photo documentation PDFs.

## Current V1 scope
- Project title, date and location
- Add multiple photos from Android gallery
- Capture a photo using the device camera
- Individual caption for every photo
- Reorder is not included in this first build; photos follow add order
- Save a draft locally on the device
- Export A4 PDF with up to two photos per page
- PDF saved under `Download/ReL TV Documentation`
- No logo; no internet required at runtime

## Build APK with GitHub Actions
1. Create a new GitHub repository named `ReL-TV-Photo-Documentation`.
2. Upload the contents of this folder to the repository root (not the containing folder itself).
3. Open **Actions** and enable workflows if GitHub asks.
4. Run **Build ReL TV Photo Documentation APK** or push to `main`.
5. Open the completed workflow run, find **Artifacts**, and download `ReL-Photo-Dokumentasi-APK`.
6. Extract the ZIP and install `ReL-Photo-Dokumentasi.apk` on Android.

Build uses Gradle 8.9+ compatible Android Gradle Plugin 8.7.3 and JDK 17.
