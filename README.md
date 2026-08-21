# Pomorodo Cube Clock

A minimalist focus timer inspired by a physical Pomodoro cube clock.

## Behavior

* First launch asks for four timer presets
* Defaults are 5, 15, 30 and 60 minutes
* Saving presets starts preset 1 immediately
* Swipe from left to right to rotate to the next preset and start it immediately
* Timer screen contains only a thin circular progress ring, `00:00` countdown and a small `×` settings control
* Dark mode with a blue remaining time progress stroke
* Presets and active timer state are saved locally
* Android app bundles the interface locally and works without internet
* Android keeps the screen awake while the app is open

## Web

Production site: https://pomorodo-cube-clock.vercel.app

## Android APK

GitHub Actions builds an installable debug APK on every push to `main` that changes the Android or web source. Open the latest **Build Android APK** workflow run and download the `pomorodo-cube-clock-apk` artifact.
