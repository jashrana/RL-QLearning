# RL QLearning
 Training an Agent in a 5x5 "Frozen Lake" grid world to reach the Win state while avoiding holes in the world using Q Learning

# University of Galway
## Assignment 2 (Agents, Multi-Agent Systems & Reinforcement Learning)
## Dr. Patrick Mannion

## 1. Aim
The “deterministic” FrozenLake is a toy problem from the so-called “grid world” category of problems. In this problem the agent
lives in a square grid and can move in 4 directions, “up”, “down”, “left” and “right”. The agent always starts in the top-left position and its
goal is to reach the bottom-right position on the grid while avoiding various holes placed in the grid.

## 2. Theory/Working:
The FrozenLake is a grid of 5x5 matrix where the agent must start at (0, 0) and navigate through to reach the Win State (4, 4) which
is the bottom right part of the grid. There are various holes [(1, 0), (1, 3), (3, 1), (4, 2)] present in the environment which the agent must try
to avoid. The agent in this puzzle can move in four directions—"up," "down," "left," and "right"—and lives in a grid of squares.

<p align="center">
<img src="3-components-q.jpg" alt="Q Learning Components" style="width:20%; border:0;">
</p>
<center>Fig 1. Components of Q-learning</center>
<center><i>Source: CT5130 CT5134 Reinforcement Learning Assignment 2 Document</center></i>

