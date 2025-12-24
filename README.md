# PacMan-Game

A classic 2D Pac-Man game built using Java and Swing. This project features smooth movement, ghost AI, and collision detection using a grid-based map system.



## 🎮 Features
* **Classic Gameplay:** Navigate Pac-Man through the maze to eat all the pellets.
* **Ghost AI:** Four distinct ghosts (Red, Pink, Blue, and Orange) with basic tracking logic.
* **Power-Ups:** Eat 'Power Food' to turn the ghosts blue and make them vulnerable.
* **Visuals:** Custom sprite support for Pac-Man's direction and ghost states.

## 📂 Project Structure
The project is organized in a flat directory for simplicity:
* `App.java`: The entry point that initializes the game window (JFrame).
* `PacMan.java`: The core engine containing game logic, rendering, and input handling.
* `*.png`: Image assets for Pac-Man, ghosts, walls, and food.
* `*.class`: Compiled bytecode files.

## 🚀 How to Run

### Prerequisites
* **Java Development Kit (JDK) 8 or higher** installed on your machine.
* A terminal or command prompt.

### Steps
1. **Clone or Download** this repository to your local machine.
2. Open your terminal and navigate to the project folder:
   ```bash
   cd "C:\Users\User\OneDrive\Desktop\projects\pac man project\java"
3. Compile the project:
    ```bash
    javac App.java PacMan.java
4. Run the game:
    ```bash
    java App
### ⌨️ Controls
* Up Arrow: Move Pac-Man Up
* Down Arrow: Move Pac-Man Down
* Left Arrow: Move Pac-Man Left
* Right Arrow: Move Pac-Man Right

### 🛠️ Technologies Used
* Language: Java
* Library: Java Swing & AWT (for Graphics and UI)