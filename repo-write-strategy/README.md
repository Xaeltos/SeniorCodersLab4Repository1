# Strategy 1: Write (Persistent Memory Architecture)

## Configuration Decisions
This repository implements the **Write** strategy from the Context Engineering framework. Instead of using a massive one-time prompt, we created a `.claude/CLAUDE.md` file. This file acts as a persistent, hierarchical memory system. 

The AI agent automatically loads this memory to understand the coding standards, grid constraints, and RL math required. This avoids "Context Poisoning" and ensures the agent always follows the project rules across multiple turns.

## How to Run
Run `python main.py` to train the agent.