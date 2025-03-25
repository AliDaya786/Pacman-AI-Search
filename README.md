# Pacman-AI-Search

### Overview
This project is part of the UC Berkeley CS188 Artificial Intelligence course. The goal is to build intelligent agents for the Pacman environment using various search algorithms and AI techniques. The Pacman AI agent is designed to navigate through complex mazes, avoid ghosts, and collect food efficiently. The project includes:
 - Implementing search algorithms like DFS, BFS, UCS, and A*.
 - Developing smart ghost behavior using probability models.
 - Designing effective heuristics to improve Pacman’s decision-making.

### Key Features
 - Search Algorithms:
    - Depth-First Search (DFS) – Explores the deepest nodes first.
     - Breadth-First Search (BFS) – Explores the shallowest nodes first.
     - Uniform-Cost Search (UCS) – Explores nodes with the least path cost.
     - A* – Combines path cost and heuristic to find the shortest path efficiently.
 - Ghost Behavior:
    - RandomGhost – Moves randomly across the maze.
    - DirectionalGhost – Strategically chases or evades Pacman based on game state.
 - Heuristics:
   - Manhattan Distance – Measures the shortest path using grid-based distance.
   - Custom Heuristics – Designed to optimize Pacman’s movement for better pathfinding.

### Files Included
| **File**              | **Description**                                                                                     |
|----------------------|-----------------------------------------------------------------------------------------------------|
| `search.py`          | Implements DFS, BFS, UCS, and A* algorithms (**My code added under `*** YOUR CODE HERE ***`**)        |
| `searchAgents.py`    | Defines Pacman’s search-based agents and game strategies (**My code added under `*** YOUR CODE HERE ***`**) |
| `ghostAgents.py`     | Implements ghost behavior using AI models (**My code added under `*** YOUR CODE HERE ***`**)            |
| `util.py`            | Provides utility functions for data handling.                                                         |
| `game.py`            | Core game logic and state management.                                                                 |
| `pacman.py`          | Main file that runs the Pacman game environment.      


![Pacmangif](https://github.com/user-attachments/assets/58a4c95b-f88d-451e-9662-f59b971b9ed1)


