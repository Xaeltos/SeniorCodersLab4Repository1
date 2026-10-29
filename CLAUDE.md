**This document contains critical information about working and interacting with this project. Always follow these guidelines precisely in every action you perform.**

This project aims to implement the Q-learning algorithm to a vacuum agent in a simple simulated environment. The agent's environment is a simple 2D grid, stored as a 2D list in Python. Each cell in the grid contains one of the following:
- "start": the agent's starting cell
- "X": an obstacle, the agent cannot move to this cell
- A number: the reward for moving to that cell

The agent's state includes the cell it is currently in, as well as whether its cell is dirty or clean.

The agent's available actions are:
- Suck, if the cell is dirty
- Move, if the cell is clean

The project follows the typical structure of an educational Python notebook exploring artificial intelligence concepts. Our task is to use the "Lab4 Solution" section to successfully implement the Q-learning algorithm for our vacuum agent. 

**Rules:**

1) Do not install or modify any Python packages.

2) Use PEP 8 style for all Python code written.

3) Explicitly prompt the user to confirm any git operations, especially `commit` and `push`.

4) Write simple, straightforward code that is easy to maintain and understand

5) Don't hide confusion - communicate when you need clarification and if there are tradeoffs, state them

6) Edit only what is necessary and clean up only your own messes