# LuxClock — Android widget starter project

Premium digital clock widget with Russian date, current temperature and short weather description.

## Build
1. Open this folder in Android Studio (Hedgehog or newer).
2. Allow Gradle to download Android Gradle Plugin 8.7.3 and Kotlin plugin 2.0.21.
3. Connect an Android phone (Android 8.0 / API 26 or newer) and press Run.
4. Grant location permission and internet access for local weather.
5. Add the widget: long-press the home screen → Widgets → LuxClock.

Weather is retrieved from Open-Meteo (no API key required). The widget clock itself uses Android's live `TextClock`; weather refreshes when the app is opened and via the widget's 30-minute update interval (Android may defer periodic updates to save battery).

## Notes
This is a starter source project, not a signed APK. An Android SDK/Gradle build environment is required to compile and sign the installable APK. The included mountain artwork is the visual mockup background; the next iteration can add selectable wallpaper gallery and image picker.
