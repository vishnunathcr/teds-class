# Sum Sprint (Android)

A native Android wrapper around the Sum Sprint web game. The game itself lives in
`app/src/main/assets/index.html` and runs inside a WebView.

## Build the APK
1. Install Android Studio (Koala or newer).
2. File > Open, then choose this `SumSprint` folder and let Gradle sync.
3. Run on a device or emulator with the green Run button, or choose
   Build > Build Bundle(s) / APK(s) > Build APK(s).
   The APK is saved to `app/build/outputs/apk/debug/`.

To change the game, edit `index.html` in `app/src/main/assets/` and rebuild.

## No Android Studio? Build the APK on GitHub
1. Create a new GitHub repository and upload everything in this folder (keep the `.github` folder).
2. Open the repo's Actions tab and wait for "Build APK" to finish (about 3 minutes).
3. Open the finished run, download the `SumSprint-apk` artifact, unzip it and copy `app-debug.apk` to your phone.
4. Tap the file and allow "Install unknown apps" when Android asks.
