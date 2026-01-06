# 3D Maze Generator

![Language](https://img.shields.io/badge/Language-C%2B%2B-blue)
![Focus](https://img.shields.io/badge/Focus-DSA-orange)
![Status](https://img.shields.io/badge/Status-Completed-green)

## 📖 Project Description

This is a C++ based Procedural 3D Maze Generator. It utilizes fundamental Data Structures and Algorithms (DSA) to generate unique, solvable mazes every time the program runs.

The project was designed to demonstrate the practical application of graph theory and backtracking algorithms in a 3D environment. It features an interactive gameplay loop where the player must navigate through generated structures of varying complexity.

## ✨ Key Features

* **3 Difficulty Modes:**
    * **Easy:** Smaller grid size, designed for quick runs.
    * **Medium:** Balanced complexity with moderate branching.
    * **Hard:** Large grid size with complex dead-ends and longer paths.
* **Procedural Generation:** Uses randomization so that no two mazes are ever the same.
* **Path Validation:** Ensures that a valid path always exists from the start point to the exit.
* **Optimized Performance:** Efficient memory management using C++ pointers and dynamic allocation.

## ⚙️ Technical Details

This project applies specific DSA concepts to manage the maze logic:

### Algorithms Used
* **Depth First Search (DFS) / Backtracking:** This is the core algorithm used for generation. It visits a cell, marks it as visited, and recursively moves to a random neighbor. If it hits a dead end, it backtracks (pops from the stack) until it finds a new path.

### Data Structures Used
* **Stacks:** Used to track the history of visited cells during the generation process to allow for backtracking.
* **Multi-dimensional Arrays:** Used to represent the 3D grid coordinate system (x, y, z) and store the state of walls and open paths.
* **Structs:** Custom data types used to define the properties of a "Cell" (walls, visited boolean, coordinates).

## 🚀 How to Run

1.  **Clone the repository** (or download the source code).
2.  **Compile the Code:**
    Open your terminal or command prompt in the project folder and run:
    ```bash
    g++ main.cpp -o maze
    ```
    *(Note: If the project uses multiple .cpp files, you may need to compile them together).*
3.  **Run the Game:**
    ```bash
    ./maze
    ```

## 🎮 Controls

* **Keyboard Input:** Use standard keys (W, A, S, D or Arrow Keys) to navigate the player through the maze.
* **Objective:** Find the exit point in the generated 3D grid.

---
*Created as a Computer Science project exploring Data Structures and Algorithms.*
