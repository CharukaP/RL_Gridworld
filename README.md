# RL Gridworld
In this section we take 5 x 5 grid world with specific characteristics to compare different reinforcement learning methodologies. Property of grid world environment as below.  Agent in environment can take a step up, down, left or right actions. However, If the agent attempts to step off the grid, the location of the agent remains unchanged with reward of −0.5.

The blue, green, red and yellow squares represent special states. At the blue square, any action yields a reward of 5 and causes the agent to jump to the red square. At the green square, any action yields a reward of 2.5 and causes the agent to jump to either the yellow square or the red square with probability 0.5. Taking any action in white, red and yellow squares will not yield any reward unless it is not trying to step off the grid.

For location identifying purpose each state is numbered as below figure in most of the cases unless different requirement arises.

![image](https://github.com/user-attachments/assets/c7964d09-6fae-4320-91d8-d930f0149e47)

The objective of the excercise can be identify by refering the rl-a2.pdf

The total excer sise devided in to two parts. Each individual segments and its recreation files can be summerise as below

Part 1 - Question 1
  Evaluate policy in three different methodologies
    1. Solving Belman equation explicitly
    2. Iterative policy evaluation
    3. Value iteration
  Results can be recreated by running A2P1Q1.ipynb file

Part 1 - Question 2
  Find the optimum policy by three different methods
    1. Explicitly solving Bellman optimality equation
    2. Policy iteration
    3. Policy improvement with value iteration
  Results can be recreated by running A2P1Q2.ipynb and A2P1Q2_part1_optional.ipynb file (additional methodology used to find optimal policy in 1 sub section)

Part 2 - Question 1
  Evaluate optimal policy using different Monte Carlo algorithms
    1. MC with exploring starts
    2. Without exploring starts but epsilon-soft approach
  Results can be recreated by running A2P2Q1.ipynb file

Part 2 - Question 2
  Evaluate optimal policy using off-policy
  Results can be recreated by running A2P2Q2.ipynb file

Part 2 - Question 3
  Evaluation of dynamic gridworld
  Results can be recreated by running A2P2Q3.ipynb file

Summary of the work and results is explained in the Reinforcement_Learning_Gridworld.pdf file
