# Adversarial Q-Learning for Dynamic Maze Navigation

**Advanced Reinforcement Learning Project – Training an agent in an evolving adversarial environment**

This project implements a **continual/adversarial reinforcement learning** system where a Q-Learning agent learns to navigate a maze, while an intelligent **Adversary Agent** dynamically increases the difficulty by strategically adding obstacles near the agent’s best-found path after each training epoch.

### 🚀 Try it Live
**Google Colab Demo:** [Open in Colab](https://colab.research.google.com/drive/1uRNlZ1Jb7WXtoSbSygD8086mtjKCH14t?usp=sharing)

### Key Features
- Custom `MazeEnv` with randomly generated solvable mazes
- Q-Learning agent with ε-greedy exploration and decaying ε
- Intelligent Adversary that analyzes the best path and adds obstacles nearby
- BFS-based solvability check to ensure the maze always remains solvable
- Real-time visualization of maze + agent path after each epoch

### Technologies
- Python 3
- NumPy, Matplotlib

### Results & Highlights
- Agent successfully learns to reach the goal in increasingly difficult mazes
- Adversary effectively forces the agent to re-learn and adapt
- Clear visualization of learning progress across multiple epochs
- Excellent demonstration of **adversarial reinforcement learning** concepts
