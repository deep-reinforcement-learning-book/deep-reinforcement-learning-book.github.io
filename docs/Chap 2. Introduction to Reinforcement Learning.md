---
layout: default
title: Chap 2. Introduction to Reinforcement Learning
nav_order: 3
lang: en
---

## Authors

- Zihan Ding* - Princeton University (zhding[at]mail.ustc.edu.cn)
- Yanhua Huang - Xiaohongshu Technology Co.
- Hang Yuan - Oxford University
- Hao Dong - Peking University 

## Abstract

In this chapter, we introduce the fundamentals of classical reinforcement learning and a general overview of deep reinforcement learning. We first start with the basic definitions and concepts of reinforcement learning, including the agent, environment, action and state, as well as the reward function. Then, we give out a classical reinforcement learning problem, the bandit problem, to provide the readers with a basic understanding of the underlying mechanism of traditional reinforcement learning. Then we introduce the Markov process, together with the Markov reward process and the Markov decision process. These notions are the cornerstones in formulating reinforcement learning tasks and how they can be solved. The combination of the Markov reward process and value function estimation produces the core results used in most reinforcement learning methods: the Bellman equations. The optimal value functions and optimal policy can be derived through solving the Bellman equations. Three main approaches for solving the Bellman equations are then introduced: dynamic programming, Monte-Carlo method, and temporal difference learning. We further introduce deep reinforcement learning for both policy and value function approximation in policy optimization. The contents in policy optimization are introduced in two main categories: value-based optimization and policy-based optimization. In value-based optimization, the gradient-based methods are introduced for leveraging deep neural networks, like Deep Q-Networks. In policy-based optimization, the deterministic policy gradient and stochastic policy gradient are introduced in detail with sufficient mathematical proofs. The combination of value-based and policy-based optimization produces the popular actor-critic structure, which leads to a large number of advanced deep reinforcement learning algorithms. This chapter will lay a foundation for the rest of the book, as well as providing the readers with a general overview of deep reinforcement learning. 

**Keywords**: reinforcement learning, multi-armed bandit, Markov process, Bellman equation, dynamic programming, Monte-Carlo method, temporal difference learning, value-based optimization, deterministic policy gradient, stochastic policy gradient

## Citation

To cite this book, please use this bibtex entry:

```
@incollection{deepRL-chapter2-2020,
 title={Introduction to Reinforcement Learning},
 chapter={2},
 author={Zihan Ding, Yanhua Huang, Hang Yuan, Hao Dong},
 editor={Hao Dong, Zihan Ding, Shanghang Zhang},
 booktitle={Deep Reinforcement Learning: Fundamentals, Research, and Applications},
 publisher={Springer Nature},
 pages={47-124},
 note={\url{http://www.deepreinforcementlearningbook.org}},
 year={2020}
}
```





If you find any typos or have suggestions for improving the book, do not hesitate to contact with the corresponding author (name with *).