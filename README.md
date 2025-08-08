# Kazumi

A Flutter-based anime collection and online viewing application with custom rules. Build your own rules using up to five lines of `Xpath` syntax selectors. Supports rule import and sharing. Supports real-time super-resolution based on `Anime4K`. Currently under active development (～￣▽￣)～

## Supported Platforms

- Android 10 and above
- Windows 10 and above
- MacOS 10.15 and above
- Linux (Experimental)
- iOS (Requires self-signing)
- HarmonyOS NEXT (Located in the [branch repository](https://github.com/ErBWs/Kazumi/releases/latest), requires sideloading)

## Screenshots

<table>
  <tr>
    <td><img alt="" src="static/screenshot/img_1.png"></td>
    <td><img alt="" src="static/screenshot/img_2.png"></td>
    <td><img alt="" src="static/screenshot/img_3.png"></td>
  <tr>
  <tr>
    <td><img alt="" src="static/screenshot/img_4.png"></td>
    <td><img alt="" src="static/screenshot/img_5.png"></td>
    <td><img alt="" src="static/screenshot/img_6.png"></td>
  <tr>
</table>

## Features / Development Plan

- [x] Rule Editor
- [x] Anime Catalog
- [x] Anime Search
- [x] Anime Schedule
- [x] Anime Subtitles
- [x] Episode Playback
- [x] Video Player
- [x] Multiple Video Source Support
- [x] Rule Sharing
- [x] Hardware Acceleration
- [x] High Refresh Rate Adaptation
- [x] Watchlist
- [x] Anime Danmaku (Bullet Comments)
- [x] Online Updates
- [x] History
- [x] Playback Speed Control
- [x] Color Schemes
- [x] Cross-device Synchronization
- [x] Wireless Screencasting (DLNA)
- [x] External Player Playback
- [x] Super Resolution
- [x] Watch Together
- [ ] Anime Download
- [ ] Anime Update Notifications
- [ ] And much more (/・ω・＼)

## Download

Download from the [releases](https://github.com/Predidit/Kazumi/releases) tab on this page:

<a href="https://github.com/Predidit/Kazumi/releases">
  <img src="static/svg/get_it_on_github.svg" alt="Get it on Github" width="200"/>
</a>

### Android

<a href="https://f-droid.org/packages/com.predidit.kazumi">
  <img src="https://fdroid.gitlab.io/artwork/badge/get-it-on-en-us.svg"
  alt="Get it on F-Droid" width="200">
</a>

### GNU/Linux

&nbsp;&nbsp;
<a href="https://flathub.org/apps/io.github.Predidit.Kazumi">
  <img src="https://flathub.org/api/badge?svg&locale=en" alt="Get it on Flathub" width="175"/>
</a>

#### Arch Linux

Can be installed from [AUR](http://aur.archlinux.org) or [archlinuxcn](https://github.com/archlinuxcn/repo).

##### AUR

```bash
[yay/paru] -S kazumi # Build from source
[yay/paru] -S kazumi-bin # Binary package
```

##### archlinuxcn

```bash
sudo pacman -S kazumi
```

## Contribution

Welcome to submit your custom rules to our [rule repository](https://github.com/Predidit/KazumiRules). You are free to choose whether to leave your ID in the rules.

## Q&A

<details>
<summary>User Q&A</summary>

#### Q: Why are there ads in a few anime?

A: This project does not insert any ads. Ads come from the video source. Please do not trust any content in the ads, and try to choose video sources without ads.

#### Q: Why does playback stutter after I enable the super-resolution feature?

A: The super-resolution feature requires high GPU performance. If Kazumi is not running on a high-performance dedicated graphics card, try to choose efficiency mode instead of quality mode. Using super-resolution for low-resolution video sources instead of high-resolution video sources can also reduce performance consumption.

#### Q: Why is memory usage high when playing videos?

A: This application caches as much video as possible to memory during video playback to provide a better viewing experience. If your memory is tight, you can enable low memory mode in the playback settings tab, which will limit caching.

#### Q: Why can't a few anime be watched with an external player?

A: Some video sources use anti-leeching measures, which can be resolved by Kazumi but not by external players.

#### Q: Why does the downloaded Linux version lack icons and tray functionality?

A: Install using the .deb version. The tar.gz version is only for convenient repackaging, and this format inherently lacks icon and tray functionality support.

</details>

<details>
<summary>Rule Writer Q&A</summary>

#### Q: Why can't my custom rules achieve retrieval?

A: Currently, our support for `Xpath` syntax is not complete. We only support selectors starting with `//`. It is recommended to refer to the example rules we provide to build your custom rules.

#### Q: Why can my custom rules achieve retrieval, but not playback?

A: Try turning off the option to use the built-in player for custom rules. This will attempt to play using `webview` to improve compatibility. However, when the built-in player is available, it is recommended to enable it for a smoother viewing experience with danmaku.

</details>

<details>
<summary>Developer Q&A</summary>

#### Q: I'm trying to compile this project myself, but the compilation failed.

A: This project requires a good network environment for compilation. In addition to Flutter-related dependencies hosted by Google, this project also relies on resources hosted on MavenCentral/Github/SourceForge. If you are in mainland China, you may need to set up appropriate mirror addresses.

</details>

## Art Resources

The icon for this project is from the work published by [Yuquanaaa](https://www.pixiv.net/users/66219277) on [Pixiv](https://www.pixiv.net/artworks/116666979).

This icon is copyrighted by its original author [Yuquanaaa](https://www.pixiv.net/users/66219277). We have obtained authorization and permission from the original author to use this icon in this project. This icon is not free to use, and no one may use, copy, modify, or distribute this icon without the express authorization of the original author.

## Disclaimer

This project is licensed under the GNU General Public License v3.0 (GPL-3.0). We make no express or implied warranties regarding its applicability, reliability, or accuracy. To the maximum extent permitted by law, the authors and contributors shall not be liable for any direct, indirect, incidental, special, or consequential damages arising from the use of this software.

Use of this project must comply with local laws and regulations, and no acts infringing on third-party intellectual property rights are permitted. Data and caches generated from the use of this project should be cleared within 24 hours. Use beyond 24 hours requires authorization from the relevant rights holders.

## Privacy Policy

We do not collect any user data and do not use any telemetry components.

## Code Signing Policy
Contributors: [Contributors](https://github.com/Predidit/Kazumi/graphs/contributors)
Reviewers: [Owner](https://github.com/Predidit)

## Sponsors
| ![signpath](https://signpath.org/assets/favicon-50x50.png) | Free code signing on Windows provided by [SignPath.io](https://about.signpath.io/), certficate by [SignPath Foundation](https://signpath.org/) |
|------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------|

## Acknowledgements

Special thanks to [XpathSelector](https://github.com/simonkimi/xpath_selector), an excellent project that serves as the foundation of this project.

Special thanks to [DandanPlayer](https://www.dandanplay.com/). This project uses DandanPlayer's open API to provide danmaku interaction.

Special thanks to [Bangumi](https://bangumi.tv/). This project uses Bangumi's open API to provide anime metadata.

Special thanks to [Anime4K](https://github.com/bloc97/Anime4K). This project uses Anime4K for real-time super-resolution.

Special thanks to [SyncPlay](https://github.com/Syncplay/syncplay). This project uses the SyncPlay protocol and SyncPlay public servers to implement the Watch Together feature.

Thanks to [media-kit](https://github.com/media-kit/media-kit). This project's cross-platform media playback capabilities come from media-kit.

Thanks to [avbuild](https://github.com/wang-bin/avbuild). This project uses out-of-tree patches from avbuild to enable non-standard video stream playback.

Thanks to [hive](https://github.com/isar/hive). This project's persistent storage capabilities come from hive.