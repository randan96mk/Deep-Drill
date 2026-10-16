# Deep Drill

A hold-to-drill mining game for Android. The game itself is a single HTML/canvas
file (`app/src/main/assets/index.html`) shown full-screen in a WebView.

## Run it

1. In Android Studio: **File > New > Project from Version Control**, paste this repo's URL.
2. Let Gradle sync (it downloads Gradle 8.7 and the Android Gradle Plugin automatically).
3. Plug in your phone with **USB debugging** on, pick it as the target, and press **Run**.

To get an installable file: **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
The debug APK appears in `app/build/outputs/apk/debug/`.

## Requirements

- Android Studio with JDK 17 or newer (the bundled one is fine)
- Phone running Android 8.0 (API 26) or newer

## How to play

- Hold anywhere to lower the drill and dig. Rock breaks fast, gems take longer.
- Tap the **$100** note (top right) to upgrade the drill. Each level drills faster, up to level 10.
- Tap **SURFACE** (bottom right) to ride back up to the grass. Hold to go back down.
- Progress (cash, depth, upgrade level) is saved on the phone.

## Edit the game

Change `app/src/main/assets/index.html` and run again. No other files need to change.
