
[![](https://jitpack.io/v/com.vuzix/connectivity-sdk.svg)](https://jitpack.io/#com.vuzix/connectivity-sdk)

![Vuzix Logo](https://apps.vuzix.com/images/vuzix-logo-old.png)
# Connectivity SDK
Use this library for connecting applications running on an Android smart phone and applications running on our line of Android
enabled Vuzix smart glasses, including VUZIX M400™, VUZIX M4000™, VUZIX SHIELD™, VUZIX BLADE®, and
VUZIX BLADE 2™.

As a developer, you can communicate between apps running on the your Vuzix device and apps running on a phone. This can be
accomplished in a variety of ways. You can choose to manage your own communication protocols using wireless technologies such
as Wi-Fi, Wi-Fi Direct, Bluetooth and Bluetooth Low Energy. You can also leverage this Connectivy SDK framework to communicate
between apps using the same secure communication protocol used by the Vuzix Companion App.

## Requirements
- Compatible Android smart phone
- Compatible Vuzix smart glasses
- Vuzix Companion App

## Installation
1. Add JitPack as a maven repository in settings.gradle or settings.gradle.kts at the top level of your Android Studio project:
```
dependencyResolutionManagement {
    repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
    repositories {
        ...
        maven { url "https://jitpack.io" } // if using settings.gradle
        maven ("https://jitpack.io")       // if using settings.gradle.kts
    }
}
```
2. Add connectivity-sdk to your module's build.gradle or build.gradle.kts file. Replace VERSION below with the version of the SDK you wish to use.
```
dependencies {
    ...
    implementation 'com.vuzix:connectivity-sdk:VERSION'   // if using build.gradle
    implementation ("com.vuzix:connectivity-sdk:VERSION") // if using build.gradle.kts
    ...
}
```
The latest connectivity-sdk version on JitPack is [![](https://jitpack.io/v/com.vuzix/connectivity-sdk.svg)](https://jitpack.io/#com.vuzix/connectivity-sdk).

## Documentation
API level documentation is available in [javadoc](https://vuzix.github.io/connectivity-sdk/javadoc).

The Developer Center on [vuzix.com](https://www.vuzix.com) includes articles and samples describing how to create applications using this library.

## Legal
Use of the SDK is available to developers agreeing to the
[VUZIX® SOFTWARE DEVELOPMENT KIT LICENSE AND CONFIDENTIALITY AGREEMENT](https://www.vuzix.com/pages/vuzix%C2%AE-software-development-kit-license-and-confidentiality-agreement)
