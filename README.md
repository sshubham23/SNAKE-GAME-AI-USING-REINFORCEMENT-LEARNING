# Teach AI To Play Snake! Reinforcement Learning With PyTorch and Pygame

In this Python Reinforcement Learning Tutorial series we teach an AI to play Snake! We build everything from scratch using Pygame and PyTorch. The tutorial consists of 4 parts:

You can find all tutorials on my channel: [Playlist](https://www.youtube.com/playlist?list=PLqnslRFeH2UrDh7vUmJ60YrmWd64mTTKV)

- Part 1: I'll show you the project and teach you some basics about Reinforcement Learning and Deep Q Learning.
- Part 2: Learn how to setup the environment and implement the Snake game.
- Part 3: Implement the agent that controls the game.
- Part 4: Implement the neural network to predict the moves and train it.

# Overview
This project implements an artificial intelligence (AI) agent to play the classic Snake game using reinforcement learning techniques. The AI agent learns to navigate the game environment, avoid obstacles, and consume food to maximize its score.

# Features
**Snake Game Environment**: The project includes a Snake game environment where the AI agent operates. The game provides a grid-based arena where the snake must move to consume food without colliding with itself or the walls.

**Reinforcement Learning**: The AI agent employs Q-learning to learn optimal policies for playing the game. It utilizes a linear Q-network to approximate the Q-values, representing expected cumulative rewards for actions in different states.

**Epsilon-Greedy Exploration**: The agent balances exploration and exploitation using an epsilon-greedy policy during action selection. This strategy enables the agent to explore new actions while exploiting known actions with higher Q-values.

**Memory Replay**: Experience replay is utilized, storing past experiences in a memory buffer and randomly sampling mini-batches during training. This technique stabilizes and improves learning efficiency by reducing correlation between consecutive experiences.

**Training Visualization**: Visualizations for monitoring training progress, such as plotting game scores and mean scores over time, are provided. These visualizations offer insights into the agent's learning curve and performance improvements.

**Modular Design**: The codebase is modular, with separate modules for the game environment, AI agent, Q-network model, and training components. This structure enhances code readability, maintainability, and extensibility.

**Save/Load Model**: Trained Q-network models can be saved to disk and loaded for future use. This feature enables users to save progress, resume training, or deploy the model for playing the game.

**Easy-to-Use Interface**: The project includes clear documentation and straightforward setup instructions. Users can quickly set up and run the project on their local machines. The code is written in Python and utilizes popular libraries such as PyTorch for deep learning.

# Usage
**Installation**: Clone the repository to your local machine and install the required dependencies listed in requirements.txt.

**Training**: Run the train.py script to train the AI agent. Adjust hyperparameters and settings as needed.

**Evaluation**: Evaluate the trained model by running the evaluate.py script. You can adjust the evaluation settings to observe the agent's performance.

**Visualization**: Use the provided visualization tools to monitor the training progress and performance metrics.

**Customization**: Modify the code to experiment with different reinforcement learning algorithms, network architectures, and game environments.

# Requirements
Python 3.x
PyTorch
NumPy
Matplotlib
