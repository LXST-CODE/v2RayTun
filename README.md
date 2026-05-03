[![Platform](https://img.shields.io/badge/Platform-%20Android%20%7C%20Android%20TV%20%7C%20iOS%20%7C%20macOS%20%7C%20Windows%20%7C%20Linux-informational.svg)](https://github.com/LXST-CODE/v2RayTun/wiki/home)
[![Android](https://img.shields.io/badge/Android-7%2B-informational.svg)](https://developer.android.com/about/versions/nougat)
[![iOS](https://img.shields.io/badge/iOS-16.0%2B-informational.svg)](https://go.dev/wiki/MinimumRequirements)
[![macOS](https://img.shields.io/badge/macOS-13.0%2B-informational.svg)](https://go.dev/wiki/MinimumRequirements)
[![Windows](https://img.shields.io/badge/Windows-10%2B-informational.svg)](https://docs.flutter.dev/reference/supported-platforms)
[![Arch](https://img.shields.io/badge/Arch-x64-informational.svg)](https://go.dev/wiki/MinimumRequirements)
[![Chat on Telegram](https://img.shields.io/badge/Chat%20on-Telegram-lightgray.svg)](https://t.me/v2raytun)

# v2RayTun - Proxy Client

v2RayTun is a cross-platform proxy client built on [Xray core](https://github.com/XTLS/Xray-core), providing platform-specific applications for Android, Android TV, iOS, macOS, Windows, and Linux.

> This repository is used for public roadmap, releases, bug reports, feature requests, and platform-specific notes.

## Releases

Builds and release notes are published through [Telegram Releases](https://t.me/v2raytun/3) and [GitHub Releases](https://github.com/LXST-CODE/v2RayTun/releases).

Available on [Google Play](https://play.google.com/store/apps/details?id=com.v2raytun.android) and [App Store](https://apps.apple.com/us/app/v2raytun/id6476628951).

> [!NOTE]
> The App Store version is currently not available in the RU region.

## Usage

> [!WARNING]
> The application does not provide ready-made configs, subscriptions, proxy servers, or VPN services!

The main function is carried out by importing configs or subscriptions into the application.

## Platforms

v2RayTun has separate platform-specific implementations and release tracks.

- [Android / Android TV](./android/)
- [iOS](./ios/)
- [macOS](./macos/)
- [Windows](./windows/)
- [Linux](./linux/)

## Independent release tracks

v2RayTun does not use a single global version for all platforms.

Each platform or platform group may have its own version number and release date.

| Release track | Platforms | Codebase | Notes |
|---|---|---|---|
| Android | Android, Android TV | Kotlin | Shared codebase with separate layouts, TV UI behavior, and platform-specific assets |
| Desktop | Windows, Linux | Flutter / Dart | Shared codebase with separate packaging, requirements, and platform-specific assets |
| iOS | iOS, iPadOS | Swift | Separate platform track with App Store release flow |
| macOS Apple Silicon | macOS M2+ | Swift | Separate macOS track for Apple Silicon builds |
| macOS Intel | macOS Intel | Swift | Separate macOS track for Intel builds |

## Roadmap

[Public Roadmap](https://github.com/users/LXST-CODE/projects/1) is managed through GitHub Projects.

Roadmap items may include platform-specific plans, feature requests, known limitations, release work, and declined ideas.

## Issues and feedback

Use GitHub Issues for:

- Bug reports
- Feature requests
- Platform-specific problems
- Roadmap suggestions

Please use the issue templates when opening a new issue.

## Languages

Пояснения на русском языке могут добавляться там, где это помогает пользователям, но основная структура репозитория ведётся на английском языке.