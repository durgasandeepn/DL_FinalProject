**Deep Q-Network Vacuum Cleaner Agent (Deep Reinforcement Learning)**

Overview: Implemented a Deep Q-Learning Network (DQN) to train a vacuum cleaner agent to autonomously clean all dirty tiles in a grid environment using the shortest possible path, scaling from small fixed grids up to a 15×15 environment with 10 dirty tiles.

Key Components
Built a custom grid-world environment (vacuum starts at corner (0,0), moves N/S/E/W, must collect all dirty tiles) with Pygame visualization/simulation
Designed a DQN architecture (inspired by the Breakout DQN / Actor-Critic approaches covered in class) to learn optimal cleaning policies
Defined and iteratively tuned a custom reward function to guide efficient path-finding behavior
Trained the agent progressively on increasing grid sizes (starting with fixed small environments before scaling up)
Visualized reward vs. training epochs and steps-to-completion to track learning progress
Extended testing to random tile configurations and varying grid dimensions to evaluate generalization

Results: Agent successfully solves fixed 5×5, 10×10, and 15×15 grid environments, with performance visualized via Pygame.

Tech stack: Python, PyTorch, Pygame (custom RL environment + DQN)


[View the Project Assignment Question](Prg3_DeepReinforcementLearning.pdf)

[View the Project in Document format](Project3_DRL.pdf)


