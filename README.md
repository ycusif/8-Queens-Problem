# 8-Queens Problem 🏆


This repository contains **8 different AI-based algorithms** to solve the **8-Queens Problem**, demonstrating various search and optimization techniques.

## 🌟 Introduction
The **8-Queens Problem** is a classic combinatorial puzzle requiring 8 queens to be placed on an 8×8 chessboard such that no two queens threaten each other. This means:
- No two queens share the same row.
- No two queens share the same column.
- No two queens share the same diagonal.

This problem is widely used in Artificial Intelligence to demonstrate search algorithms, constraint satisfaction problems, and optimization techniques.

## 🚀 Implementations
This project presents **8 different AI-based solutions**:
- **Breadth-First Search (BFS)** (`bfs.ipynb`)
- **Depth-Limited Search (DLS)** (`dls.ipynb`)
- **Iterative Deepening Search (IDS)** (`ids.ipynb`)
- **Genetic Algorithm (GA)** (`genetic.ipynb`)
- **Best-First Search (Heuristic BFS)** (`best_first_search.ipynb`)
- **Bidirectional Backtracking** (`bidirectional_backtracking.ipynb`)
- **Alpha-Beta Pruning** (`alpha_beta_pruning.ipynb`)
- **Hill Climbing** (`hill_climbing.ipynb`)

## 📂 Project Structure
```
8-queens-problem/
│── algorithms/
│   │── bfs.ipynb
│   │── dls.ipynb
│   │── ids.ipynb
│   │── genetic.ipynb
│   │── best_first_search.ipynb
│   │── bidirectional_backtracking.ipynb
│   │── alpha_beta_pruning.ipynb
│   │── hill_climbing.ipynb
│── docs/
│   │── AI201(BFS).pdf
│── images/
│   │── 8_queens_solution.png
│   │── code_screenshot.png
│── README.md
│── LICENSE
```

## 🎯 Expected Output
Each algorithm finds a valid queen placement. Example solution:
```
Q . . . . . . .
. . . . Q . . .
. . . . . . . Q
. . . Q . . . .
. . . . . Q . .
. Q . . . . . .
. . . . . . Q .
. . Q . . . . .
```

## 📷 Visual Representation
Example solution for the 8-Queens Problem:

![8-Queens Solution]([https://l1nk.dev/3E5bO)

## 🚀 Live Demo
- [Google Colab link](https://colab.research.google.com/drive/171nh_5z0hInLo6Nenitl5q_cSwv566Cj?usp=sharing)
   ```

## 🚀 Running the Code
Example for the **Genetic Algorithm**:
```python
import numpy as np
from genetic_algorithm import solve_8_queens
solve_8_queens()
```


## 📜 License
This project is licensed under the **MIT License**. All code is free to use and modify.

---
🔥 **Master AI search algorithms with the 8-Queens Problem!** 🚀

