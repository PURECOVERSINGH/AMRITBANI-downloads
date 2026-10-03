# AMRITBANI downloads

[Choose your device](https://purecoversingh.github.io/AMRITBANI-downloads/) · [Web player](https://amritbani.vercel.app/) · [Latest Android release](https://github.com/PURECOVERSINGH/AMRITBANI-downloads/releases/tag/v2.2.5)

AMRITBANI Android 2.2.5 · iOS 2.2.2

- Centered transparent chrome artwork, crisp unblurred Monstera backdrop with a 10% black tint, and darker readable glass player.
- Smaller glass-style coffee button, with the existing on-page support popup.
- Manual red-glass buttons switch between the Player and Timer/Weather dashboard; screens never change automatically.
- Manual 25/5/15-minute Pomodoro, clock, date, and optional local weather.
- Six translucent frosted weather icons with clear day/night and condition mapping.
- iPhone/iPad native AVPlayer background audio and iOS 17+ AudioPlaybackIntent widgets for play/pause and next channel without foregrounding the app.
- Android Media3 native playback for reliable Shoutcast AAC streams, notification controls and Home Screen widget.
- Updated Android TV launcher banner and chrome emblem.
- Optional notification alerts when the official Sri Harmandir Sahib broadcast starts; permission is requested only after the user enables it.
- Player and Timer/Weather navigation buttons now sit at the bottom of their screens.
- iPhone/iPad and Android Phone WebViews use a fixed app scale with pinch and double-tap zoom disabled.
- Coffee and Timer/Weather controls share one bottom row, and red button glows were replaced with neutral clear glass.
- Android and iOS widgets use a more transparent player layout with elapsed-live progress plus previous, play/pause, and next controls.
- Android TV player is 30% smaller; low-latency Media3 buffering and automatic recovery improve Harmandir Sahib connection reliability.

Validation: 20 web tests passed; iPhone/iPad 2.2.2 unsigned Release build passed; Android phone/TV 2.2.5 signed Release builds, lint and signatures passed. Physical-device notifications, widgets, audio interruptions and background playback still need testing.

The IPA is unsigned and must be signed with your Apple ID using a compatible sideloading tool. Retain the widget extension when signing, then remove/re-add the widget after updating. Widgets require iOS 17+; the main app supports iOS 15+. Android requires Android 6+ and a current System WebView.

- TV uses a 10-foot two-column layout with 5% safe margins, large sans-serif type, a dominant Play/Pause control, pill status, and explicit D-pad focus.
- iOS no longer runs a synthetic widget timer after playback stops; Android widget status and elapsed time follow actual playback.
