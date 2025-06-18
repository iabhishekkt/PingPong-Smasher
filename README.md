# 🏓 Ping Pong Arcade (C++ with Raylib)

Welcome to **Ping Pong Arcade** – a classic Pong-inspired game created using Raylib Library! This is a beginner C++ project aimed at learning how to build real-time games with graphics, input handling, object-oriented programming, and simple AI.

---

## 📜 Table of Contents

* [🎮 About the Game](#-about-the-game)
* [⚙️ Requirements](#️-requirements)
* [🛠️ How to Run](#️-how-to-run)
* [📦 Code Structure](#-code-structure)
* [🧠 What I Learned](#-what-i-learned)
* [💡 Future Ideas](#-future-ideas)
* [📚 Credits](#-credits)

---

## 🎮 About the Game

This project is a modern re-imagining of the iconic arcade game **Pong** – written in **C++** using the **Raylib graphics library**.

Features:

* Two paddles (Player vs CPU)
* Moving ball with basic physics
* Collision detection
* Scoring system
* Stylish blue retro visuals
* CPU paddle tracks the ball automatically

---

## ⚙️ Requirements

* C++ Compiler (like `g++` or MSVC)
* Raylib installed on your system
* CMake or any build system (Optional)

---

## 🛠️ How to Run

### 🔧 Step 1: Clone the Repository

```bash
git clone https://github.com/yourusername/ping-pong-arcade.git
cd ping-pong-arcade
```

### 🔧 Step 2: Compile the Code

If you have Raylib installed:

```bash
g++ main.cpp -o pong -lraylib -lGL -lm -lpthread -ldl -lrt -lX11
```

> For Windows, link with `-lraylib -lopengl32 -lgdi32 -lwinmm` instead.

### 🎮 Step 3: Run the Game

```bash
./pong
```

Enjoy the game!

---

## 📦 Code Structure

* `main.cpp`: Main source code with the game logic.

  * `Ball` class handles the ball's position, movement, drawing, and collision.
  * `Paddle` class handles user-controlled paddle (arrow keys).
  * `CpuPaddle` inherits from `Paddle` and auto-tracks the ball's Y-position.
* Uses Raylib for drawing, animation, input, and screen rendering.

---

## 🧠 What I Learned

As a beginner exploring C++, this project taught me:

* How to set up and use an external library (Raylib)
* Basics of game loops (`while` loops with rendering and updates)
* Object-oriented programming (OOP): classes, inheritance
* Handling real-time input (keyboard controls)
* Simple AI for CPU paddle
* Collision detection between objects
* Using `DrawCircle`, `DrawRectangleRounded`, `DrawLine`, and `DrawText` from Raylib

---

## 💡 Future Ideas

If you'd like to take this further:

* Add sound effects (Raylib supports this!)
* Add a start menu or pause screen
* Improve AI difficulty (slow reaction time, error margin)
* Add particle effects or ball trail
* Multiplayer over keyboard or network
* Power-ups (speed boost, shrink paddle, etc.)

---

## 📚 Credits

* **Raylib** – simple and powerful C/C++ game development library.
* **YouTube Tutorials** – helped me understand the fundamentals of Raylib and C++ gameplay mechanics.
* **Myself** – a beginner trying to explore the world of game development through simple and fun projects.

---

> Thanks for checking out this project. Your suggestions are welcome!

Give it a star if you like it!

