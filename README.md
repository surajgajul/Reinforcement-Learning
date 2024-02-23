**For the Experimental CartPole(DQN):**

Implemented a DQN architecture using TensorFlow/Keras to approximate the Q-values for each action given a state.
Employed an epsilon-greedy policy for action selection, balancing between exploration and exploitation.
Utilized experience replay with a memory buffer to store and sample past experiences for efficient learning.
Implemented a target network to stabilize training by fixing target Q-values during updates.
Neural Network Architecture: Two hidden layers with 24 units each and ReLU activation, output layer with linear activation.
Adjusted learning rate, discount factor, epsilon decay, and other parameters for optimal performance.
Iterated over a fixed number of episodes, each consisting of multiple steps.
Interacted with the environment, collecting experiences and updating the DQN's weights accordingly.
Updated the target network periodically to enhance stability during training.
Successfully trained the DQN in the CartPole-v1 environment.
Evaluated the agent's performance over multiple episodes and reported the average total reward.

**Other Notebooks:**

Explored various algorithms like PPO and A2C in environments like Atari Breakout, Car Racing.
Used tensorboard for visualization of parameters over time.
Successfully trained for short time_steps (resource limitations), and evaluated the models.
