# Project Context: Q-Learning Vacuum Robot

## Architecture Overview
This is a Python reinforcement learning project. 
- `vacuum_env.py` must contain the `VacuumEnvironment` class.
- `q_learning_agent.py` must contain the `QLearningAgent` class.
- `main.py` must run the training loop and test the agent.

## Environment Rules
- The grid is a 4x4 2D array: `[["start", 0, 0, 0], [0, "X", 0, 0], [0, 0, 0, 0], [0, -1, 0, 10]]`
- The environment must parse this array to find the `start`, `10` (goal), `-1` (trap), and `"X"` (obstacle).
- Stochastic movement: 80% intended direction, 10% slip left, 10% slip right. Bounce back if hitting a wall or "X".
- Living cost is -0.1 per step. Reaching goal is +10 (terminal). Hitting trap is -1 (terminal).

## Coding Standards
- Use explicit return types (Python type hints).
- Always use descriptive variable names (e.g., `next_state`, not `ns`).
- Implement Epsilon decay in the Q-Learning agent.