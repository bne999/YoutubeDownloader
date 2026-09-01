# YouTube Downloader

A simple Windows GUI application for downloading YouTube videos and audio using yt-dlp and FFmpeg.

## Features

- Download YouTube videos
- Video resolutions up to 4K
- Audio-only downloads
- MP3, WAV, FLAC and OGG support
- Custom download location
- FFmpeg support
- Automatic update system via GitHub Releases

## Requirements

The released Windows application does not require Python or yt-dlp to be installed separately.

## Download

Download the latest version from the [Releases](../../releases) page.

## First-Time Setup

## 1. Download the latest release from GitHub. You need these files together in the same folder:
  * YouTubeDownloader.exe
  * YouTubeDownloaderUpdater Folder

## 2. Folder layout should look like the following:

YouTubeDownloader\
├── YouTubeDownloader.exe

└── YouTubeDownloaderUpdater\

└── (YouTubeDownloaderUpdater.exe, etc.)
Don't rename or move any of these — the app looks for them right next to itself.

## 3. Run it

Double-click YouTubeDownloader.exe. Paste in a YouTube URL, don't do a playlist it'll break currently, pick your settings, and hit download.

## 4. Updates

Click Check for Updates any time to get the latest version. Updates install automatically, the app will close and reopen on its own.

## Reporting Problems

Found a bug or having trouble with the app? Please open an issue on the
[Issues page](https://github.com/bne999/YoutubeDownloader/issues) and include:

- What you were trying to do
- What happened instead
- Your app version
- Any error message text or a screenshot

This helps track down problems faster than a DM or comment elsewhere.
## Disclaimer

This software is intended for downloading content that you have permission to download. Users are responsible for complying with YouTube's Terms of Service and applicable copyright laws.
