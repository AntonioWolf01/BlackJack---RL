# Link to the Colab Notebook
https://colab.research.google.com/drive/1fgSIaAV9LwTtG4pAz51cGxj3a6NtFSJQ?usp=sharing

# Blackjack Reinforcement Learning Agent

## Description

This project is a reinforcement learning model developed to teach an agent how to effectively play Blackjack using linear function approximation. The model incorporates both **Sarsa** and **Q-learning** algorithms to learn optimal strategies through experience. The environment used in this project is custom-built using the **Gym** package, with an added twist: an additional "peek" action that allows the agent to look at the next card in the deck, gaining valuable information. However, this action comes with a risk, as the agent can be penalized if caught peeking.

Key features include **reshuffling rules** that impact decision-making, as well as the use of **threshold feature transformation** and **polynomial feature transformation** techniques to enhance the learning process.

## Features & Highlights

- **Custom Gym Environment**: A Blackjack environment with a modified action space, including a "peek" action.
- **Reinforcement Learning Algorithms**:
  - **Sarsa**: A reinforcement learning algorithm that updates Q-values based on the agent's current state, action, reward, and next state-action pair.
  - **Q-learning**: An off-policy algorithm that updates Q-values based on the agent's current state and action, aiming for maximum future reward.
- **Feature Transformations**:
  - **Threshold Feature Transformation**: Helps to categorize certain features by thresholds to improve model performance.
  - **Polynomial Feature Transformation**: Expands features to a higher degree to capture more complex relationships in the state space.
- **Peek Action**: Allows the agent to peek at the next card, providing strategic information but with penalties if misused.
- **Reshuffling Mechanics**: Custom reshuffling rules that affect the learning process and strategy optimization.
- **Model Performance**: Evaluate the agent's performance in terms of total rewards and optimal strategy learning.
