# TubeyRoll Android TV beta

TubeyRoll is an experimental Android TV / Fire TV adaptation of [SmartTube](https://github.com/yuliskov/SmartTube). This repository hosts TubeyRoll's beta APK downloads and release notes. It is not affiliated with or endorsed by the SmartTube project or YouTube.

## Install

Install the [current `.28` beta APK](https://github.com/MadeByGoodTools/TubeyRoll/releases/download/v32.47-tubeyroll.28-beta/TubeyRoll-Firestick-v2465-debug.apk) from [Releases](https://github.com/MadeByGoodTools/TubeyRoll/releases). Enable installation from Downloader when Fire TV asks. The Android package is `ca.goodtools.tubeyroll.beta`, separate from SmartTube.

In the Downloader app, enter **5009649** for the `.28` APK. The matching short link is [aftv.news/5009649](https://aftv.news/5009649). Downloader codes point to one specific release; in-app update checks begin after `.28` is installed.

The `.28` beta introduces a TubeyRoll-only in-app update channel. The `.27` beta cannot discover `.28` on its own, so install `.28` manually once. Later beta releases can be found from the app's update check. Keep the same package and signing key when publishing future beta APKs; Android will reject an update signed with a different key.

Check the release page for the newest beta before installing manually.

This is a **debug-signed beta**, not a production release. Sign-in, playback on every TV, and all remote-control behavior have not been verified across devices. Only download from this repository or the Good Tools site, and check the release notes before updating.

## Attribution

TubeyRoll's native Android beta is based on SmartTube, copyright 2020-present yuliskov, under the MIT License. See [SmartTube's license](https://github.com/yuliskov/SmartTube/blob/master/LICENSE) and the upstream project for source and dependency notices. TubeyRoll-specific source changes are being prepared for publication; the APK is a beta test artifact in the meantime.
