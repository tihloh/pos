# Installation and Updates

## Install the APK

1. Open the latest release in this repository.
2. Download the file named `POS-vX.Y.Z.apk`.
3. Open the APK on the Android device.
4. If Android asks for permission to install unknown apps, allow it for the browser or file manager you are using.
5. Confirm the installation.

## Updating

The app checks the public `tihloh/pos` releases for newer versions.

When an update is available, the app can prepare the APK internally and launch Android's installer. Normal sideloaded Android apps may still require the system install confirmation.

The APK is handled internally and is not intentionally left in the Downloads folder.

## Existing data

Normal app updates preserve the local Room database and settings. Do not uninstall the app if you want to keep local data unless you have an appropriate backup or central-sync strategy.
