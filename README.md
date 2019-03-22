# msne-rl-finance

The target problem is the classic smoov & curly's bogus journey. An illustration example could be found in the following link
https://www.youtube.com/playlist?list=PLw0qyFP7t4IYuI9XcDIGsARfO1QKMrpbN

The exercise implements the following algorithms to solve the problem as a Markov Decision Process and Reinforcement Learning respectively.

0. Introduction

0.1 Markov Chain class

0.2 Markov Reward Process class


1. Markov Decision Process

1.1 MDP class

1.2 Policy iteration

1.3 value iteration


2. Reinforcement Learning

The following RL algorithms build on the MDP we developed in the previous section. We use the MDP to generate episodes of observations, but avoid using any transition/expected reward. Then we implement the following model-free algorithm to solve the optimal value functions / policy.

2.1 Model-free prediction

2.1.1 Monte Carlo learning

2.1.2 TD(0) learning

2.2 Model-free control

2.2.1 Sarsa(0)

2.2.2 Q-learning

2.3 Value function approximation

2.3.1 Sarsa(0)

2.3.2 Q-learning

2.4 Policy Gradient

2.4.1 REINFORCE algorithm
