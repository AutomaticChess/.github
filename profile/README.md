# AutoChess ♟️

**Infinite client-side AI chess battles.**

[![Live Demo](https://img.shields.io/badge/Live_Demo-Visit-brightgreen)](https://automaticchess.github.io) 
[![Report Bug](https://img.shields.io/badge/Report-Bug-red)](https://github.com/automaticchess/automaticchess.github.io/issues)

## ⚡ Features

- **AI**: 3 distinct personalities (Aggressive, Positional, Balanced)
- **Engine**: Visual advantage bar, material counting, ECO opening detection
- **Audio**: Procedural sound generation (Web Audio API)
- **UI**: Glassmorphism design, fully responsive, no frameworks

## 🛠 Tech Stack

| Component   | Technology                     |
|-------------|--------------------------------|
| Core        | HTML5, CSS3, Vanilla JS (ES6+) |
| Logic       | chess.js (Move validation)     |
| Audio       | Native Web Audio API           |
| Build       | None (Zero dependency)         |

## 🚀 Usage

No build steps required.

1. **Clone the repo**
   ```bash
   git clone https://github.com/automaticchess/automaticchess.github.io.git
   cd automaticchess.github.io
   ```

2. **Run**
   - Simply open `index.html` directly in Chrome or Safari  
   - (Optional) For stricter module security:  
     ```bash
     python3 -m http.server
     ```

## 🎮 Controls

- **Speed**: Toggle Slow / Normal / Fast
- **Sound**: Toggle Audio API on/off
- **New Game**: Reset board state

## 📄 License

MIT © [AutoChess Team](https://github.com/automaticchess)
