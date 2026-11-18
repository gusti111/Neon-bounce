<div align="center">

# NEON BOUNCE

**An infinite runner built for the browser.**

A minimal arcade experience powered by HTML Canvas.

</div>

---

## Overview

Neon Bounce is a responsive, single-page endless-runner game. The player jumps to avoid obstacles, keeps the run alive, and aims to beat a locally stored high score. The visual direction uses a neon interface with a full-screen Canvas playfield.

## Features

- Full-screen Canvas gameplay with viewport-aware scaling.
- Jump input through keyboard, mouse, or touch.
- Score and best-score display.
- Progressive difficulty: game speed increases during longer runs.
- High-score persistence through browser localStorage.
- Responsive rendering with device-pixel-ratio handling.
- Lightweight single-file implementation.

## Controls

| Action | Input |
| --- | --- |
| Start or jump | Space, click, or tap |
| Mobile play | Tap the game area |

## Technology

- HTML5
- CSS3
- Vanilla JavaScript
- HTML Canvas 2D API
- Browser localStorage

The page loads display fonts from Google Fonts. An internet connection may be required for those fonts; the game logic itself is bundled locally in the HTML file.

## Run locally

    git clone https://github.com/gusti111/Neon-bounce.git
    cd Neon-bounce
    python -m http.server 8000

Open http://localhost:8000.

No package manager, dependency installation, or compilation is required.

## Project structure

    Neon-bounce/
    ├── index.html
    ├── .gitignore
    └── LICENSE

## Project status

A self-contained browser game prototype. High scores are local to the current browser profile; there is no account system or online leaderboard.

## Author

**Gusty Faqikh** · [GitHub](https://github.com/gusti111)