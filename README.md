# Pathfinding Visualizer

![HTML](https://img.shields.io/badge/HTML5-orange)
![CSS](https://img.shields.io/badge/CSS3-blue)
![JavaScript](https://img.shields.io/badge/JavaScript-yellow)
![Algorithms](https://img.shields.io/badge/Graph-Algorithms-green)

An interactive, Google Maps-inspired pathfinding and route-planning application built to visualize graph algorithms and understand shortest-path computation. Users can explore different pathfinding algorithms on a dynamic weighted graph with customizable edge weights, simulated traffic, road closures and animated algorithm execution.

## Tech Stack

- **Frontend:** HTML5, CSS3, JavaScript (ES6+)
- **Data Structures:** Graphs, Priority Queues, Adjacency Representations
- **Algorithms:** BFS, DFS, Dijkstra's Algorithm, A* Search, Bellman-Ford, Floyd-Warshall
- **Visualization:** DOM Manipulation, CSS Animations, JavaScript

## Features

### 1. Pathfinding Algorithms

- **Breadth-First Search (BFS):** Explores nodes level by level to find the shortest path in an unweighted graph.
- **Depth-First Search (DFS):** Explores graph branches deeply before backtracking.
- **Dijkstra's Algorithm:** Finds the shortest path in a weighted graph with non-negative edge weights.
- **A* Search:** Uses heuristic-based search to efficiently explore promising paths.
- **Bellman-Ford Algorithm:** Computes shortest paths while supporting negative edge weights.
- **Floyd-Warshall Algorithm:** Calculates shortest paths between all pairs of vertices.

### 2. Dynamic Graph Visualization

- Interactive weighted graph with customizable edge weights.
- Visual representation of nodes, edges and traversal sequences.
- Animated algorithm execution to illustrate how different algorithms explore the graph.
- Comparative visualization of shortest-path algorithms.

### 3. Route Planning and Simulation

- Google Maps-inspired route-planning interface.
- Traffic simulation through adjustable edge weights.
- Road closure simulation to block selected routes.
- Real-time route recalculation when graph conditions change.
- Visual identification of the selected shortest path.

### 4. Data Structures and Optimization

- Efficient graph representations for graph traversal.
- Priority queues for efficient minimum-distance selection.
- Heuristic-based search for A* pathfinding.
- Algorithm comparison based on traversal behaviour and path cost.

## Algorithms and Complexity

| Algorithm | Purpose | Time Complexity |
|---|---|---|
| BFS | Unweighted shortest path | O(V + E) |
| DFS | Graph traversal | O(V + E) |
| Dijkstra | Weighted shortest path | O((V + E) log V)* |
| A* Search | Heuristic-based shortest path | Depends on heuristic and graph |
| Bellman-Ford | Shortest path with negative edges | O(VE) |
| Floyd-Warshall | All-pairs shortest paths | O(V³) |

*Dijkstra's complexity assumes an adjacency-list representation with a binary min-heap.*

## How It Works

1. The application initializes a graph containing nodes and weighted edges.
2. The user selects a pathfinding algorithm.
3. The selected algorithm explores the graph according to its traversal or shortest-path strategy.
4. Visited nodes and explored edges are visualized through animation.
5. The shortest path is highlighted after algorithm execution.
6. Users can modify edge weights or simulate road closures and recalculate routes.

## Getting Started

**1. Clone the repository**

```bash
git clone <repository-url>
cd <repository-folder>
```

**2. Run the application**

Open `index.html` in your web browser.

Alternatively, use the VS Code Live Server extension to run the application locally.

## Key Learning Outcomes

- Understanding graph representations and graph traversal techniques.
- Implementing fundamental graph algorithms.
- Working with priority queues and heuristic-based search.
- Comparing shortest-path algorithms and their computational complexity.
- Building interactive frontend applications using JavaScript.
- Visualizing algorithm execution through dynamic animations.

## Future Improvements

- Add support for customizable grid sizes and graph structures.
- Introduce additional pathfinding algorithms.
- Implement algorithm performance comparison using execution time and explored-node count.
- Improve responsive design for mobile devices.
- Add support for saving and loading custom graph configurations.

---

**Developed as a Data Structures & Algorithms and Frontend Development portfolio project.**
