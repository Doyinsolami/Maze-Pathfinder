# Maze Solver — BFS Pathfinding

A Python-based maze generator and pathfinder built with Pygame.

## Overview
Generates a random 21×21 maze using randomized depth-first search, 
selects random start and end points, and finds the shortest path 
using Breadth-First Search (BFS). The result is visualized in a 
Pygame window with color-coded cells.

## Features
- Random maze generation using DFS carving
- Shortest path finding with BFS
- Visual display using Pygame
  - 🟢 Green — Start
  - 🔴 Red — End  
  - 🟡 Gold — Shortest path
  - 🔵 Light blue — Visited cells not on path
- Press R to regenerate a new maze
- Press Q to quit

## Tech Stack
Python, Pygame

## Why BFS?
BFS guarantees the shortest path on an unweighted grid. 
For a 21×21 maze where every move costs one step, it is 
simple, fast, and reliable.

## How to Run
```bash
pip install pygame
python maze_lab.py
```
<img width="726" height="464" alt="image" src="https://github.com/user-attachments/assets/ffb167b7-3af7-411a-8c00-79596aef8f05" />
