# play_install_referrer
[![pub package](https://img.shields.io/pub/v/play_install_referrer.svg)](https://pub.dartlang.org/packages/play_install_referrer)

A Flutter plugin for the Android Play Install Referrer API.
The plugins throws an exception on iOS and on Android if Google Play Services are not available.

## Usage

Get Google Play Install Referrer Details:

```Dart
ReferrerDetails referrerDetails = await PlayInstallReferrer.installReferrer;
```

For more information see https://developer.android.com/google/play/installreferrer/library.html

## Credits

This plugin was originally created as [android_play_install_referrer](https://pub.dev/packages/android_play_install_referrer) by [Lukas Schmierer (@lschmierer)](https://github.com/lschmierer). [Chunky Tofu Studios](https://github.com/ChunkyTofuStudios/play_install_referrer) maintained the intermediate fork and renamed it to `play_install_referrer`.

TVBS maintains this company fork for compatibility with current Flutter and Android build tooling. The original BSD-2-Clause copyright notice, disclaimer, repository history, and contributor credits are retained.
