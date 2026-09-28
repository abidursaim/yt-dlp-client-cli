# 🎬 YT-DLP Interactive Downloader

A sleek, interactive CLI tool to download videos and audio from YouTube (and other supported sites) using [yt-dlp](https://github.com/yt-dlp/yt-dlp).

![Python](https://img.shields.io/badge/Python-3.6%2B-blue?logo=python)
![License](https://img.shields.io/badge/License-MIT-green)
![Platform](https://img.shields.io/badge/Platform-Linux-orange?logo=linux)

## ✨ Features

- **4-step guided wizard** — Quality → Audio → Filename → Destination
- **Video quality options** — Best / 1080p / 720p / 480p / 360p / Audio-only
- **Audio formats** — MP3 (128–320 kbps), AAC, or lossless original
- **Metadata preview** — Shows title, channel, and duration before downloading
- **Custom filenames** with automatic sanitization
- **Color-coded terminal UI** with emoji decorations
- **Loop mode** — Download multiple videos in a single session

## 📋 Prerequisites

- **Python 3.6+**
- **[yt-dlp](https://github.com/yt-dlp/yt-dlp)** — `sudo apt install yt-dlp` or `pip install yt-dlp`
- **[ffmpeg](https://ffmpeg.org/)** — `sudo apt install ffmpeg`

## 🚀 Installation

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/yt-dlp-downloader.git
cd yt-dlp-downloader

# Make it executable
chmod +x yt-downloader

# (Optional) Create a shortcut symlink
ln -sf $(pwd)/yt-downloader ytdl
```

## 📖 Usage

```bash
# Run directly
./yt-downloader

# Or use the symlink
./ytdl
```

The tool will guide you through:

1. **Paste a video URL**
2. **Select video quality** (Best / 1080p / 720p / 480p / 360p / Audio-only)
3. **Select audio quality** (MP3 bitrate or AAC encoding)
4. **Choose filename** (default title or custom)
5. **Choose save location** (defaults to current directory)

## 📸 Preview

```
╔══════════════════════════════════════════════════════════════════╗
║               🎬  YT-DLP MEDIA DOWNLOADER  🚀                   ║
║                     Interactive Kali CLI                         ║
╚══════════════════════════════════════════════════════════════════╝

🔗 Enter video link / URL (or 'q' to exit): 
```

## 🤝 Contributing

Pull requests are welcome! Feel free to open issues for bugs or feature requests.

## 📄 License

This project is licensed under the MIT License.
