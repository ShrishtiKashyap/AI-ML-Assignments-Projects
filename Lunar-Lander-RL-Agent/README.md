# Lunar Lander RL Agent Training using PPO

## Overview

This project demonstrates how Reinforcement Learning can be used to train an autonomous agent to safely land a spacecraft in the Lunar Lander environment provided by Gymnasium. The agent is trained using the Proximal Policy Optimization (PPO) algorithm from Stable-Baselines3, enabling it to learn an optimal landing strategy through continuous interaction with the environment and a reward-based learning process.

The project covers the complete reinforcement learning workflow, including environment creation, agent training, model evaluation, testing, and saving the trained model for future use.

---

## Objectives

* Understand the fundamentals of Reinforcement Learning.
* Train an agent using the PPO algorithm.
* Learn how reward-based learning differs from supervised learning.
* Evaluate the performance of the trained agent.
* Save and reload the trained model for future inference.

---

## Technologies Used

* Python 3
* Gymnasium
* Stable-Baselines3
* NumPy
* Matplotlib
* Jupyter Notebook

---

## Algorithm Used

### Proximal Policy Optimization (PPO)

Proximal Policy Optimization (PPO) is a reinforcement learning algorithm that enables an agent to learn an optimal policy through trial-and-error interactions with its environment. It updates the policy in a stable and efficient manner, preventing large changes that could negatively affect learning. PPO is widely used because of its simplicity, reliability, and strong performance across a variety of reinforcement learning tasks.

---

## Workflow

1. Install the required Python libraries.
2. Create the Lunar Lander environment using Gymnasium.
3. Initialize the PPO agent.
4. Train the agent using multiple timesteps.
5. Save the trained model.
6. Load the saved model for testing.
7. Evaluate the trained agent using multiple episodes.
8. Test the agent's landing performance.

---

## Training Parameters

| Parameter          | Value     |
| ------------------ | --------- |
| Algorithm          | PPO       |
| Policy             | MlpPolicy |
| Learning Rate      | 0.0003    |
| Gamma              | 0.99      |
| Batch Size         | 64        |
| Training Timesteps | 100000    |

---

## Results

The PPO agent successfully learned to improve its landing strategy by maximizing cumulative rewards through continuous interaction with the environment. After training, the saved model can be loaded and evaluated over multiple episodes to measure its average reward and overall performance.

---

## Applications

* Autonomous spacecraft landing
* Robotics and autonomous navigation
* Drone control systems
* Autonomous vehicles
* Industrial automation
* Game AI
* Reinforcement Learning research

---

## Future Improvements

* Increase the number of training timesteps for improved performance.
* Compare PPO with other reinforcement learning algorithms such as DQN and A2C.
* Record gameplay videos for visualization.
* Perform hyperparameter tuning to optimize learning.
* Train the agent on more challenging reinforcement learning environments.

---

## Learning Outcomes

Through this project, I learned:

* The fundamentals of Reinforcement Learning.
* The difference between supervised learning and reinforcement learning.
* How PPO trains an agent using reward-based optimization.
* How to create and interact with Gymnasium environments.
* How to evaluate, save, and reload reinforcement learning models.
* The importance of balancing exploration and exploitation during training.

---

## Conclusion

This project successfully demonstrates the implementation of a Reinforcement Learning agent for the Lunar Lander environment using the PPO algorithm. The trained agent learns to perform safe landings through continuous interaction with the environment and reward-based learning. The project provides practical experience with modern reinforcement learning techniques and highlights their applications in autonomous decision-making and intelligent control systems.
