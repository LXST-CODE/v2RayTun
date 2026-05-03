# Releases

v2RayTun builds and release notes are published through GitHub Releases and platform-specific release channels.

This repository uses independent release tracks for different platforms and platform groups. Versions and release dates do not have to match across platforms.

GitHub Releases are used for downloadable build files, release notes, version history, and platform-specific release information.

## Release channels

v2RayTun may use the following release channels:

- Google Play
- App Store
- Telegram Releases
- GitHub Releases

Store releases may differ from Telegram/GitHub releases because of review process, regional availability, platform rules, and release timing.

## Independent release tracks

v2RayTun does not use a single global version for all platforms.

Each platform or platform group may have its own version number and release date.

## Availability

Current and planned release availability:

| Platform | Release channel |
|---|---|
| Android / Android TV | Google Play, Telegram Releases, GitHub Releases |
| iOS | App Store |
| macOS | App Store |
| Windows | Telegram Releases, GitHub Releases |
| Linux | Telegram Releases, GitHub Releases |

## Platform-specific release channels

Platform-specific releases are available here:

[Google Play](https://play.google.com/store/apps/details?id=com.v2raytun.android), [App Store](https://apps.apple.com/us/app/v2raytun/id6476628951)

## Telegram Releases

Telegram release posts are available here:

[Telegram Releases](https://t.me/v2raytun/3)

## GitHub Releases

GitHub Releases are available here:

[GitHub Releases](https://github.com/LXST-CODE/v2RayTun/releases)

## Versioning

v2RayTun uses independent versioning for each platform or platform group.

There is no single global version that must apply to all platforms at the same time.

Recommended tag format:

```text
PLATFORM-vMAJOR.MINOR.PATCH
```

Examples:

```text
android-v1.8.0
windows-v1.2.0
linux-v0.2.0
```

Version meaning:

| Part | Meaning |
|---|---|
| `PLATFORM` | Target platform or platform-specific release track |
| `MAJOR` | Large changes, compatibility changes, or major product updates |
| `MINOR` | New features, platform updates, or significant improvements |
| `PATCH` | Bug fixes, small improvements, or maintenance updates |

Versions and release dates may differ between platforms.

## Release asset naming

Release files should use clear platform-specific names.

Recommended format:

```text
v2RayTun-PLATFORM-ARCH-VERSION.EXT
```

Examples:

```text
v2RayTun-android-universal-v1.8.0.apk
v2RayTun-android-armeabi-v7a-v1.8.0.apk
v2RayTun-android-arm64-v8a-v1.8.0.apk
v2RayTun-windows-x64-v1.2.0.exe
v2RayTun-windows-x64-v1.2.0.msi
v2RayTun-windows-x64-v1.2.0.zip
v2RayTun-linux-x64-v0.2.0.deb
```

For store-only platforms, the GitHub release may contain release notes instead of downloadable application files.

## Platform notes

Each release may include platform-specific notes.

Recommended release note structure:

```md
## android-v1.8.0

### Added

- ...

### Updated

- ...

### Fixed

- ...

### Known issues

- ...

## windows-v1.2.0

### Added

- ...

### Updated

- ...

### Fixed

- ...

## linux-v0.2.0

### Platform notes

- First experimental Linux release.
```

## Release status

A release may use one of the following statuses:

| Status | Meaning |
|---|---|
| Stable | Recommended for general use |
| Beta | Public testing build |
| Preview | Early build with incomplete features |
| Experimental | Platform or feature testing build |
| Deprecated | Older release that should no longer be used |

## Binary files

Binary release files are not stored directly in this repository.

Build artifacts such as `.exe`, `.msi`, `.zip`, `.apk`, `.dmg`, `.AppImage`, `.deb`, `.rpm`, and `.tar.gz` should be published through GitHub Releases or platform-specific stores.

## Source code

This repository does not contain the application source code.

It is used for public roadmap, releases, bug reports, feature requests, and platform-specific notes.

## Reporting release problems

If a release does not work correctly, open a GitHub Issue and include:

- Platform
- App version
- Operating system version (including device model or vendor UI version if applicable)
- Where the app was installed from
- Steps to reproduce the problem
- Logs or screenshots, if available
