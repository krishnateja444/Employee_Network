# Employee Network Analysis System

A Python-based graph analytics project that models employees as nodes in a weighted communication network.

## Features

- Employee CRUD Operations
- CSV Data Persistence
- Graph-Based Employee Connections
- BFS Traversal
- DFS Traversal
- Dijkstra's Shortest Path Algorithm
- Prim's Minimum Spanning Tree Algorithm
- Hash Map Employee Lookup

## Data Structures Used

- Graph (Adjacency List)
- Dictionary (Hash Map)
- Queue
- Stack
- Heap (Priority Queue)

## Algorithms Implemented

### Breadth First Search (BFS)
Used for network traversal and connectivity analysis.

### Depth First Search (DFS)
Used for graph exploration and reachability.

### Dijkstra's Algorithm
Computes shortest communication paths between employees.

### Prim's Algorithm
Constructs a Minimum Spanning Tree for efficient network design.

## Complexity Analysis

| Algorithm | Time Complexity |
|------------|----------------|
| BFS | O(V + E) |
| DFS | O(V + E) |
| Dijkstra | O(E log V) |
| Prim MST | O(E log V) |

## Project Structure

employee-network/
├── employee.py
├── employee_management.py
├── graph_algorithms.py
├── main.py
├── data.csv
└── README.md

## Run

```bash
python main.py
```
