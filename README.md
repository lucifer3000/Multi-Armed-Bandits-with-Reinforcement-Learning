# Multi-Armed-Bandits-with-Reinforcement-Learning

Multi-Armed Bandits creates the Bandits environment and explores various algorithms such as Greedy Algorithm, the Epsilon-Greedy Algorithm, Time-Varying Epsilon-Greedy Algorithm, Successive Elimination Algorithm, The Upper-Confidence-Bound (UCB) Algorithm, and Thompson Sampling (TS) for optimal rewards.

A GIF is also plotted for each of the algorithms to test how well the agent is performing compared to the real values provided by the environment. The agent doesn't have access to that information. Plots for average reward and average optimality ratio are plotted with respect to the number of steps for better clarity of the algorithms.

Regret plots for each of the above algorithms are plotted with a deep-dive into the Hoeffding Inequality which has been used to prove the regrets.

## Model-Based Learning
Model-Based Learning includes methods like Policy Iteration and Value Iteration algorithms for which a model of the environment has been given. These algorithms have been implemented from scratch.

## Model-Free Learning
Model-Free Learning includes methods like SARSA and Q-Learning algorithms for which a model of the environment is not available. These algorithms have been implemented from scratch.

