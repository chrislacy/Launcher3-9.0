# Launcher3-9.0

A fork of AOSP's [Launcher3](https://android.googlesource.com/platform/packages/apps/Launcher3.git) project as at [032d5f7](https://android.googlesource.com/platform/packages/apps/Launcher3.git/+/032d5f742b66f1acc618889d008bdd3948822da7) (Android 9.0).

This project is intended to make it as easy as possible for the Android team to reproduce Android Q Beta bug reports that occur when using a 3rd party launcher.

# Usage

    ./gradlew installAospDebug

# Changes

* Rename the app to `"L3-9.0"`.
* Expose the launcher Activity so it appears in app drawers.
* Sets the packageName to `com.android.launcher3.pie` - this avoids potential conflicts with other installs of Launcher3 on a device.
