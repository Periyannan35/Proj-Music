# 🎧 Feel of Music (FM)

Professional real-time audio enhancement web application. Enhance your music instantly with custom bass, volume, and clarity controls.

## ✨ Features

- **Real-time Enhancement** - Adjust bass, volume, and clarity while playing
- **Original vs Enhanced Toggle** - Compare raw and processed audio instantly
- **Playlist Management** - Queue multiple songs with individual settings
- **Per-Song Memory** - Each track saves its own enhancement settings
- **Demo Mode** - Try with included sample tracks
- **Keyboard Shortcuts** - Space to play, arrows to seek, numbers for tabs
- **Mobile Responsive** - Works on all devices

## 🚀 Quick Start

1. Open `index.html` in any modern browser
2. Drop audio files or click "Select Files"
3. Or click "Play Demo" to try with samples
4. Adjust enhancement sliders in real-time
5. Download enhanced versions if desired

## 🎮 Controls

| Key | Action |
|-----|--------|
| `Space` | Play/Pause |
| `←` `→` | Seek -5s / +5s |
| `1-5` | Switch tabs |
| `Click` | Seek to position |

## 🛠️ Tech Stack

- Web Audio API - Real-time processing
- HTML5 Canvas - Visualizers
- Vanilla JavaScript - No dependencies
- CSS3 - Modern styling

## 📁 File Structure
feel-of-music/
├── index.html          # Main app
├── css/
│   └── styles.css      # All styles
├── js/
│   ├── audioEngine.js  # Web Audio processing
│   ├── playlistManager.js  # Queue management
│   ├── player.js       # Main controller
│   └── uiController.js # UI helpers
└── assets/
└── samples/        # Demo audio files


## 🔒 Security Notes

- All processing happens client-side
- No audio files uploaded to any server
- No user data collected
- LocalStorage used only for saving enhancement preferences

## 📝 License

© 2026 Periy AI. All rights reserved.
