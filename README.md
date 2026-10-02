# AMRITBANI

Live Gurbani, Kirtan and Akhand Paath. Official testing downloads for Android TV, Android phones, iPhone and iPad.

[Open the live player](https://amritbani.vercel.app/) · [All releases](https://github.com/PURECOVERSINGH/AMRITBANI-downloads/releases)

## Download 1.0.0 beta 1

| Device | Download | Installation status |
|---|---|---|
| Android TV / Google TV | [AMRITBANI-Android-TV.apk](https://github.com/PURECOVERSINGH/AMRITBANI-downloads/releases/download/v1.0.0-beta.1/AMRITBANI-Android-TV.apk) | Release-signed APK. Android 6+ with Android TV and WebView. |
| Android phone / tablet | [AMRITBANI-Android-Phone.apk](https://github.com/PURECOVERSINGH/AMRITBANI-downloads/releases/download/v1.0.0-beta.1/AMRITBANI-Android-Phone.apk) | Release-signed APK. Android 6+ and current Android System WebView. |
| iPhone / iPad | [AMRITBANI-iPhone-iPad-signing-required.ipa](https://github.com/PURECOVERSINGH/AMRITBANI-downloads/releases/download/v1.0.0-beta.1/AMRITBANI-iPhone-iPad-signing-required.ipa) | Unsigned arm64 test build for iOS/iPadOS 15+. Must be signed with your own Apple ID/development profile through a compatible sideloading tool. **Not a tap-to-install or App Store download.** |

[SHA-256 checksums](https://github.com/PURECOVERSINGH/AMRITBANI-downloads/releases/download/v1.0.0-beta.1/SHA256SUMS.txt)

These are early testing builds. Compilation and automated checks do not constitute physical-device validation. Internet access is required. Playback pauses when the app goes into the background; this release does not provide a native background-audio service.

## Android installation

1. Download the matching APK from this repository's Releases page.
2. Open it on your phone, or transfer it to the TV by USB/a trusted file transfer method.
3. If prompted, allow installation from that specific browser/file manager, install AMRITBANI, then turn that permission off again.
4. Launch **AMRITBANI** from the device's Apps screen.

On TV, use the directional pad to move focus and OK to activate controls. On the station selector use Left/Right to change stations. The remote's media Play/Pause button is supported. The TV's own volume keys remain available.

The original TV debug APK used a different signing key. **Uninstall that original test build before installing the release-signed TV APK.** Future release APKs will use the persistent release key.

## iPhone and iPad testing

The IPA is intentionally labeled **signing-required**. Downloading it in Safari alone cannot install it. Use a compatible sideloading tool on your own computer to sign and provision it with your Apple ID, or build/sign the Xcode project using a Personal Team. Free provisioning is temporary and may require periodic renewal and Developer Mode. Never send your Apple ID password to this project or enter it on this download page.

For immediate use without signing: open [AMRITBANI](https://amritbani.vercel.app/) in Safari, then Share → Add to Home Screen. This is the web app, not the native IPA.

No TestFlight, App Store or Google Play listing is available in this release. The iOS build is a minimal testing shell and has not been validated on physical iPhones/iPads.

## Earlier build

[Original Android TV debug APK](https://github.com/PURECOVERSINGH/AMRITBANI-downloads/releases/tag/v0.1.0-tv-preview) — archived for existing testers; use the current release above for new installations.

## Privacy and security

The apps load the AMRITBANI HTTPS website and public broadcaster streams. Third-party broadcasters and hosting providers receive ordinary connection data. Support payments are handled by Buy Me a Coffee. The native shells do not request camera, microphone, contacts or location permissions. This public repository contains downloads and documentation; signing private keys are never release assets.
