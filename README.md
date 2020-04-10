# Graph Networks in Deep Reinforcement Learning

This repository contains two works done at the MVA master (2019) for the course 'Graphs in Machine Learning' taught by Michal Valko.

The first one is an analysis of the research article: Neural Relational Inference for Interacting Systems by Kipf et al., 2018, and the second one is the final project validating this course. These two works offers a broad overview of what can be done with GNs (Graph Networks) nowadays. In particular, my research project ends up on the combination of graphs and reinforcement learning. As this was a review work, no code has been written. See below the global instructions of the final research project:

Topic:  graph neural networks, reinforcement learning, combinatorial generalization
Category: review
Contact: Omar Darwiche Domingues, omar.darwiche-domingues@inria.fr
Assigned to:  Thibault Lahire,  thibault.lahire@student.isae-supaero.fr
Description:

Real-world objects and their interactions at each time t can be modeled as a graph, which can be used to infer the states of the objects at time t+1 [1]. Learning this kind of graph might be useful for combinatorial generalization [6], i.e., being able to model the dynamics of any number objects by generalizing the knowledge about pairwise interactions.
For instance, we can think of two objects connected by a spring: at a time t, each object represents a node in a graph and the spring represents an edge. To each node, we associate a state (e.g., position and velocity) and the edge describes the interaction between the objects (e.g. the spring constant). Then, we might try to learn a function (such as a neural net) that predicts future states by mapping the graph at time t to the graph at t+1. This approach has been studied in [2] to learn physical models, use them to predict trajectories and also to train model-based reinforcement learning agents.
In [3],  graph networks were also used to train model-free RL agents (by learning a Q function with a graph net) in order to use the relations between the objects that compose the environment to improve learning.
The goal of this project is to understand how graph networks work and review how these networks have been used in reinforcement learning.

[1] Battaglia, P. et al. 'Interaction Networks for Learning about Objects,
Relations and Physics' (https://arxiv.org/abs/1612.00222)
[2] Sanchez-Gonzalez, A. et al. 'Graph networks as learnable physics engines for inference and control' (https://arxiv.org/pdf/1806.01242.pdf)
[3]  B. Hamrick, J. et al. 'Relational inductive bias for physical construction in humans and machines' (https://arxiv.org/abs/1806.01203)
[4] https://gym.openai.com/envs/#classic_control
[5] Scarselli, F., Gori, M., Tsoi, A., Hagenbuchner, M. & Monfardini, G. 2009, 'The graph neural network model', IEEE Transactions on Neural Networks, vol. 20, no. 1, pp. 61-80 (http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.1015.7227&rep=rep1&type=pdf).
[6] Battaglia, P. et al. 'Relational inductive biases, deep learning, and graph networks' (https://arxiv.org/pdf/1806.01261.pdf)
