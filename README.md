# 🎮 **Falling Shapes Game**  

![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python)
![Game](https://img.shields.io/badge/Genre-Arcade-green)
![License](https://img.shields.io/badge/License-MIT-orange)

## 📝 **Description**
Falling Shapes is an engaging arcade-style game where players control a paddle to catch randomly falling shapes. Each shape has different properties and awards varying points, with special effects for certain combinations.

## ✨ **Key Features**
- 🕹️ Intuitive keyboard controls (Left/Right arrows)
- 🔵 4 distinct shape types (Circle, Square, Triangle, Turtle)
- 🌈 Random colors and sizes for dynamic gameplay
- 📊 Comprehensive scoring system with high score tracking
- ⚡ Progressive difficulty system
- 💥 Special shape interactions and effects

## 📦 **Requirements**
- Python 3.8+
- Turtle module (included in standard library)

## ⚙️ **Installation**
```bash
git clone https://github.com/yourusername/falling-shapes-game.git
cd falling-shapes-game
```

## 🚀 **How to Run**
```bash
python main.py
```

## 🎮 **Gameplay Mechanics**

| Shape      | Points | Special Effect              |
|------------|--------|-----------------------------|
| 🔵 Circle  | +1     | Standard shape              |
| ⬛ Square  | +2     | Faster movement             |
| 🔺 Triangle| 0      | Resets current score        |
| 🐢 Turtle  | +5     | White turtle ends the game  |

## 🖥️ **Game Interface**
```
   +---------------------------+
   |         Score: 00         |
   |       High Score: 00      |
   |                           |
   |                           |
   |            🐢             |
   |                           |
   |                           |
   |          ======           |
   +---------------------------+
```

## 🏆 **Scoring System**
- Earn points by catching shapes
- Compete against your high score
- Special bonus effects for consecutive catches

## 📂 **Project Structure**
```
falling_shapes/
├── main.py            # Main game loop
├── game/
│   ├── paddle.py      # Paddle controller
│   ├── shapes.py      # Falling shapes logic
│   └── scoreboard.py  # Score system
├── assets/            # Game assets
└── README.md          # Documentation
```

## 🤝 **Contributing**
Contributions are welcome! Please open an issue or submit a PR for any improvements.

## 📜 **License**
This project is licensed under the [MIT License](LICENSE).

---

**🎮 Happy Gaming!** For any issues, please open a ticket in the project repository.
