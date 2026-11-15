# yt2mp3

Download YouTube videos and playlists as MP3 from your browser (Chrome, Chromium, Edge) on Windows, Linux and macOS.

This repository only hosts the downloads. Copyright © Nomerika.

## Installation

1. Download `yt2mp3-extension.zip` from the [latest release](https://github.com/Twistmac/yt2mp3-releases/releases/latest) and unzip it.
2. Open `chrome://extensions` (or `edge://extensions`), enable **Developer mode**, click **Load unpacked** and select the unzipped folder.
3. Click the yt2mp3 button in the toolbar, then **Install the companion app**. The extension downloads the companion app for your system and shows how to run it once (double-click on Windows, one command on Linux and macOS).
4. On a YouTube video or playlist, click the yt2mp3 button, then **Download MP3** or **Download playlist**.

Downloads are added to a list and run one after the other, so you can keep browsing and add other videos. MP3 files are saved in your `Music` folder.

The companion app runs `yt-dlp` and `ffmpeg`, which it downloads and keeps up to date by itself. It installs into:

- Windows: `%LOCALAPPDATA%\yt2mp3`
- Linux: `~/.local/share/yt2mp3`
- macOS: `~/Library/Application Support/yt2mp3`

To remove it, run the downloaded `yt2mp3-host-…` file with `--uninstall`.

The executables are not signed: Windows SmartScreen may ask you to confirm (**More info** → **Run anyway**).
