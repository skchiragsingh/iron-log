# IRON LOG Android

This private repository can build an Android APK automatically with GitHub Actions.

## Build
Push the project to the private GitHub repository. GitHub Actions will build a debug APK.
Open the repository's **Actions** tab, open the latest **Build IRON LOG APK** run, and download the artifact named `iron-log-debug-apk`.

## App data
Workout data is stored locally inside the Android WebView using localStorage. It works offline and survives normal app restarts/reboots. It does not automatically sync to another phone.

Use IRON LOG's Export Backup / Import Backup buttons for manual backup and restore.

## Editing later
Edit `www/index.html` (workout program/UI). Push the change to GitHub. The workflow automatically builds a new APK.
