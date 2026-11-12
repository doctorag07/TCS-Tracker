TCS TRACKER — ANDROID STUDIO PROJECT

Features
- Includes tracking number 5567694096 as the initial saved shipment.
- Add, rename, delete, and one-tap track multiple shipments.
- Saves the parcel list locally in the Android WebView browser storage.
- Opens the official TCS tracking URL for live scans.

Build an APK
1. Install Android Studio (current stable version) on a computer.
2. Open the TCS-Tracker folder in Android Studio.
3. Allow Gradle sync and install the Android SDK Platform 35 if prompted.
4. Select Build > Build Bundle(s) / APK(s) > Build APK(s).
5. Android Studio will show the APK location, usually app/build/outputs/apk/debug/app-debug.apk.

Important
- This source project is provided; a compiled APK is not included because this environment does not have the Android SDK/Gradle build toolchain.
- TCS live tracking is performed on the official TCS website. The app does not scrape TCS or promise automatic background status updates.
- Saved shipments are stored on this device and are not cloud-synced.
