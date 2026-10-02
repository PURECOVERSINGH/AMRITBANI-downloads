# AMRITBANI downloads

[Choose your device](https://purecoversingh.github.io/AMRITBANI-downloads/) · [Web player](https://amritbani.vercel.app/) · [Latest release](https://github.com/PURECOVERSINGH/AMRITBANI-downloads/releases/tag/v1.1.0-beta.4)

AMRITBANI 1.1.0 beta 4

- Centered transparent chrome artwork, Monstera backdrop and clear glass player.
- Smaller glass-style coffee button, with the existing on-page support popup.
- Clock, date and optional local weather after ten seconds of active listening. Location requires permission; rounded coordinates go directly to Open-Meteo.
- iPhone/iPad native AVPlayer background audio and iOS 17+ AudioPlaybackIntent widgets for play/pause and next channel without foregrounding the app.
- Android native media service, notification controls and Home Screen widget.
- Updated Android TV launcher banner and chrome emblem.

Validation: 18 web tests passed; iPhone/iPad Release build passed; Android phone/TV signed Release builds and lint passed. Physical-device widget, audio interruptions and background playback still need testing. Widget material/transparency depends on the OS and launcher; Android TV launchers generally do not support Home Screen widgets.

The IPA is unsigned and must be signed with your Apple ID using a compatible sideloading tool. Retain the widget extension when signing, then remove/re-add the widget after updating. Widgets require iOS 17+; the main app supports iOS 15+. Android requires Android 6+ and a current System WebView.
