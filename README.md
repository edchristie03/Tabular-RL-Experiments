## Tabular RL Experiments

# Maze Environment and Reinforcement Learning Agents

This repository contains a set of Python classes and functions for creating, visualizing, and solving a Maze environment using different reinforcement learning approaches. The code includes:

- **GraphicsMaze**: A class for visualizing the maze topology, states, rewards, and policies.
- **Maze**: A class defining the maze environment, including obstacles, absorbing states, and transitions.
- **DP_agent**: A Dynamic Programming (DP) agent that solves the maze using value iteration.
- **MC_agent**: A Monte Carlo (MC) learning agent for solving the maze environment.
- **TD_agent**: A Temporal-Difference (TD) learning (Q-learning) agent for maze solving.
- Plotting functions to visualize agent performance over multiple episodes.

## Features

- **Graphical Visualization**  
  Render the maze, state values, and policies (deterministic and probabilistic) using Matplotlib.

- **Multiple RL Approaches**  
  Compare how different learning algorithms—Dynamic Programming, Monte Carlo, and Temporal Difference—solve the maze environment.

- **Customizable Maze Environment**  
  The maze is configured with obstacles, rewards, absorbing states, and a set of starting locations.  
  Transition and reward matrices are built automatically based on the environment setup.

- **Performance Plotting**  
  Plot and compare the evolution of total rewards over multiple episodes for both MC and TD agents.

## Requirements

Ensure you have Python 3.x installed along with the following libraries:

- numpy
- pandas
- matplotlib



pip install requirements.txt

