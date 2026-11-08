# ⚡ Zig Zag Numbers

An interactive matrix puzzle game where players connect numbers in sequential order along evolving **Zig-Zag** patterns across 100 progressively challenging levels.

## 🎮 How to Play

1. Open `index.html` in any web browser.
2. Select or drag through the numbered cells in ascending order: **1 ➔ 2 ➔ 3 ➔ ... ➔ N**.
3. Follow the highlighted Zig-Zag pattern (horizontal, vertical, diagonal, or reverse weaves).
4. Build combos by selecting numbers rapidly to boost your score!
5. Clear all numbers before the timer expires to complete the level and unlock the next challenge.

## 🚀 Features

- **100 Dynamic Levels**: Grid sizes smoothly scale from 3×3 (9 numbers) up to 7×7 (49 numbers) as you progress.
- **Dynamic Zig-Zag Traversal Modes**:
  - Horizontal Serpentine (Left-to-Right, Right-to-Left)
  - Vertical Serpentine (Top-to-Bottom, Bottom-to-Top)
  - Diagonal Zig-Zag (Snake weave across diagonals)
  - Inverted Horizontal & Vertical Weaves
  - Corner Diagonal Waves
- **Intuitive Controls**: Supports single-click, tap, and fluid click-and-drag / touch-swipe selection.
- **Smooth Progressive Difficulty ("Slowly Tough to Play")**:
  - Early levels (1–5) offer relaxed warm-ups and clear hints.
  - Mid levels (6–45) introduce vertical and diagonal zig-zags with larger grids.
  - Advanced levels (46–100) challenge your memory, speed, and eye-tracking.
- **Difficulty Modes**:
  - **Easy**: Extra time limit and subtle target beacon hints.
  - **Medium**: Balanced time and standard visual cues.
  - **Hard (Memory Zig-Zag)**: Numbers preview for 3.5 seconds, then flip face-down! Remember the path to clear the level.
- **Audio Synthesizer**: Built-in Web Audio API melodies (ascending pentatonic notes per selection, combo chimes, fanfare chords, and mute toggle). Zero external audio dependencies.
- **Score, Combos & Stars**: Earn 1 to 3 stars per level based on speed, accuracy, and combo streaks.
- **Leaderboard & Best Times**: Track personal best records stored locally.
- **Responsive Design**: Optimized for mobile, tablet, and desktop screens with scalable SVG path rendering.

## 📁 Repository Structure

- `index.html` — Self-contained HTML5, CSS3, and JavaScript game application.
- `.github/workflows/static.yml` — Automated GitHub Pages deployment workflow.

## 💻 Run Locally

Simply open `index.html` in any browser:

```bash
# Windows
start index.html

# macOS
open index.html

# Linux
xdg-open index.html
```

Or serve via any static HTTP server:

```bash
python -m http.server 8080
```
Then visit `http://localhost:8080`.
