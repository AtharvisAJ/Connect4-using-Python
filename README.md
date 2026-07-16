# 🎮 Connect4 Multiplayer Game

A desktop implementation of the classic **Connect 4** strategy game built using **Python** and **Pygame**, featuring support for **2–4 players**, customizable board sizes, and a persistent leaderboard powered by **MySQL**.

Developed as a first-year Bachelor of Engineering mini project to explore game development, GUI programming, algorithms, and database integration.

---

## 📖 Overview

Connect 4 is a strategy board game where players take turns dropping coloured discs into a vertical grid. The objective is to connect four discs in a horizontal, vertical, or diagonal line before your opponents.

This implementation extends the traditional game by introducing:

- Multiplayer support (2–4 players)
- Configurable board dimensions
- Player profile management
- Persistent leaderboard
- Match history storage

---

## ✨ Features

- 🎮 Supports **2–4 Players**
- 📐 Customizable board size
- 🖥️ Interactive GUI built with Pygame
- 🏆 Persistent leaderboard
- 👤 Player registration
- 💾 Match history stored in MySQL
- 🟢 Horizontal, Vertical & Diagonal win detection
- 🎨 Multiple player colours
- ⚡ Quick gameplay

---

## 🛠️ Tech Stack

### Language
- Python

### Libraries
- Pygame
- NumPy
- mysql-connector-python
- Tabulate

### Database
- MySQL

---

## 📂 Project Structure

```
.
├── connect4.py
├── README.md
└── docs/
    ├── Synopsis.pdf
    └── Presentation.pdf
```

---

## ⚙️ How It Works

1. Select the number of players (2–4)
2. Choose the board dimensions
3. Enter player names
4. Take turns placing discs
5. The application detects winning conditions automatically
6. Winner statistics are saved to the MySQL database
7. Leaderboard is updated after every game

---

## 🧠 Core Concepts Implemented

- Event-driven programming
- Game algorithms
- Collision & board state management
- Win detection algorithms
- Database connectivity
- CRUD operations
- GUI programming
- Session-based gameplay

---

## 🚀 Installation

### Clone the repository

```bash
git clone https://github.com/AtharvisAJ/Connect4-using-Python.git
```

### Install dependencies

```bash
pip install pygame numpy mysql-connector-python tabulate
```

### Configure MySQL

Create a database named:

```
connect4
```

Import the required tables or create them as needed.

### Run

```bash
python connect4.py
```

---

## 📈 Future Improvements

- AI opponent
- Online multiplayer
- Better animations
- Sound effects
- Save and resume games
- Improved UI/UX
- Cross-platform executable
- Difficulty levels

---

## 👨‍💻 My Contribution

This was a team project completed during the first year of my Bachelor of Engineering.

My contributions included:

- Designed the core game algorithm and gameplay logic
- Developed the win detection algorithms
- Implemented major portions of the Python application
- Contributed to pseudocode and project design
- Assisted in integrating game functionality with the database

---

## 🎯 Learning Outcomes

This project helped me gain practical experience with:

- Python Programming
- Object-oriented thinking
- Game Development
- GUI Design using Pygame
- MySQL Database Integration
- Algorithm Design
- Team Collaboration
- Software Development Lifecycle

---

## 📜 License

This project was developed for educational purposes.

---

## 👤 Author

**Atharv Joshi**
GitHub: https://github.com/AtharvisAJ
