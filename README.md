# My Little Library — Android starter app

This is an Android Studio project for a personal book tracker.

## Included
- Live camera ISBN-13 barcode scanning using CameraX + Google ML Kit.
- Automatic title/author lookup through the Google Books public volumes API.
- Manual editing when a book cannot be found.
- Local SQLite storage on the device.
- Reading statuses and a date picker for finished dates.
- Basic bookshelf list, status updates, and deletion.

## Build and install
1. Install Android Studio (current stable) and the Android SDK Platform 35.
2. Open this folder in Android Studio.
3. Let Gradle sync and install any prompted SDK components.
4. Connect an Android phone with USB debugging enabled, or start an emulator with camera support.
5. Press Run. Grant camera permission when prompted.
6. On the phone, tap **Scan ISBN** and point the rear camera at the ISBN-13 barcode on the back of a book.

## Notes
- Requires internet access for automatic Google Books lookup.
- The app stores your bookshelf in a local SQLite database on the device.
- This starter app does not upload your library to a cloud account or sync between devices.
- ISBN-10-only barcodes are not currently accepted by the live scanner; ISBN-13 (978/979) is supported.
- Google Books may not have every edition. If no match is found, the ISBN is carried into the manual-entry form.
- This is source code, not a prebuilt APK. Build it in Android Studio to create/install the APK.
