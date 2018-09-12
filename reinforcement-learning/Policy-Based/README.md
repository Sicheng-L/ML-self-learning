#Policy-Based Reinforcement Learning

###1. Policy-Based
Reinforcement learning paradigm in which agents learn a policy.
###2. Policy
A function that takes an environment state and outputs a probability distribution over all possible actions that can be taken. We construe the probabilities as measuring the relative value of each action.
###3. Policy Gradient
One of the algorithms that we can use to learn a policy.
###4. Deep Policy Gradient
A variant of policy gradient in which we use a deep neural network as the policy function.
###5. Deep Policy Gradient Algorithm
1. Initialize the agent and environment
2. Initialize the policy network with random weights
3. Play game for an episode, storing transitions (s, a, r) for each timestep
4. Update the policy network's weights
5. Repeat 3 and 4 until network has learned a decent policy
###6. The Policy Network
For generating policies, the network must take current state as input and generate a probability distribution over the set of actions as output
###7. Architecture
* Input: the game state (and some other things)
* Output: a probability distribution over all possible actions