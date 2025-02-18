# 8-Queens Problem 🏆






This repository contains multiple AI-based implementations of the **8-Queens Problem**, demonstrating different search and optimization techniques.

## 🌟 Introduction

The **8-Queens Problem** is a classic combinatorial puzzle that requires placing 8 queens on an 8×8 chessboard so that no two queens threaten each other. This means:

- No two queens share the same row.
- No two queens share the same column.
- No two queens share the same diagonal.

This problem is widely used in Artificial Intelligence to demonstrate search algorithms, constraint satisfaction problems, and optimization techniques.

## 🚀 Implementations

This project presents solutions using:

- **Breadth-First Search (BFS)** (`8_queens_(BFS).ipynb`)
- **Depth-Limited Search (DLS)** (`8_queens_(DLS).ipynb`)
- **Iterative Deepening Search (IDS)** (`Iterative_Deepening_Search_(IDS).ipynb`)
- **Genetic Algorithm (GA)** (`8_queens_(gentic).ipynb`)
- **Best-First Search (Heuristic BFS)** (`ai.ipynb`)

## 📂 Project Structure

```
8-queens-problem/
│── algorithms/
│   │── 8_queens_(BFS).ipynb
│   │── 8_queens_(DLS).ipynb
│   │── Iterative_Deepening_Search_(IDS).ipynb
│   │── 8_queens_(gentic).ipynb
│   │── ai.ipynb
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
Q . . . . . . .  
. . . . Q . . .  
. . . . . . . Q  
. . . Q . . . .  
. . . . . Q . .  
. Q . . . . . .  
. . . . . . Q .  
. . Q . . . . .  



Example of one of the algorithms in action:  

### **Algorithm Execution Steps:**  
1️⃣ **Initialize a population** of random board configurations.  
2️⃣ **Evaluate fitness** by counting conflicts (queens attacking each other).  
3️⃣ **Select parents** based on fitness.  
4️⃣ **Apply crossover** (combine parents to create new solutions).  
5️⃣ **Mutate** some individuals to introduce diversity.  
6️⃣ **Repeat until a valid board is found** (fitness = 0).  

### **Example Output (Genetic Algorithm in Action)**  
```
Generation 1: Best fitness = 5  
Generation 2: Best fitness = 3  
Generation 3: Best fitness = 2  
Generation 4: Best fitness = 1  
Generation 5: Solution found!  
```
Final valid board configuration:  
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


## 🚀 Live Demo

- [Run on Google Colab](https://colab.research.google.com/github/yourusername/8-queens-problem)


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
