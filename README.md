# AyuTube

AyuTube is an independent Android fork of [LibreTube](https://github.com/libre-tube/LibreTube). It builds on LibreTube’s open-source YouTube frontend and gives the app a distinct, quieter visual identity.

> AyuTube is not affiliated with YouTube or the LibreTube maintainers. Core playback, content extraction, and service compatibility continue to depend on the upstream project and its dependencies.

## Project status

This repository is an active rebranding and UI-development fork. Not every upstream screen or behavior has been redesigned yet, and builds from this branch should be treated as development builds.

## Build from source

Requirements: JDK 17 and Android SDK 36.

```bash
 git clone https://github.com/ayush143-maker/AyuTube.git
 cd AyuTube
 ./gradlew assembleDebug
```

The debug APK is generated under `app/build/outputs/apk/debug/`.

## Upstream and license

AyuTube is derived from [LibreTube](https://github.com/libre-tube/LibreTube). The upstream project and its contributors retain their original copyright and attribution. This fork is distributed under the GNU General Public License v3.0; see [`LICENSE`](LICENSE) for the complete license text. Changes made in this fork are intended to remain compatible with the GPL-3.0 terms.
