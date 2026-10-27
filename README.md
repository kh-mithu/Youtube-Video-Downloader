# Me2bhai Downloader

A simple and efficient **video & audio downloader** for Windows, developed by **M Tech Solution**. Download full videos or extract just the audio from your favorite online content with a clean, easy-to-use interface.



## ✨ Features

- 🎬 **Download Videos** — Save full video files in your preferred quality.
- 🎵 **Download Audio** — Extract audio only from any supported video source.
- 🖥️ **Simple GUI** — No command line needed; just paste a link and click download.
- ⚡ **Fast & Lightweight** — Powered by FFmpeg for reliable media processing.
- 📁 **Custom Output Location** — Choose where your files are saved.

---

## ⚠️ Prerequisites (IMPORTANT)

**Me2bhai Downloader requires FFmpeg to function.** Before running the app, you must have `ffmpeg.exe` and `ffprobe.exe` available on your system.

### Option 1 — Use the Included FFmpeg Build (Recommended)

This project was built and tested with the **January 2020 FFmpeg build**. To ensure compatibility:

1. Download the **FFmpeg build from January 2020** (or any compatible build).
2. Extract the archive.
3. Locate **`ffmpeg.exe`** and **`ffprobe.exe`** inside the `bin` folder.
4. Place **both files in the same folder as `Me2bhai Downloader by M Tech Solution.exe`**, OR add that folder to your system `PATH`.

### Option 2 — System-Wide Installation

1. Download FFmpeg from the [official site](https://ffmpeg.org/download.html) or check release. 
2. Add the `bin` directory to your **Windows PATH** environment variable.
3. Verify installation by running:
   ```cmd
   ffmpeg -version
   ffprobe -version
