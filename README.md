# Oren's Math Game

A browser-based math quiz game with multiple difficulty levels and randomly generated arithmetic questions.

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Demo](#demo)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Game Logic](#game-logic)
- [License](#license)

---

## Overview

Oren's Math Game is an interactive arithmetic quiz built entirely in vanilla HTML, CSS, and JavaScript. Players choose a difficulty level and are presented with randomly generated math questions. The game tracks the score and provides feedback on correct and incorrect answers.

---

## Features

- 🎮 Multiple difficulty levels
- 🔢 Randomly generated arithmetic questions
- ✅ Instant feedback on answers
- 📊 Score tracking throughout the session
- 🖱️ Custom cursor styles for enhanced UX
- 🎨 Shiny button component

---

## Demo

Open `index.html` directly in your browser — no build step or server required.

---

## Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Semantic page structure |
| CSS3 | Game styling and layout |
| JavaScript (ES6+) | Game logic, random question generation, score tracking |

---

## Project Structure

```
oren-s-math-game/
├── index.html
├── scripts/
│   └── game_logic.js       # All game logic: question generation, scoring, state
├── styles/
│   ├── general.css         # Base/reset styles
│   ├── game_style.css      # Game board and UI styles
│   └── shiny_button.css    # Button component styles
└── images/
    ├── cursor_24x24.png
    ├── cursor-click_24x24.png
    ├── select-cursor_24x24.png
    ├── select-cursor-3_24x24.png
    └── unavailable-cursor_24x24.png
```

---

## Getting Started

1. Clone or download the repository.
2. Open `index.html` in any modern browser.

No internet connection, dependencies, or build tools are required.

---

## Game Logic

All game logic is contained in `game_logic.js`:

- **Difficulty levels** — control the range of numbers used in questions
- **Question generation** — randomly creates arithmetic problems (addition, subtraction, multiplication, etc.) based on the selected difficulty
- **Answer validation** — compares the user's input against the correct answer
- **Score tracking** — maintains the player's running score for the session

---

## License

This project is intended for educational and portfolio purposes.
