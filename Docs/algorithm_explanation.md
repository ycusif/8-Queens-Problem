# Algorithm Explanation 🧠  

This document provides a detailed explanation of the 8 different AI-based algorithms implemented in this repository to solve the **8-Queens Problem**.  

## 1️⃣ Breadth-First Search (BFS)  
- **Type**: Uninformed Search  
- **How it Works**:  
  - Explores all possible placements level by level.  
  - Uses a queue (FIFO) to store board configurations.  
  - Guaranteed to find a solution if one exists, but can be slow due to memory usage.  

## 2️⃣ Depth-First Search (DFS)  
- **Type**: Uninformed Search  
- **How it Works**:  
  - Explores one branch deeply before backtracking.  
  - Uses a stack (LIFO) for board configurations.  
  - Efficient in space but can get stuck in deep branches.  

## 3️⃣ Iterative Deepening Search (IDS)  
- **Type**: Combination of BFS & DFS  
- **How it Works**:  
  - Performs DFS up to a depth limit, then increases the depth.  
  - Balances space and completeness.  
  - More memory-efficient than BFS but still guarantees finding the solution.  

## 4️⃣ Bidirectional Backtracking  
- **Type**: Backtracking Search  
- **How it Works**:  
  - Starts from both ends (beginning and goal) and searches toward the middle.  
  - Reduces search space significantly, making it faster.  
  - Requires careful implementation to ensure paths meet.  

## 5️⃣ Alpha-Beta Pruning  
- **Type**: Optimization of Minimax Algorithm  
- **How it Works**:  
  - Used in decision-making to eliminate unneeded branches.  
  - Reduces computation time by skipping unnecessary evaluations.  
  - Often used in game-playing AI.  

## 6️⃣ Best-First Search  
- **Type**: Informed Search  
- **How it Works**:  
  - Uses a heuristic to choose the most promising path.  
  - More efficient than BFS & DFS but depends on the heuristic function.  
  - Can still explore unnecessary paths if heuristic is not perfect.  

## 7️⃣ Hill Climbing  
- **Type**: Local Search Algorithm  
- **How it Works**:  
  - Starts with a random solution and improves it step by step.  
  - Stops when no further improvements can be made.  
  - Fast but can get stuck in **local optima** (not the best overall solution).  

## 8️⃣ Genetic Algorithm  
- **Type**: Evolutionary Algorithm  
- **How it Works**:  
  - Uses **mutation, selection, and crossover** to evolve better solutions.  
  - Mimics biological evolution.  
  - Can escape local optima but is computationally expensive.  

---

## 🏆 **Conclusion**  
Each algorithm has strengths and weaknesses. **Uninformed searches** like BFS/DFS guarantee solutions but can be slow, while **heuristic-based approaches** like Hill Climbing and Genetic Algorithms provide faster, more efficient solutions but may not always find the absolute best answer.  

🔹 **For exact solutions** → Use BFS, DFS, IDS, or Bidirectional Backtracking.  
🔹 **For heuristic-based solutions** → Use Best-First Search, Hill Climbing, or Genetic Algorithms.  

--
