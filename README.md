
ABSTRACT:

Reinforcement learning (RL) algorithms enable agents to learn how to act in different environments. The SARSA and Q-learning algorithms are two popular RL algorithms, each with unique features. In this paper, we evaluate and compare the performance of SARSA and Q-learning algorithms on two gymnasium environments, namely CliffWalker-v0 and Blackjack-v1, based on convergence rate and reward received. We also investigate the impact of different Epsilon values on the performance of the two algorithms. Our results show that SARSA and Q-learning algorithms both learn the optimal policy for the CliffWalker-v0 environment. However, SARSA outperforms Q-learning in terms of efficiency, requiring fewer steps to reach convergence and less time to learn the optimal policy.

INTRODUCTION:

Reinforcement learning (RL) techniques enable agents to learn how to act in different environments by trial and error. The agent is rewarded or penalized based on its interaction with the environment, and the objective is to learn a policy that maximizes the overall reward. SARSA and Q-learning are two well-known RL algorithms, each with different characteristics. SARSA modifies its policy after every action, whereas Q-learning modifies its policy based on the predicted rewards of all possible actions, not just the chosen action.
In this study, we compare the performance of SARSA and Q-learning algorithms on two gymnasium environments. The CliffWalker-v0 environment requires the agent to move from the starting point to the goal in a 12x4 grid world without falling off the cliff, earning a reward of -1 for each step taken and a penalty of -100 for falling off the cliff. The Blackjack-v1 environment requires the agent to obtain cards that sum closer to 21 than the dealer’s cards without going over 21.

CONCLUSION:

Notebook results show that SARSA outperforms Q learning on CliffWalker-v0. In BlackJack-v1, we see that This suggests that SARSA is a more effective RL algorithm than Q learning for some environments.
