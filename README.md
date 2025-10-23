# Minesweeper Pro (HTML, CSS, JavaScript)

A feature-rich, browser-based implementation of the classic puzzle game **Minesweeper**, built entirely with **HTML, CSS, and vanilla JavaScript**. No frameworks or external dependencies required — just open in your browser and play.

## 🎮 Features

### Core Gameplay
* **Classic Minesweeper mechanics** with modern enhancements
* **4 difficulty levels**: Easy (8×8), Medium (12×12), Hard (16×16), Expert (20×20)
* **Smart first-click guarantee** - never hit a mine on your first move
* **Auto-reveal** for empty cells and surrounding areas
* **Flag system** to mark suspected mines
* **Real-time statistics**: mine counter, timer, and flag counter

### Advanced Features
* **🔄 Undo system** - Revert up to 5 moves with visual counter
* **🤖 AI Mode** - Watch an advanced AI solve puzzles using:
  - Deterministic safe move detection
  - Constraint satisfaction algorithms
  - Probability-based decision making
  - Pattern recognition for complex scenarios
  - Auto-progression through difficulty levels
* **🏆 Leaderboard** - Track your best times for each difficulty level
* **💾 Auto-save** - Game state persists across browser sessions
* **📱 Fully responsive** - Optimized for desktop, tablet, and mobile devices
* **⌨️ Keyboard shortcuts** - Quick undo with U, ESC, or Backspace

### UI/UX
* Beautiful gradient design with smooth animations
* Color-coded numbers for mine proximity
* Intuitive touch controls for mobile devices
* Animated win/loss feedback
* Comprehensive help modal with game instructions
* Relative timestamps for leaderboard entries ("2 hours ago")

## 🚀 Getting Started

### Play Locally

1. Clone this repository:

   ```bash
   git clone https://github.com/minesweeperjs/minesweeperjs.github.io
   ```
2. Navigate to the project folder:

   ```bash
   cd minesweeperjs.github.io
   ```
3. Open `index.html` in your browser.

That's it! No build tools, npm packages, or server required.

## 🌐 Play Online

You can access the latest version live here: **[minesweeperjs.github.io](https://minesweeperjs.github.io)**

## 🎯 How to Play

### Basic Controls
- **Left Click**: Reveal a cell
- **Right Click**: Place or remove a flag
- **Keyboard**: Press `U`, `ESC`, or `Backspace` to undo

### Game Rules
1. Click cells to reveal what's underneath
2. Numbers indicate how many mines are in adjacent cells (including diagonals)
3. Use flags to mark cells you think contain mines
4. Reveal all non-mine cells to win
5. Clicking a mine ends the game

### AI Mode
Enable AI Mode to watch the computer play:
- Uses advanced algorithms to solve puzzles
- Automatically flags discovered mines
- Recovers from mistakes using the undo system
- Progresses to harder difficulties after 2 wins per level

## 📂 Project Structure

```
index.html       # Complete game in a single file
                 # - HTML structure
                 # - CSS styling with responsive design
                 # - JavaScript game logic and AI
```

## 🛠️ Technologies Used

* **HTML5** - Semantic structure and SVG graphics
* **CSS3** - Modern layouts with Flexbox/Grid, animations, and gradients
* **JavaScript (ES6+)** - Game logic, AI algorithms, and state management
  - Classes and modules
  - LocalStorage for persistence
  - Advanced algorithms (constraint satisfaction, probability analysis)

## 🧠 AI Implementation

The AI uses a multi-layered decision-making approach:

1. **Deterministic Safe Moves** - Identifies cells that are guaranteed safe
2. **Obvious Mine Detection** - Flags cells that must contain mines
3. **Constraint Satisfaction** - Solves complex patterns using overlapping constraints
4. **Probability Analysis** - Calculates mine probability for each unrevealed cell
5. **Educated Guessing** - Makes optimal guesses when no certain moves exist
6. **Error Recovery** - Uses undo system to recover from mine hits

## 📱 Browser Compatibility

- ✅ Chrome/Edge (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🎨 Customization

The game is built with CSS custom properties for easy theming. Key variables include:
- Color gradients for primary UI elements
- Cell sizes and spacing (automatically responsive)
- Animation timings and effects

## 📜 License

This project is released under the **MIT License**. Feel free to use, modify, and distribute.

## 🙌 Acknowledgments

Inspired by the original **Minesweeper** game bundled with early Windows operating systems, enhanced with modern web technologies and AI capabilities.

## 🐛 Known Issues

- None currently reported

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest new features
- Submit pull requests
- Improve documentation

## 📧 Contact

For questions or feedback, please open an issue on GitHub.

---

**Enjoy playing Minesweeper Pro!** 💣🎮