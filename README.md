# SLVS FTTH Map – Android app

FTTH route mapper: GPS points, fiber distance from start to end, FBT coupler / PLC splitter
power (input & each output), fiber-cut joints, ONT Rx check, KML/CSV/JSON export.

The whole app is `app/src/main/assets/index.html`; this project wraps it in an Android WebView
with GPS permission, file import and export/share.

## Get the APK
**Option A – Android Studio:** File › Open › this folder › wait for Gradle sync ›
Build › Build APK(s). Copy `app/build/outputs/apk/debug/app-debug.apk` to the phone and install.

**Option B – GitHub (no PC setup):** push this folder to a GitHub repo. The included
workflow builds the APK automatically: Actions tab › latest run › download "SLVS-FTTH-Map-apk".

Internet is needed for map tiles; your network data is stored on the phone.
