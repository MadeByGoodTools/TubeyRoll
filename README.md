# TubeyRoll Android TV beta

TubeyRoll is an experimental Android TV / Fire TV adaptation of [SmartTube](https://github.com/yuliskov/SmartTube). This repository hosts TubeyRoll's beta APK downloads and release notes. It is not affiliated with or endorsed by the SmartTube project or YouTube.

## Install

Install the [current `.30` beta APK](https://github.com/MadeByGoodTools/TubeyRoll/releases/download/v32.47-tubeyroll.30-beta/TubeyRoll-Firestick-v2467-debug.apk) from [Releases](https://github.com/MadeByGoodTools/TubeyRoll/releases). Enable installation from Downloader when Fire TV asks. The Android package is `ca.goodtools.tubeyroll.beta`, separate from SmartTube.

In the Downloader app, enter **5009649** for the `.28` APK. The matching short link is [aftv.news/5009649](https://aftv.news/5009649). This code still installs `.28`, not `.30`; use the in-app update check after installing `.28`, or enter the direct `.30` release URL in Downloader.

The `.28` beta introduced a TubeyRoll-only in-app update channel. The `.27` beta cannot discover `.28` on its own, so install `.28` manually once. The `.29` beta added Up Next; `.30` adds Watch Modes, improved Continue Watching, saved/reorderable queues, quick channel controls, and playback recovery. Keep the same package and signing key when publishing future beta APKs; Android will reject an update signed with a different key.

Check the release page for the newest beta before installing manually.

This is a **debug-signed beta**, not a production release. Sign-in, playback on every TV, and all remote-control behavior have not been verified across devices. Only download from this repository or the Good Tools site, and check the release notes before updating.

## Attribution

TubeyRoll's native Android beta is based on SmartTube, copyright 2020-present yuliskov, under the MIT License. See [SmartTube's license](https://github.com/yuliskov/SmartTube/blob/master/LICENSE) and the upstream project for source and dependency notices. TubeyRoll-specific source changes are being prepared for publication; the APK is a beta test artifact in the meantime.
