# Maze Pathfinding Visualization (Python + Curses)

A terminal-based maze solver and visualizer that demonstrates Breadth-First Search (BFS) pathfinding using Python's `curses` library.

## How It Works

- The maze is represented as a 2D grid, with walls (`#`), open spaces (` `), a start point (`O`), and an end point (`X`).
- The algorithm uses BFS to explore the maze, searching for the shortest path from `O` to `X`.
- As the pathfinding progresses, the current path is visualized in real-time:
    - Maze walls and cells are drawn in blue.
    - The current explored path is highlighted in red.
- When the target (`X`) is found, the path that led to it is displayed.

## How to Run

1. Ensure you have Python 3 installed on your machine.
2. On Windows, install the `windows-curses` package: pip install windows-curses
3. Save the code as `maze_solver.py` in your project folder.
4. Open your terminal/command prompt in the project folder.
5. Run: python project.py
6. Watch the visualization in the terminal as the algorithm explores and solves the maze.
 
## What I Learned and Used

- Implementing the Breadth-First Search (BFS) algorithm to find the shortest path in a grid maze.
- Using Python's `curses` library for colored, animated real-time visualization in the terminal.
- Manipulating 2D arrays to represent and traverse grid-based mazes.
- Queue-based state management and visited node tracking to avoid redundant exploration.
- Handling color pairs for visual feedback and understanding pathfinding steps.

## Skills Used

Python, BFS Algorithm, Queue Data Structures, Curses Library, Terminal Graphics, Visualization, Algorithmic Problem Solving
