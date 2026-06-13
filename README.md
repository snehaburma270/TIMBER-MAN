# 🌲 TIMBER-MAN

A 2D arcade game developed using **C++** and **SFML (Simple and Fast Multimedia Library)**. Inspired by the classic Timberman game, this project demonstrates game development concepts such as sprite animation, event handling, real-time rendering, game state management, and object movement.

---

## 🎮 Features

- Fullscreen game interface
- Dynamic animated background
- Moving bee animation with randomized speed and position
- Three independently moving clouds
- Real-time countdown timer bar
- Pause and Resume functionality
- Game Over screen
- Keyboard event handling
- Score display system
- Smooth sprite rendering using SFML

---

## 🛠️ Technologies Used

- C++
- SFML (Simple and Fast Multimedia Library)
- Object-Oriented Programming Concepts
- Game Loop Architecture

---

## 🎯 Controls

| Key | Function |
|------|----------|
| Space | Start / Restart Game |
| P | Pause / Resume Game |
| Esc | Exit Game |

---

## 📂 Project Structure

```text
TIMBER-MAN/
│
├── graphics/
│   ├── background.png
│   ├── bee.png
│   ├── cloud.png
│   └── tree.png
│
├── fonts/
│   └── KOMIKAP_.ttf
│
├── main.cpp
│
└── README.md
```

---

## 🚀 How to Run

### Prerequisites

- SFML 2.x installed
- C++ Compiler (GCC, MinGW, or MSVC)

### Clone Repository

```bash
git clone https://github.com/snehaburma270/TIMBER-MAN.git
```

### Build

Compile the source file and link SFML libraries.

Example (g++):

```bash
g++ main.cpp -o timberman -lsfml-graphics -lsfml-window -lsfml-system
```

### Run

```bash
./timberman
```

---

## 🧠 Concepts Implemented

- Real-Time Game Loop
- Delta Time (dt) Based Movement
- Sprite Rendering
- Texture Management
- Event Handling
- Randomized Object Spawning
- State Management (Start, Pause, Game Over)
- UI Elements using SFML Text Objects

---

## 🔮 Future Improvements

- Player Character Animation
- Tree Chopping Mechanics
- Branch Collision Detection
- Sound Effects and Background Music
- High Score System
- Difficulty Levels
- Leaderboard Support

---

## 👩‍💻 Author

**Sneha Burma**

GitHub: https://github.com/snehaburma270

---

## 📜 License

This project was developed for educational and learning purposes as part of game development practice using C++ and SFML.

---

### Repository Description

🌲 Timber-Man is a 2D arcade game built with C++ and SFML featuring animated environments, countdown timer mechanics, pause/resume functionality, and real-time game rendering.
