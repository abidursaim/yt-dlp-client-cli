# 📝 Changelog

All notable changes to the **YT-DLP Interactive Downloader** will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

---

## [1.1.0] — 2026-09-28

### Added
- **Playlist / Course download support** — auto-detects playlist URLs from YouTube, SoundCloud, Udemy, Skillshare, Coursera, and more
- **Playlist metadata preview** — displays title, uploader, video count, and a listing of videos before downloading
- **Download range selection** — download all videos, a custom range (e.g. 3–10), specific items (e.g. 1,3,5,8), or resume from a specific video
- **Organized output** — creates a named subfolder for each playlist with configurable file naming (numbered + title, title only, or number only)
- **Resume support** — uses `--download-archive` to skip already-downloaded videos on subsequent runs
- **Rate limiting** — adds sleep intervals between playlist downloads to avoid throttling
- **Smart mode selection** — when a URL could be both a video and a playlist, prompts the user to choose

### Changed
- URL prompt text updated to indicate playlist support (`video/playlist URL`)

---

## [1.0.0] — 2026-09-28

### Added
- Initial release
- Interactive 4-step download wizard (Quality → Audio → Filename → Destination)
- Video quality options: Best / 1080p / 720p / 480p / 360p / Audio-only
- Audio format options: MP3 (128–320 kbps), AAC, or lossless original
- Video metadata preview (title, channel, duration) before downloading
- Custom filename support with automatic sanitization
- Color-coded terminal UI with emoji decorations
- Loop mode for downloading multiple videos in a single session
- Dependency check for `yt-dlp` and `ffmpeg`
