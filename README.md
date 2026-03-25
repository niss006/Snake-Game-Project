# Snake-Game-Project
### Overview
A lightweight, terminal-based recreation of the classic Snake arcade game. Built entirely in C, this project focuses on real-time logic and efficient memory handling without the need for external graphics libraries.

### Objectives
- Real time logic: Implementing a non-blocking game loop.
- Memory and data: Managing snake growth using coordination arrays
- System Calls: Utilizing Unix-specific libraries (termios.h, select) for terminal handling.

### 🎮 Features

| Feature | Technical Detail |
| :--- | :--- | :--- |
| **Non-blocking Input** |Uses termios to capture keystrokes without pausing the game loop.|
| **Tail Movement** | Array-shifting logic ensures the tail follows the head's previous coordinates.|
| **Fruit & Scoring** |Randomized coordinate generation and dynamic score scaling. |
| **Collision Engine** |Real-time checks for self-collision to trigger Game Over states. |
| **Border Wrapping** | Seamless "screen wrapping" (reappearing on the opposite side). |


### 🏁 Conclusion
This Snake implementation successfully demonstrates the power of C in creating efficient, real-time applications. By bypassing external graphics libraries and working directly with Unix terminal attributes, I was able to build a lightweight game that focuses on pure logic and performance. It’s a proud first step in my coding journey!

