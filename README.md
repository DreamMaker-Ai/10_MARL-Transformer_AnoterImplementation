# 10_MARL-Transformer_AnoterImplementation

Abstract
This article is a follow-up to the previous articles “ Preliminary Implementation of MARL-Transformers for Generating Battlefield Strategy “ [2]-[5]

The transformer used in natural language processing is applied to multi-agent reinforcement learning (MARL).

In previous articles, I mentioned that there are two ways to represent the agent set.

The first method is to represent the agent set like natural language processing, and this method was implemented in the previous articles.

The second method is to implement the communication network structure among multiple agents more directly as an attention mask, which is the implementation in this article. In this method, the attention matrix is an adjacency matrix, and the entire neural network architecture is nothing but a graph attention network.

Experiments are conducted in the same environment used in the previous implementations, red army versus blue army battlefield [4]. Each agent is a platoon or a company composed of unmanned systems. The goal of reinforcement learning is to learn the optimal red army strategy.

Experimental results confirm that the performance of this implementation is comparable to the previous implementation.


https://medium.com/@tym406/preliminary-implementation-of-marl-transformers-follow-up-1-ea0e02a3a9d9
