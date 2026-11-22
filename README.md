<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="docs/brand/mark-dark.svg">
  <img src="docs/brand/mark-light.svg" alt="Shasha logo" width="112" height="112">
</picture>

# Shasha | شاشة

**One screen for everything you watch, on every screen at home.**

[![License: GPL-3.0](https://img.shields.io/badge/license-GPL--3.0-blue.svg)](LICENSE)
![Platforms](https://img.shields.io/badge/platforms-Android%20%7C%20Android%20TV%20%7C%20Windows-lightgrey.svg)

</div>

## About

Shasha (Arabic: شاشة, "screen") is a media player for Android phones and tablets, Android TV (including Mi Box) and Windows. It is based on the open-source [CloudStream](https://github.com/recloudstream/cloudstream) and is released under the same licence, GPL-3.0.

Shasha plays media from extensions (plugins) that you install yourself. It hosts no content and ships no extensions. See [Extensions](#extensions).

## Features

### Watch anywhere at home
- **One app on every screen.** Phone, tablet, Android TV with the remote, and Windows, each with a layout made for it.
- **Continue on another device.** Hand what you are watching to another device at the same moment, or pull it back with Continue here.
- **Your phone as a remote.** Play, pause, seek, volume, brightness, audio track, subtitles and source of the TV, also from the notification shade.
- **Play on another device** straight from a title page.
- **Device sync on your own server.** Devices join one space on your own Firebase Realtime Database. Sign in once and your accounts follow on every device, encrypted with your passphrase.
- **Chromecast.**

### The player
- **Seeking that feels right.** Double tap a side and keep tapping to add up the jump, swipe across the picture to scrub with a frame of where you will land, peek and filmstrip while scrubbing, pinch to fill or zoom.
- **Skip intro, credits and to the next episode,** with a countdown.
- **Speed up to 5x,** and press and hold for double speed.
- **Ambient mode,** where the space around the video takes its colours, and **Enhance video** for a sharper picture from low-quality sources.
- **Subtitles done properly.** Right to left, alignment, a font made for English and Arabic, captions that sit above the controls, and subtitle search that only adds subtitles for the title you are watching.
- **Auto captions,** made on the fly when a video has none, and translated to your language.
- **The original audio language first,** with dubbed tracks labelled.
- **Picture-in-Picture and an in-app mini player** with the full controls.
- **Play next and Add to queue,** with Loop (current or playlist) and Autoplay.

### Audio
- **One audio player for everything you listen to.** Play any video as audio, with lyrics or live subtitles on the back of the artwork, Up next that you pull up, a sleep timer and a data saver.
- **YouTube Music and SoundCloud** in the same player, with the Song and Video switch and lyrics where available.
- **Music and podcasts start as audio** and are labelled as tracks and episodes.

### YouTube
- **Your own YouTube.** Sign in on Google's own page and get your Home, subscriptions and library.
- **Watch later, Like, Subscribe and comments** from the title page, the players and the menus.
- **History with its own look,** day by day.
- **A Shorts player** that opens Shorts full screen, swipe to the next.
- **Search filters** for Videos, Shorts, Channels and Playlists, and the same chips for every source that has them.
- **Open any pasted or shared link,** including YouTube, YouTube Music, Dailymotion and SoundCloud.

### Live TV
- **IPTV inside the app** with your own Xtream Codes or M3U account: channels, categories, favourites, your lists, the guide, and quick zapping with the remote and number keys.

### Find and organise
- **Search once** across sources and names in several languages; sources with no results stay out of the way.
- **Find and install extensions** from the community list, with suggestions during setup.
- **Downloads** for a whole season or just the episodes you choose.
- **Trackers:** Simkl, MyAnimeList and AniList.
- **A tunnel for sources that are blocked where you are,** set per device.

### Yours
- **Profiles** with PIN lock, quick switching, a default profile per device, and its own language, accent and extensions.
- **Themes:** Default, Material You and Glass, a real Liquid Glass look, all coloured by your accent, in light, dark or following the system.
- **A launcher icon that follows your theme and accent,** with Match the app, Material You, Line and Glass styles.
- **English and Arabic,** with full right-to-left layouts and Inter with Noto Sans Arabic everywhere.

## Platforms

| Platform | Support |
| --- | --- |
| Android phone and tablet | Android 6.0 and later |
| Android TV, including Mi Box | Android 6.0 and later, with remote control support |
| Windows | Windows 10 and Windows 11 |

## Download and install

Get the latest version from the [Releases page](https://github.com/farahalibrahim/shasha/releases).

**Android phone or tablet**

1. Download the APK from a release.
2. Open it. When Android asks, allow your browser or file manager to install unknown apps.
3. Install and open Shasha.

**Android TV (including Mi Box)**

1. On the TV, install a file manager or a downloader app that works with a remote.
2. In the TV settings, allow that app to install unknown apps (usually under Security and restrictions).
3. Download the APK from the release page in that app, copy it to the TV from a USB drive, or install it with `adb install`.
4. Open the APK and install it. Shasha appears in the TV launcher.

**Windows**

Download the Windows build from the same release and run it.

## Extensions

Shasha does not host, store, upload or distribute any media. It does not ship with any extensions, and it does not endorse or control any extension.

Extensions are separate software written by third parties. You choose which ones to install, and you are responsible for the extensions you add and for what you watch with them, including following the laws that apply to you. The developers of Shasha are not responsible for the content that extensions provide.

## Privacy

- Shasha has no analytics.
- Sign-ins (for example your YouTube account) stay on your devices. Device sync goes to your own Firebase database, encrypted with your passphrase.
- Extensions, and the sites they contact, are third parties with their own behaviour. Shasha cannot vouch for them.

## Credits

Shasha stands on the work of many open-source projects. See [NOTICE.md](NOTICE.md) for details.

- [CloudStream](https://github.com/recloudstream/cloudstream) and its contributors (GPL-3.0). Shasha is a modified version of CloudStream.
- [Inter](https://rsms.me/inter/) and [Noto Sans Arabic](https://fonts.google.com/noto/specimen/Noto+Sans+Arabic) fonts (SIL Open Font License 1.1).
- [Tabler Icons](https://tabler.io/icons) (MIT).
- [ExoPlayer / Media3](https://github.com/androidx/media) (Apache-2.0).
- [NewPipe Extractor](https://github.com/TeamNewPipe/NewPipeExtractor) (GPL-3.0).

## License

Shasha is free software, licensed under the [GNU General Public License v3.0](LICENSE). See [NOTICE.md](NOTICE.md) for attribution and third-party licences.
