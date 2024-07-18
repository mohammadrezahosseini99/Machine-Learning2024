# Mini Project 4: Reinforcement Learning and Algorithms

This mini project is part of the Machine Learning 2024 course by Dr. Mehdi Aliyari at Khajeh Nasir Toosi University of Technology (KNTU). The project explores and implements two significant reinforcement learning algorithms: Q-learning and Deep Q-Networks (DQN). The goal is to solve the Wumpus World problem and apply Deep Q-Learning to the Lunar Lander environment.

## Project Synopsis

### Task 1: Solving the Wumpus World

The Wumpus World is a grid-based environment where an agent must navigate to find gold while avoiding deadly pits and a dangerous Wumpus. This environment is a classic AI challenge, providing a rich context for testing reinforcement learning algorithms due to its combination of rewards and risks.

#### Objectives:
1. **Navigate the Grid**: Teach the agent to move effectively within the grid.
2. **Avoid Hazards**: Ensure the agent avoids pits and the Wumpus.
3. **Collect Gold**: Guide the agent to find and collect the gold.
4. **Kill the Wumpus**: Equip the agent to shoot arrows to eliminate the Wumpus.

#### Algorithms Implemented:
1. **Q-learning**: A model-free reinforcement learning algorithm that uses a Q-table to store and update the value of state-action pairs. It learns the optimal policy through exploration and exploitation.
2. **Deep Q-Networks (DQN)**: Extends Q-learning by using neural networks to approximate Q-values, enabling the algorithm to handle larger state spaces. DQN stabilizes training with experience replay and a target network.

#### Performance Evaluation:
- **Total Rewards**: Cumulative reward obtained by the agent during training episodes.
- **Cumulative Rewards**: Sum of rewards over time to analyze learning progress.
- **Mean Rewards per Episode**: Average reward per episode to evaluate consistency.

#### Key Findings:
- **Policy Performance**: Evaluating the agent's policy performance through learning curves.
- **Epsilon Impact**: Assessing the effect of different epsilon values (exploration rate) on the learning process.
- **Comparison**: Comparing Q-learning and DQN in terms of speed and efficiency in learning the optimal policy.

### Task 2: Deep Q-Learning for Lunar Lander

In this task, we design and train an agent using Deep Q-Learning to solve the Lunar Lander environment. The Lunar Lander is a simulated environment where an agent must land a spacecraft safely on a lunar surface.

#### Objectives:
1. **Design an Agent**: Implement an agent using Deep Q-Learning to learn the optimal policy for landing.
2. **Train the Agent**: Train the agent with various hyperparameters and evaluate its performance.

#### Features of Lunar Lander Environment:
- **State Space**: Continuous state space describing the lander's position, velocity, angle, and angular velocity.
- **Action Space**: Actions include firing the main engine or side engines.
- **Reward System**: Rewards based on proximity to the landing pad and penalties for crashing.

#### Performance Evaluation:
- **Batch Sizes**: Evaluate agent performance with different batch sizes (32, 64, 128) and episodes (50, 100, 150, 200, 250).
- **Learning Curves**: Analyze learning curves to understand the agent's learning process.
- **Model Comparison**: Compare DQN and DDQN (Double DQN) models' performance.

#### Key Findings:
- **Optimal Policy**: Determine the best performing model and hyperparameters based on reward convergence.
- **Regret Analysis**: Analyze and visualize the regret to understand the agent's decision-making over time.

## About Me

I am a student at K. N. Toosi University of Technology, specializing in Digital Electronics. This repository showcases my work on implementing and evaluating reinforcement learning models, focusing on the Wumpus World and Lunar Lander environments. Through this project, I have gained experience in designing agents, training models, and analyzing performance using Python.