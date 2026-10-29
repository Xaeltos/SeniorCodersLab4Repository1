# Strategy 4: Isolate (Sub-Agent Delegation)

## Configuration Decisions
This repository implements the **Isolate** strategy. Based on the lecture (Page 33), we solved "Context Confusion" by strictly limiting each agent's knowledge scope. 

We created two sub-agent profiles (`env-agent.md` and `rl-agent.md`). 
- The Environment Agent was given *only* grid rules.
- The RL Agent was given *only* math rules.

The Main Agent (Orchestrator) delegated the tasks, resulting in modular code with zero hallucination overlap.

## How to Run
Run `python main.py` to train the agent.