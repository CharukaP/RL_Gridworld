# RL Gridworld
In this section we take 5 x 5 grid world with specific characteristics to compare different reinforcement learning methodologies. Property of grid world environment as below.  Agent in environment can take a step up, down, left or right actions. However, If the agent attempts to step off the grid, the location of the agent remains unchanged with reward of −0.5.

The blue, green, red and yellow squares represent special states. At the blue square, any action yields a reward of 5 and causes the agent to jump to the red square. At the green square, any action yields a reward of 2.5 and causes the agent to jump to either the yellow square or the red square with probability 0.5. Taking any action in white, red and yellow squares will not yield any reward unless it is not trying to step off the grid.

For location identifying purpose each state is numbered as below figure in most of the cases unless different requirement arises.

![image](https://github.com/user-attachments/assets/c7964d09-6fae-4320-91d8-d930f0149e47)

