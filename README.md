# AI Snake Game Solver (Project #13)

The thirteenth project in my **AI/ML Learning Path**. This project explores **Pathfinding Algorithms** and **Autonomous Decision Making** by creating an agent that plays the classic Snake game perfectly.

## 📌 Overview
This project implements an AI agent that uses various graph-based algorithms to navigate a grid, collect food, and avoid collisions. It features a real-time visualization built with **Pygame**.

## 🛠️ Tech Stack
* **Language:** Python
* **GUI Framework:** Pygame
* **Algorithms:** * **Greedy Solver:** Uses BFS (Breadth-First Search) to find the shortest path to the food.
    * **Hamiltonian Solver:** Generates a Hamiltonian Cycle to ensure the snake visits every tile without ever trapping itself.

## 🧠 Algorithmic Strategies
1. **The Greedy Solver:** - Calculates the shortest path from the head to the food.
   - Fast and high-scoring initially, but prone to getting trapped (deadlocks) as the snake's length increases.
2. **The Hamiltonian Solver:**
   - Constructs a cycle that visits every node in the grid exactly once.
   - By following this cycle, the snake is mathematically guaranteed never to collide with its own tail, eventually filling the entire grid for a "Perfect Win."

## ⚙️ Features
- **Real-time Visualization:** Watch the AI make decisions frame-by-frame.
- **Speed Control:** Adjustable game speed to analyze pathfinding logic.
- **Stat Tracking:** Displays current length, score, and algorithm status.

## 🚀 Quick Start
1. **Install Pygame:**
   ```bash
   pip install pygame
2. **Run**
   ```bash
   python AI_SnakeGame.py
3. **Toggle Algorithms**
   ```bash
   conf.solver_name=hamilton or greedy

*Progress: Mastered pathfinding and grid-based AI logic.*
