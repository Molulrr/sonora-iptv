<p align="center">
  <img src="assets/logo.svg" width="64" alt="Sonora IPTV logo">
</p>

<h1 align="center">Sonora IPTV</h1>

<p align="center">
  A calm, fast media player for Windows.<br>
  Live TV, movies and series from the subscription you already have, in one place.
</p>

<p align="center">
  <a href="https://github.com/Molulrr/sonora-iptv/releases/latest"><img alt="Latest release" src="https://img.shields.io/github/v/release/Molulrr/sonora-iptv?style=flat-square&label=release&labelColor=161617&color=2b2a2c"></a>
  <img alt="Windows 10 and 11" src="https://img.shields.io/badge/Windows-10%20%7C%2011-2b2a2c?style=flat-square&labelColor=161617">
</p>

<p align="center">
  <a href="https://github.com/Molulrr/sonora-iptv/releases/latest"><b>Download</b></a>
  &nbsp;·&nbsp;
  <a href="https://molulrr.github.io/sonora-iptv/"><b>Website</b></a>
  &nbsp;·&nbsp;
  <a href="#getting-started"><b>Getting started</b></a>
</p>

<br>

<p align="center">
  <img src="docs/assets/sonora-hero.webp" alt="Sonora IPTV: the home screen in front, Live TV and the movie library behind it" width="100%">
</p>

<br>

## About

Sonora IPTV is a player for IPTV subscriptions in the Xtream Codes or M3U format. It brings channels, programme guide, films and series together in one quiet, dark interface that works with a mouse, a keyboard or a remote.

Sonora IPTV is a player only. It does not include any channels, streams, playlists or subscriptions.

## Features

- **Live TV** — categories, channel list, live preview and today's programme as a timeline
- **Movies and series** — posters, details, seasons, episodes and your progress
- **Live sport** — current scores, matched to the channels in your own subscription
- **Continue watching** — resume where you stopped; the next episode starts by itself
- **Playback with mpv** — hardware decoding, audio and subtitle tracks, automatic reconnect
- **Search** — channels, movies and series in one place (<kbd>Ctrl</kbd> + <kbd>F</kbd>)
- **Keyboard and remote** — arrow-key navigation, custom shortcuts, sizes up to TV scale
- **Private** — logins stay in the Windows Credential Manager; updates install in one click

Available in English, German, French, Spanish, Italian and Turkish.

## Screenshots

<table>
  <tr>
    <td width="50%"><img src="docs/assets/sonora-live-tv.webp" alt="Live TV with channel list, preview and programme"></td>
    <td width="50%"><img src="docs/assets/sonora-movies.webp" alt="Movie library with Top 10 and recently added"></td>
  </tr>
  <tr>
    <td align="center"><sub>Live TV</sub></td>
    <td align="center"><sub>Movies</sub></td>
  </tr>
  <tr>
    <td><img src="docs/assets/sonora-movie-details.webp" alt="Movie details page"></td>
    <td><img src="docs/assets/sonora-live-sport.webp" alt="Live sport with scores"></td>
  </tr>
  <tr>
    <td align="center"><sub>Details</sub></td>
    <td align="center"><sub>Live sport</sub></td>
  </tr>
  <tr>
    <td><img src="docs/assets/sonora-series.webp" alt="Series page with episodes"></td>
    <td><img src="docs/assets/sonora-settings.webp" alt="Settings"></td>
  </tr>
  <tr>
    <td align="center"><sub>Series</sub></td>
    <td align="center"><sub>Settings</sub></td>
  </tr>
</table>

<sub>The screenshots use invented demo data: channel names, titles and teams are fictional, pictures are free stock photos.</sub>

## Installation

1. Download **`Sonora.IPTV_<version>_x64-setup.exe`** from [Releases](https://github.com/Molulrr/sonora-iptv/releases/latest).
2. Run the installer. No administrator rights needed.
3. Open Sonora IPTV and add your provider.

Requires Windows 10 or 11 (64-bit) and about 150 MB of disk space.

> [!NOTE]
> If Windows shows **"Windows protected your PC"**, choose **More info** → **Run anyway**. The installer is not code-signed yet.

## Getting started

**Xtream Codes** — choose *Xtream Codes*, enter server URL, username and password, then *Test connection* and *Save*.

**M3U playlist** — choose *M3U / M3U8 playlist*, paste the link or pick a file, optionally add an XMLTV guide, then *Save*.

<details>
<summary><b>Player shortcuts</b></summary>
<br>

| Key | Action |
|---|---|
| <kbd>Space</kbd> | Play / pause |
| <kbd>F</kbd> | Fullscreen |
| <kbd>M</kbd> | Mute |
| <kbd>↑</kbd> <kbd>↓</kbd> | Volume |
| <kbd>←</kbd> <kbd>→</kbd> | Back / forward 10 seconds |
| <kbd>Page Up</kbd> <kbd>Page Down</kbd> | Previous / next channel |
| <kbd>I</kbd> | Stream info |

All shortcuts can be changed under **Settings → Keyboard shortcuts**.
</details>

<details>
<summary><b>Troubleshooting</b></summary>
<br>

- **Stream stutters** — Settings → Live TV: set the format to HLS or raise the network buffer.
- **Black picture** — Settings → Playback: set the video output to *Separate window*.
- **Picture errors** — turn off hardware decoding.
</details>

## Feedback

Found a bug or have an idea? [Open an issue](https://github.com/Molulrr/sonora-iptv/issues/new) with your Windows version and the Sonora IPTV version (Settings → About). Please never post your provider URL, login or playlist link.

## Legal

Sonora IPTV is free to download and use. It is distributed as a binary; the source code is not published. Playback uses [mpv](https://mpv.io) (GPL/LGPL). Built with [Tauri](https://tauri.app).

Sonora IPTV does not provide, sell or link to any channels, streams or subscriptions. Use it only with content and subscriptions you are legally allowed to use. All names and pictures in the screenshots are fictional or free stock photos.

<br>

<p align="center"><sub>© 2026 Sonora IPTV</sub></p>
