# 🏓 Ping Pong Game (Assembly Language)

A classic **2-Player Offline Ping Pong** game developed entirely in **x86 Assembly Language**. This project recreates the timeless table tennis experience in a simple graphical interface where two players compete on the same keyboard.

The project was built to strengthen understanding of **low-level programming**, **computer graphics**, **keyboard interrupt handling**, **game loops**, and **real-time collision detection** using Assembly Language.

---

## 🎮 Features

* 🏓 Two-player offline gameplay
* 🎯 Real-time ball movement
* 🚀 Smooth paddle controls
* 💥 Ball collision detection with paddles
* 🧱 Collision detection with screen boundaries
* 📈 Dynamic ball bouncing mechanics
* 🧮 Score tracking system
* 🔄 Ball reset after each point
* ⌨️ Keyboard-controlled paddles
* 🎨 Simple graphical game interface
* ⚡ Lightweight and fast execution

---

## 🎮 Controls

### Player 1 (Left Paddle)

| Key   | Action    |
| ----- | --------- |
| **W** | Move Up   |
| **S** | Move Down |

### Player 2 (Right Paddle)

| Key   | Action    |
| ----- | --------- |
| **↑** | Move Up   |
| **↓** | Move Down |

---

## 🛠 Technologies Used

* x86 Assembly Language
* DOS Interrupts
* BIOS Interrupts
* VGA Graphics Mode
* Keyboard Interrupt Handling

---

## ⚙️ Game Mechanics

* The ball starts from the center of the screen.
* Players move their paddles vertically to prevent the ball from passing.
* The ball bounces realistically when it collides with:

  * A paddle
  * The top wall
  * The bottom wall
* A point is awarded when a player misses the ball.
* The ball resets after every score.
* The game continues until the predefined winning score is reached (if implemented).

---

## 🧠 Concepts Demonstrated

This project demonstrates practical implementation of:

* Assembly Programming
* Low-Level Memory Manipulation
* Graphics Programming
* Real-Time Game Loop
* Collision Detection
* Keyboard Input Handling
* Coordinate-Based Animation
* Game State Management

---

## 📂 Project Structure

```text
.
├── main.asm          # Main game source code
├── assets/           # Images or additional resources (if any)
├── README.md
└── executable        # Compiled game (optional)
```

---

## 🚀 How to Run

1. Install **DOSBox** or an Assembly-compatible emulator.
2. Assemble the source code using your preferred assembler (MASM/TASM/NASM, depending on the project).
3. Run the generated executable.
4. Enjoy a two-player Ping Pong match!

---

## 🎯 Learning Outcomes

This project was developed to gain hands-on experience with:

* Low-level software development
* Assembly Language programming
* Game development fundamentals
* Computer graphics
* Interrupt handling
* Problem-solving and debugging

---

## 📸 Preview

> Add screenshots or gameplay GIFs here for a better showcase.

Example:

```
/screenshots/gameplay.png
```

---

## 🤝 Future Improvements

* 🔊 Sound effects
* 🎵 Background music
* 🎮 Single-player mode with AI
* ⚡ Adjustable difficulty levels
* 🏆 High score system
* 🎨 Improved graphics
* ⏸ Pause and Resume functionality
* 🎯 Start menu
* 🖥 Full-screen support

---

## 👨‍💻 Author

**Noyan Siddiqui**

Data Science Student | AI & Machine Learning Enthusiast

GitHub: https://github.com/noyansiddiqui99-maker

LinkedIn: https://linkedin.com/in/noyan-siddiqui-b39139373

---

⭐ If you found this project interesting, consider giving it a **star** on GitHub!
