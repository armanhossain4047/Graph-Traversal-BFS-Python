# 🚀 Graph Traversal using BFS

This repository contains a Python implementation of **Graph Traversal** using **Breadth-First Search (BFS)**. The program performs BFS traversal on a directed graph represented as an **adjacency matrix**.

## 📌 How It Works
The code implements BFS traversal by using a **queue** to explore nodes level by level.

### 🔥 Step-by-Step Execution

1. **Graph Representation** 📊
   - The graph is represented using an **adjacency matrix**, where:
     - `1` indicates an edge between two nodes.
     - `0` indicates no connection.
   - Example adjacency matrix:
     ```python
     graph = [
         [0, 1, 1, 0, 0, 0],
         [0, 0, 1, 1, 0, 0],
         [0, 0, 0, 1, 0, 0],
         [0, 0, 0, 0, 1, 0],
         [1, 1, 0, 0, 0, 1],
         [0, 0, 0, 0, 0, 0]
     ]
     ```

2. **Initialization** ⚙️
   - The `BFS` class is initialized with:
     - `graph` (Adjacency matrix)
     - `source` (Starting node for BFS traversal)
   - It also maintains:
     - `queue` (For storing nodes to be visited)
     - `visited_node` (Set of visited nodes)

3. **Breadth-First Search (BFS) Traversal** 🔄
   - Starts from the **source node**.
   - Visits all adjacent nodes level by level using a **queue**.
   - Prints the nodes in the order they are visited.

4. **Traversal Output** 📢
   - The program prints the BFS traversal path, showing the order in which nodes are visited.

## 💻 Example Input & Output
### Input:
```python
source = 4
```
### Output:
```
Graph Adjacency Matrix:
[0, 1, 1, 0, 0, 0]
[0, 0, 1, 1, 0, 0]
[0, 0, 0, 1, 0, 0]
[0, 0, 0, 0, 1, 0]
[1, 1, 0, 0, 0, 1]
[0, 0, 0, 0, 0, 0]
Source node is: 4
BFS Traverse: 4 0 1 5 2 3
```

## 📂 Files
- `bfs_traversal.py` → Python script implementing BFS traversal.
- `README.md` → This file (Project documentation).

## 🛠️ How to Run
1. Clone the repository:
   ```sh
   git clone https://github.com/armanHossain4047/Graph-BFS-Traversal.git
   ```
2. Navigate to the project directory:
   ```sh
   cd Graph-BFS-Traversal
   ```
3. Run the script:
   ```sh
   python bfs_traversal.py
   ```

## 🤝 Contributing
Feel free to fork this repository, submit issues, or suggest improvements!

## 📜 License
This project is **open-source** and available under the **MIT License**.

Happy Coding! 🚀🎯

