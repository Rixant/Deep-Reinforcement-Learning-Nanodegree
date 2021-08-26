# Deep-Reinforcement-Learning-Nanodegree

[image1]: https://user-images.githubusercontent.com/10624937/42135619-d90f2f28-7d12-11e8-8823-82b970a54d7e.gif "Trained Agent" 
[image2]: https://user-images.githubusercontent.com/10624937/43851024-320ba930-9aff-11e8-8493-ee547c6af349.gif "Trained Agent" 
[image3]: https://user-images.githubusercontent.com/10624937/42135623-e770e354-7d12-11e8-998d-29fc74429ca2.gif "Trained Agent" 


## Projects 
1. [Deep-Q Navigation](https://github.com/Rixant/Deep-Reinforcement-Learning-Nanodegree/tree/main/Project%201%20-%20Navigation)\
<img src="https://user-images.githubusercontent.com/10624937/42135619-d90f2f28-7d12-11e8-8823-82b970a54d7e.gif" width="350" height="200">\
The environment consists of yellow bananas and blue bananas lying on the floor. A reward of +1 is awarded for collecting every yellow banana and -1 for collecting blue bananas. The goal of bananas is to collect as many as yellow bananas by neglecting blue bananas.\
The agent has 37 state spaces and four discrete actions.
    - 0 - move forward.
    - 1 - move backward.
    - 2 - turn left.
    - 3 - turn right.\
The task is episodic, and in order to solve the environment, your agent must get an average score of +13 over 100 consecutive episodes.


2. [Continous Contol](https://github.com/Rixant/Deep-Reinforcement-Learning-Nanodegree/tree/main/Project%202%20-%20Continous%20Control)\
<img src="https://user-images.githubusercontent.com/10624937/43851024-320ba930-9aff-11e8-8493-ee547c6af349.gif" width="350" height="200">\
The environment consists of a double-jointed arm can move to target locations. A reward of +0.1 is awarded for each step that the agent's hand is in the goal location. The goal of the agent is to maintain its position at the target location for as many time steps as possible. 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.
The environment is considered solved, when the average (over 100 episodes) of those average scores is at least +30. 


3. [Multi-Agent Tennis Player](https://github.com/Rixant/Deep-Reinforcement-Learning-Nanodegree/tree/main/Project%203%20-%20MultiAgent%20Tennis)\
<img src="https://user-images.githubusercontent.com/10624937/42135623-e770e354-7d12-11e8-998d-29fc74429ca2.gif" width="350" height="200">\
The environment consists of two agents controlling rackets to bounce a ball over a net. A reward of +0.1 is awarded for every ball the agent hits over the net and the reward of -0.01 if an agent lets a ball hit the ground or hits the ball out of bounds. The goal of each agent is to keep the ball in play. 8 variables corresponding to the position and velocity of the ball and racket. Each agent receives its own, local observation. Two continuous actions are available, corresponding to movement toward (or away from) the net, and jumping.\
The task is episodic, and in order to solve the environment, your agents must get an average score of +0.5 (over 100 consecutive episodes, after taking the maximum over both agents). Specifically,
    - After each episode, we add up the rewards that each agent received (without discounting), to get a score for each agent. This yields 2 (potentially different) scores. We then take the maximum of these 2 scores.
    - This yields a single score for each episode.\
 The environment is considered solved, when the average (over 100 episodes) of those scores is at least +0.5.
