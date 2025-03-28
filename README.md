# CoinRun Deep Reinforcement Learning Video Game Agent
This deep reinforcement learning agent is designed to beat a simple platforming game
called CoinRun. The main goal of the agent is to collect a coin without dying from a monster 
or running out of time.

### Reinforcement Learning
Typical reinforcement learning, in essence, is done by learning a policy (action to take) in a given state
by optimizing the amount of utility/reward it can receive in that state. For video games, the amount of 
possible states is extremely large, making it very inefficient to learn this policy funtion directly.

Instead, this agent implements reinforcement learning by using the pixels in the current frame as the 
state and predicting the action (or policy) by using those pixels as inputs to a neural network. This 
eliminates the need to learn the policy directly and allows the agent to update it's policy through
the loss function and back propogation.
