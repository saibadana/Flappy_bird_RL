🐦 Flappy Bird Reinforcement Learning using Deep Q-Network (DQN)
📌 Overview

This project implements an autonomous Flappy Bird agent using Deep Reinforcement Learning. The agent learns to play the game through trial and error using the Deep Q-Network (DQN) algorithm, without being explicitly programmed how to play.

The objective of the agent is to maximize its cumulative reward by learning the optimal action (flap or do nothing) based on the current game state.

🚀 Features
Deep Q-Network (DQN) based agent
Experience Replay for stable learning
Epsilon-Greedy Exploration Strategy
Neural Network for Q-value approximation
Model checkpoint saving
Autonomous gameplay after training
🛠️ Technologies Used
Python
PyTorch
Gymnasium
Flappy Bird Gymnasium Environment
NumPy
📂 Project Structure
FLAPPY-BIRD-RL/
│
├── Agent.py              # Main training script
├── model.py              # Deep Q-Network architecture
├── replay_memory.py      # Experience replay buffer
├── utils.py              # Helper functions
├── checkpoints/          # Saved model weights
├── requirements.txt      # Project dependencies
└── README.md             # Project documentation

Note: The file structure above is an example. Update it if your project contains different filenames or folders.

⚙️ Installation

Clone the repository:

git clone git@github.com:saibadana/Flappy_bird_RL.git

Move into the project directory:

cd Flappy_bird_RL

Install the required packages:

pip install -r requirements.txt
▶️ Training the Agent

Run:

python Agent.py

Training will continue until it is stopped manually or according to the stopping condition defined in the code.

🧠 How It Works
The agent observes the current game state.
The DQN predicts the Q-value for each possible action.
The agent selects an action using the epsilon-greedy strategy.
The environment returns the next state and reward.
The experience is stored in replay memory.
Mini-batches are sampled to train the neural network.
Over time, the agent learns an effective policy to survive longer and achieve higher scores.
📈 Reinforcement Learning Concepts Used
Agent
Environment
State
Action
Reward
Deep Q-Network (DQN)
Experience Replay
Target Network (if implemented)
Epsilon-Greedy Exploration
Neural Networks
🎯 Future Improvements
Double DQN
Dueling DQN
Prioritized Experience Replay
Training visualizations
Hyperparameter tuning
Performance comparison between different RL algorithms
📚 Learning Outcome

This project helped me understand the practical implementation of Reinforcement Learning, including experience replay, exploration vs. exploitation, neural network training, and how an agent learns optimal behavior through interaction with an environment.

👨‍💻 Author

Sai Kumar

Final Year B.Tech Student

Aspiring Data Scientist
