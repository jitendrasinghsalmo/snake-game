<div align="center">

# 🐍 Snake Game
### A classic Snake Game built with HTML, CSS and JavaScript (Canvas API)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Canvas](https://img.shields.io/badge/Canvas-API-green)

</div>

---

## 📑 Table of Contents

- [About](#-about)
- [Features](#-features)
- [Controls](#-controls)
- [Tech Stack](#️-tech-stack)
- [Project Structure](#-project-structure)
- [How It Works](#-how-it-works)
- [Game Settings](#️-game-settings)
- [Getting Started](#-getting-started)
- [Future Scope](#-future-scope)
- [Author](#-author)

---

## 📌 About

A simple Snake Game drawn on an HTML `<canvas>`. The snake moves on a grid, eats food to grow and the game ends when it hits a wall. No framework or library is used, only plain HTML, CSS and JavaScript.

---

## ✨ Features

- 🟩 Green snake and 🟥 red food on a yellow canvas
- 🔢 Live score counter
- 📈 Snake grows every time it eats food
- 🎲 Food appears at a random cell on the grid
- 💀 "game over" message when the snake hits a wall

---

## 🎮 Controls

| Key | Action |
|---|---|
| ⬆️ Arrow Up | Move up |
| ⬇️ Arrow Down | Move down |
| ⬅️ Arrow Left | Move left |
| ➡️ Arrow Right | Move right |

---

## 🛠️ Tech Stack

| Layer | Technologies |
|---|---|
| **Structure** | HTML5 (`<canvas>`) |
| **Styling** | CSS3 |
| **Logic** | JavaScript (Canvas API, DOM events, `setInterval`) |

---

## 📁 Project Structure

```text
Snake_Game/
├── index.html    # Canvas and page layout
└── Game.js       # Game logic (draw, update, controls)
```

---

## ⚙️ How It Works

1. The snake is stored as an array of cells, for example `[[0, 0]]`.
2. `setInterval` runs `draw()` and `update()` every 200 ms.
3. `update()` adds a new head cell in the current direction.
4. If the head reaches the food, the score increases and a new food cell is generated. Otherwise the tail is removed, so the snake moves forward.
5. `draw()` clears the canvas and draws the snake, the food and the score.
6. If the snake goes outside the canvas, `gameOver` becomes `true` and the game stops.

---

## ⚙️ Game Settings

| Setting | Value |
|---|---|
| Canvas size | 1200 x 500 |
| Cell size | 50 px |
| Speed | 200 ms per move |
| Start position | Top-left, moving right |

---

## 🚀 Getting Started

No installation is needed.

**1. Download or clone the repository**

**2. Open the project folder**

**3. Open `index.html` in any browser**

Use the arrow keys to control the snake.

---

## 🧭 Future Scope

- Self-collision detection
- Restart button after game over
- Prevent the snake from reversing into itself
- High score saved in the browser
- Touch controls for mobile
- Responsive canvas size
- Increasing speed with higher score

---

## 👨‍💻 Author

**Jitendra Singh**
Java Full Stack Developer | Bengaluru, India

- GitHub: [jitendrasinghsalmo](https://github.com/jitendrasinghsalmo)
- LinkedIn: [Jitendra Singh](https://www.linkedin.com/in/jitendra-singh-725698290)

---

<div align="center">

⭐ If you like this project, please give it a star on GitHub!

</div>
