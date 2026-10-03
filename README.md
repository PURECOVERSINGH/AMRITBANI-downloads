# AMRITBANI downloads

[Choose your device](https://purecoversingh.github.io/AMRITBANI-downloads/) · [Web player](https://amritbani.vercel.app/) · [Latest Android release](https://github.com/PURECOVERSINGH/AMRITBANI-downloads/releases/tag/v2.3.0)

AMRITBANI Android and iOS 2.3.0

- The player uses a translucent colorless frosted-glass surface with the chrome emblem on the left, one station title, and Inter Black headings. The Monstera background keeps its 10% black tint.
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

Validation: 20 web tests passed and the iPhone/iPad 2.3.0 unsigned Release build passed. Android phone/TV 2.3.0 signed Release builds, lint and signatures passed. Physical-device layout, notifications, widgets, audio interruptions and background playback still need testing.

The IPA is unsigned and must be signed with your Apple ID using a compatible sideloading tool. Retain the widget extension when signing, then remove/re-add the widget after updating. Widgets require iOS 17+; the main app supports iOS 15+. Android requires Android 6+ and a current System WebView.

- TV uses a 10-foot two-column layout with safe margins, previous/next station controls, a dominant Play/Pause control, a compact connection-status dot, and explicit D-pad focus.
- iOS no longer runs a synthetic widget timer after playback stops; Android widget status and elapsed time follow actual playback.

- iOS 2.2.4 clears Now Playing metadata on stop and refreshes Home Screen widget snapshots. The Home Screen widget shows controls without a synthetic elapsed timer.

- iOS 2.2.4 gives the Home Screen widget dark text on pale glass in light appearance and light text on dark glass in dark appearance.
