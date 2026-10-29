<p align="center"><img src="assets/banner.png" alt="Batflix for Android TV"></p>

<p align="center">
  <b>The IPTV player built for the remote.</b><br>
  Live TV, movies and series from your own subscription. Fast, readable from the couch.
</p>

<p align="center">
  <a href="https://github.com/loudovic12/Batflix-TV/releases/latest/download/Batflix.apk"><b>Download Batflix.apk</b></a>
  · Android TV and Google TV, Android 6+
  · <a href="README.fr.md">Version française</a>
</p>

<p align="center">
  <a href="https://github.com/loudovic12/Batflix-TV/releases/latest"><img alt="Latest version" src="https://img.shields.io/github/v/release/loudovic12/Batflix-TV?label=version&color=FFC93C&labelColor=12151C"></a>
  <img alt="Downloader code 9415870" src="https://img.shields.io/badge/Downloader-9415870-FFC93C">
  <img alt="Android TV 6+" src="https://img.shields.io/badge/Android%20TV-6%2B-3DDC84">
  <img alt="Built with the help of AI" src="https://img.shields.io/badge/built%20with-the%20help%20of%20AI-8A2BE2">
</p>

<p align="center">
  <a href="#whats-new-in-130">What's new</a> ·
  <a href="#what-it-does">Features</a> ·
  <a href="#screenshots">Screenshots</a> ·
  <a href="#install-on-your-tv">Install</a> ·
  <a href="#good-to-know">Good to know</a>
</p>

## What's new in 1.3.0

> [!TIP]
> **Two screens.** Watch two live channels at once, side by side or one large and one small. Sound follows the
> screen you pick, and the second channel can come from another account. In the live player: ▼ then *Two screens*.

- **Live TV that copes with outages.** When a channel stops, Batflix tries each fix once (another server, format or
  quality), then switches by itself to the same channel under another name from your provider.
- **Retry works again** in live TV, and a frozen stream no longer waits forever.
- **Instant sound** when going from the preview to full screen, and a **much faster Guide**.

Full history in the [Releases](https://github.com/loudovic12/Batflix-TV/releases).

## What it does

| | |
|---|---|
| **Live TV that holds.** When a server stalls, Batflix reconnects on its own, on the same channel or another server of your subscription. Zapping starts in under a second and a half. | **Made for the remote.** Categories left, channels center, live preview right. Voice search, country filter, hold OK for favorites. |
| **Movies and series.** Resume where you stopped, Watch later, favorites, watched marks, sort by newest or A to Z, next episode plays by itself. | **Add your account from your phone.** Scan the QR code on the TV and fill in the form on your phone. It goes straight to the TV over your Wi-Fi, never through the internet. |
| **TV guide and replay.** A Guide tab with programmes in a grid, hour by hour. Catch up on past programmes for the last few days when your provider offers it. | **Two screens.** Two live channels at once, side by side or picture in picture, from one or two accounts. |
| **Several accounts.** Xtream codes or M3U playlists, several servers per account. If one goes down, the others keep working. | **Updates built in.** Batflix tells you when a new version is out, shows what changed and installs it in one click. |

## Screenshots

| Live TV | Full screen |
|---|---|
| ![Live TV: categories, channels, live preview](assets/screens/live.png) | ![Player menu](assets/screens/player.png) |
| **Home** | **Add an account from your phone** |
| ![Home](assets/screens/home.png) | ![QR code to add an account](assets/screens/add.png) |

## Install on your TV

**Easiest: the Downloader app** (works on Android TV, Google TV and older Fire TV)

1. On the TV, install **Downloader** by AFTVnews (orange icon) from the Play Store, or the Amazon Appstore on Fire TV.
2. Open Downloader and enter the code **9415870** ([aftv.news/9415870](https://aftv.news/9415870)), or the address
   `https://github.com/loudovic12/Batflix-TV/releases/latest/download/Batflix.apk`.
   Both always point to the latest signed version.
3. When Android asks, allow Downloader to install apps, go back, then **Install** and **Open**.
4. Downloader can delete the APK afterwards to free space: Batflix stays installed.

<details>
<summary><b>Other ways</b></summary>

- **From your phone or computer**: download `Batflix.apk` from the [Releases](https://github.com/loudovic12/Batflix-TV/releases)
  and send it to the TV with a file transfer app such as *Send Files to TV*.
- **USB drive**: copy `Batflix.apk` to a USB drive and open it with a file manager on the TV (for example *X-plore*).
- **adb** (advanced): `adb install Batflix.apk`.

</details>

<details>
<summary><b>Device notes</b></summary>

- **Google TV (Chromecast with Google TV, recent TVs)**: installing apps is blocked until you enable it. Go to
  *Settings › System › About*, press *Android TV OS build* 7 times to enable developer mode, then
  *Settings › Apps › Security & restrictions › Unknown sources* and turn on **Downloader**.
- **Fire TV**: enable *Settings › My Fire TV › Developer options › Install unknown apps › Downloader*. Fire TV
  devices released since late 2025 run Vega OS instead of Android and cannot run Batflix. Fire TV is not tested yet.
- Batflix needs **Android 6 or newer**. The reference device is a Xiaomi Mi Box S (Android TV 14).

</details>

**Add your subscription**

On first launch, follow the welcome steps to **New account**. The quickest way: **scan the QR code with your phone**
(same Wi-Fi as the TV), enter the PIN shown on the TV, then fill in your details or paste your full subscription link.
Back on the TV, choose **Save and load**. Channels are ready in seconds, movies and series in about a minute.

**Updates**

Nothing to do: Batflix shows a window when a new version is out (or check in *Settings › About › Check for updates*)
and installs it in one click. The first time, Android may ask you to allow Batflix to install apps.

<details>
<summary><b>Troubleshooting</b></summary>

- *"App not installed"*: free some storage space and download again. If an old Batflix from another source is
  installed, uninstall it first (a different signature cannot be updated).
- *Downloader cannot open the code*: type the full address above instead.
- *No channels*: check your subscription details, then *Settings › Sync*.

</details>

## Good to know

- **Batflix provides no channels and no content.** It is a player: you need your own IPTV subscription.
- **Your logins stay on the TV**, encrypted. No Batflix account, no ads, no tracking.
- **Only download Batflix from this page.** Every version is signed, so a modified copy cannot replace yours.
- **Built with the help of AI.** Batflix is designed, tested on real Android TV boxes and maintained by its author,
  with Claude (Anthropic) as a coding assistant.

The screenshots use free, public channels.
