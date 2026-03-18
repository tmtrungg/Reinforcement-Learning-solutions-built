# Reinforcement Learning Solutions

Implementations of classic RL algorithms applied to OpenAI Gym environments. Each problem is solved with both a baseline (non-RL) approach and RL methods, with performance comparisons.

## Problems & Methods

| Environment | Baseline | RL Method | Notebook |
|------------|----------|-----------|----------|
| **Taxi-v3** | Random Policy | Q-Learning | [Taxi.ipynb](Taxi.ipynb) |
| **CartPole-v1** | Random Search | Q-Learning | [CartPole.ipynb](CartPole.ipynb) |
| **MountainCar-v0** | — | Q-Learning vs TD-Learning | [MountainCar.ipynb](MountainCar.ipynb) |

## What's Inside

Each notebook includes:
- Environment setup and exploration
- Baseline implementation for comparison
- RL agent training with hyperparameter tuning
- Reward curves and performance comparison
- Analysis of convergence behavior

## Tech Stack

- **Python** — NumPy, Matplotlib
- **OpenAI Gym** — simulation environments
- **Jupyter Notebook** — interactive experiments

## Presentation

- [Full walkthrough: RL concepts, problems, methods, and code](https://youtu.be/kruxPuKM-DE)