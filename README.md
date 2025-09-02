# Searching Algorithms in Artificial Intelligence

This project demonstrates various **search algorithms** commonly used in Artificial Intelligence (AI) for problem-solving and pathfinding. These algorithms are fundamental for exploring state spaces, optimizing decisions, and finding solutions efficiently.

---

## 📌 Algorithms Implemented

### 1. **Uninformed (Blind) Search**
- **Breadth-First Search (BFS)** – Explores nodes level by level, guaranteeing the shortest path in an unweighted graph.
- **Depth-First Search (DFS)** – Explores nodes deeply before backtracking, memory efficient but may not find the shortest path.
- **Uniform Cost Search (UCS)** – Expands the node with the lowest path cost, suitable for weighted graphs.
- **Depth-Limited Search (DLS)** – DFS with a depth cutoff to avoid infinite loops.
- **Iterative Deepening DFS (IDDFS)** – Combines DFS space efficiency and BFS completeness.

### 2. **Informed (Heuristic) Search**
- **Greedy Best-First Search** – Chooses the node with the lowest heuristic value (fast but not always optimal).
- **A\* Search** – Uses both path cost and heuristic, guaranteeing the optimal solution if the heuristic is admissible.
- **Hill Climbing** – Local search using heuristics, can get stuck in local maxima.

---
