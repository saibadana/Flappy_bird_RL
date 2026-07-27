# 🐦 Flappy Bird AI using Deep Q-Network (DQN)

An autonomous Reinforcement Learning agent that learns to play Flappy Bird using the **Deep Q-Network (DQN)** algorithm. Instead of following predefined rules, the agent learns an optimal policy through trial-and-error interactions with the game environment to maximize long-term rewards.

---

## 📌 Project Overview

Flappy Bird is a challenging game where the player must navigate a bird through gaps between pipes without colliding.

In this project, a Deep Reinforcement Learning agent is trained to solve the game by interacting with the environment, collecting rewards, and continuously improving its decision-making ability using a Deep Q-Network (DQN).

The project demonstrates the practical implementation of value-based Reinforcement Learning using PyTorch.

---

## 🎯 Objectives

- Train an autonomous Flappy Bird agent using Deep Q-Learning.
- Learn an optimal policy through interaction with the environment.
- Stabilize learning using Experience Replay.
- Balance exploration and exploitation using an Epsilon-Greedy strategy.
- Save trained model checkpoints for future gameplay.

---

## 🚀 Key Features

- ✅ Deep Q-Network (DQN) implementation
- ✅ Experience Replay Buffer
- ✅ Epsilon-Greedy Exploration
- ✅ Neural Network-based Q-value approximation
- ✅ Model checkpoint saving
- ✅ Autonomous gameplay after training
- ✅ PyTorch implementation
- ✅ Trained for **5000+ episodes**

---

## 🛠️ Tech Stack

- Python
- PyTorch
- Gymnasium
- Flappy Bird Gymnasium Environment
- NumPy

---

## 📂 Project Structure

```
Flappy_bird_RL/
│
├── agent.py                 # Training loop
├── dqn.py                   # Deep Q-Network model
├── experience_replay.py     # Replay buffer
├── checkpoints/             # Saved model weights
├── requirements.txt
├── README.md
└── assets/
```

> **Note:** Update the file names above if your repository structure differs.

---

## ⚙️ Installation

### Clone the Repository

```bash
git clone https://github.com/saibadana/Flappy_bird_RL.git
```

### Navigate to the Project

```bash
cd Flappy_bird_RL
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Train the Agent

Run the training script:

```bash
python agent.py
```

The agent will begin learning by interacting with the game environment and periodically save model checkpoints.

---

## 🧠 How the DQN Agent Learns

1. Observe the current game state.
2. Predict Q-values using the Deep Q-Network.
3. Select an action using the Epsilon-Greedy policy.
4. Execute the action in the environment.
5. Receive the reward and next state.
6. Store the experience in Replay Memory.
7. Sample mini-batches from replay memory.
8. Update the neural network using gradient descent.
9. Repeat the process for **5000+ training episodes**.

---

## 📈 Reinforcement Learning Concepts

- Deep Q-Network (DQN)
- Markov Decision Process (MDP)
- Agent & Environment
- State Representation
- Action Space
- Reward Function
- Experience Replay
- Q-Learning
- Neural Networks
- Epsilon-Greedy Exploration

---

## 📊 Training Workflow

```
Game Environment
        │
        ▼
Observe State
        │
        ▼
Deep Q-Network
        │
        ▼
Choose Action
        │
        ▼
Receive Reward
        │
        ▼
Store Experience
        │
        ▼
Replay Memory
        │
        ▼
Update Neural Network
        │
        ▼
Improved Policy
```

---

## 🎯 Future Improvements

- Double DQN
- Dueling DQN
- Prioritized Experience Replay
- Hyperparameter Optimization
- TensorBoard Training Visualization
- Performance comparison with PPO and A2C
- Model deployment for interactive gameplay

---

## 📚 Learning Outcomes

This project strengthened my understanding of:

- Deep Reinforcement Learning
- Deep Q-Network (DQN)
- Exploration vs. Exploitation
- Experience Replay
- Neural Network training with PyTorch
- Reward optimization
- Sequential decision-making
- Reinforcement Learning workflows

---

## 👨‍💻 Author

**Sai Kumar**

🎓 Final Year B.Tech (Computer Science & Engineering)

🔗 GitHub: https://github.com/saibadana

🔗 LinkedIn: https://www.linkedin.com/in/sai-badana-a52472339/

---

## ⭐ Support

If you found this project useful, consider giving the repository a ⭐ on GitHub.
