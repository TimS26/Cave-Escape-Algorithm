# 🪨 Cave Escape Algorithm

**Mine Path Finder** is a console-based C++ application that finds the shortest path from the starting position to the exit on a mine map using the **Breadth-First Search (BFS)** algorithm.

---

## ✅ Features:
- Simple and intuitive map input.
- Finds the **shortest** path automatically.
- Step-by-step directions using:
  - `N` — North  
  - `E` — East  
  - `S` — South  
  - `W` — West  

---

## ✅ How to Use:
1. Compile the program:
```bash
g++ mine_path_finder.cpp -o mine_path_finder
---
Examle input:
Enter map dimensions (Row's, Column's): **3** 4**
Enter mine map ('*' for start, 'X' for exit, '.' for path, '#' for wall. Use the space button between your inputs.):
. . . *
. # # .
X . . .
---
Resot:
Path to exit: SSWWW
