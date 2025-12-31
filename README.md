# 🎄 ChristmasPlayer — Local Music Player with Lyrics Sync

**ChristmasPlayer** is a fully local music player that lets you play your own MP3 songs with synchronized lyrics — no internet, no APIs, no subscriptions.

Download once. Play forever.

---

## ✨ Features

- 🎵 Local music playback (MP3 → WAV)
- 📝 Time-synced lyrics display
- 📂 Simple folder-based setup
- ⚡ Offline — no internet required
- 🔧 FFmpeg-based audio conversion
- 🎄 Designed for seasonal & personal playlists

---

## 📁 Project Structure

ChristmasPlayer/
├── christmas.exe # Main application

├── convert.bat # Auto MP3 → WAV converter

├── songs/ # Place MP3 files here

│ ├── example_test.mp3

│ └── your_song.mp3

├── lyrics/ # Lyrics with timestamps

│ └── your_song_lyrics.txt

└── converted/ # Auto-generated WAV files

---

## ⚙️ Requirements

- **Windows**
- **FFmpeg** (required for audio conversion)

👉 Download FFmpeg from the official website:  
https://ffmpeg.org/download.html  

> **Note:** FFmpeg is **not included** in this repository due to licensing.  
Make sure `ffmpeg.exe` is accessible from your system PATH or placed next to `convert.bat`.

---

## 🚀 How to Use

1. Download or copy your MP3 files
2. Place them inside the `songs/` folder
3. Create matching lyrics files inside `lyrics/`
4. open main.cpp in the CMD and run this command: g++ main.cpp -o christmas.exe
5. Run `christmas.exe`
6. Enjoy synced music & lyrics 🎶

---

## 📝 Lyrics File Format

Each lyrics file must have the **same name** as its song and follow this format:

MILLISECONDS|LYRIC_TEXT

### Example:
0|Last Christmas
2500|I gave you my heart
5200|But the very next day

- Time is in **milliseconds**
- Lyrics are displayed automatically at the correct moment

---

## 🧪 Included Test Files

This repository includes **example test files** to verify that your setup is correct.

- The test audio is **not copyrighted music**
- Lyrics are dummy/example content
- You may safely delete them after confirming everything works

---

## 🔒 Legal Notice

- Do **NOT** upload copyrighted music to public repositories
- This project does **not** distribute songs or lyrics
- Users are responsible for their own local content
- FFmpeg is subject to its own license (LGPL/GPL)

---

## 💡 Why Local?

- No ads
- No tracking
- No subscription
- Works forever, even offline

Your music. Your control.

---

## 🛠️ Future Improvements (Ideas)

- GUI enhancements
- Manual lyrics sync editor
- Playlist support
- Visual audio effects
- Drag & drop support

---

## 📜 License

This project is released under the **MIT License**  
You are free to use, modify, and distribute it.

---

## Disclaimer

The author is **not responsible for any copyright violations, legal issues, or damages** that may result from the misuse of this software. Users are responsible for ensuring that they comply with all applicable laws when using this software.

---

🎅 Built for learning, fun, and full control over your music 🎄
