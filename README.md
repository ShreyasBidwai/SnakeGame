# 🐍 SnakeMania

**Best way to brush your JavaScript logic?**  
Not watching endless tutorials.  
Not reading a thousand blog posts.  
It’s **actually building something**—and then breaking it, fixing it, and making it cooler.  

This project is exactly that: a classic **Snake Game** built with plain **HTML, CSS, and JavaScript**.  
No frameworks. No magic. Just logic, implementation, and a little bit of pixel nostalgia.

---

## 🎯 Features

- **Pure JavaScript game loop** using `requestAnimationFrame`
- **Dynamic snake movement** controlled by arrow keys
- **Score tracking** and **Hi-Score persistence** via `localStorage`
- **Collision detection** (walls + self)
- **Randomized food generation**
- **Sound effects** for movement, eating, and game over
- **Responsive, grid-based design** using CSS

---

## 📂 Project Structure

├── index.html # Game structure & container elements
├── style.css # Styles for board, snake, food, and scoreboard
├── index.js # Game logic, controls, and rendering
└── music/ # Sound files for game events


---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/SnakeMania.git
   cd SnakeMania

music/
├── food.mp3
├── gameover.mp3
├── move.mp3
└── music.mp3

xdg-open index.html    # Ubuntu way

Play!
Use the arrow keys to control the snake. Eat food, grow longer, and beat your Hi-Score.
