## 1.0.0
* Initial TVBS-maintained release as `play_install_referrer_client`.
* Requires Flutter 3.44 or later and Dart 3.12 or later.
* Migrates the Android plugin and example app to AGP 9 built-in Kotlin.
* Updates the example app to Android Gradle Plugin 9.2.0 and Gradle 9.4.1.
* Retains the BSD-2-Clause license and credits from the original projects.

## 0.5.0
* BREAKING: Plugin is renamed AndroidPlayInstallReferrer -> PlayInstallReferrer
* Updates Gradle and AGP
* Updates Android compileSDK to 36
* Fixes DeadObjectException (by @levBerlinkov)
* Plugin is now maintained by Chunky Tofu Studios

## 0.4.0
* Updates Gradle to 8.3
* Updates AGP to 8.1.0
* Updates java/kotlin compilation target to 1.8

## 0.3.0
* Update Gradle version to keep compatibility with Flutter
* Updated example to use v2 embedding

## 0.2.1
* Minor improvement to onDetachedFromEngine

## 0.2.0
* Fix for DeadObjectException
* Only query Install Referrer API once

## 0.1.1
* Fix null safety issue with nullable strings

## 0.1.0
* Enable null safety

## 0.0.4
* Expose new ReferrerDetails fields

## 0.0.3
* Update Gradle
* Update installreferrer dependency to 2.1

## 0.0.2
* Update installreferrer dependency to 1.1.2 to remove unnecessary WRITE_EXTERNAL_STORAGE and READ_EXTERNAL_STORAGE permissions.

## 0.0.1

* Google Play Install Referrer API for Android
