---
layout: default
title: Chap 5. Policy Gradient
nav_order: 5
---

## Authors

- Ruitong Huang - Borealis AI
- Tianyang Yu - Nanchang University
- Zihan Ding - Princeton University
- Shanghang Zhang* - University of California, Berkeley (shzhang.pku[at]gmail.com)

## Abstract

Policy gradient methods are a type of reinforcement learning techniques that rely upon optimizing parameterized policies with respect to the expected return (long-term cumulative reward) by gradient descent. They do not suffer from many of the problems that have been traditional reinforcement learning approaches such as the lack of guarantees of an accurate value function, the intractability problem resulting from the uncertain state information, and the complexity arising from continuous states and actions. In this chapter, we will introduce a list of popular policy gradient methods. Starting with the basic policy gradient method REINFORCE, we then introduce the actor-critic method, the distributed versions of actor-critic, and trust region policy optimization and its approximate versions, each one improving its precedent. All the methods introduced in this chapter will be accompanied with its pseudo-code and, at the end of this chapter, a concrete implementation example.

**Keywords**: policy optimization, policy gradient, actor-critic, trust region policy optimization, proximal policy optimization

## Content
[中文版PDF](/assets/pdfs/ch5.pdf){: .btn .btn-purple  .fs-3 .mb-4 .mb-md-0 .mr-2 }

## Code 

Codes for contents in this chapter are available [**here**](https://github.com/tensorlayer/tensorlayer/tree/master/examples/reinforcement\_learning).

## Citation

To cite this book, please use this bibtex entry:

```
@incollection{deepRL-chapter5-2020,
 title={Policy Gradient},
 chapter={5},
 author={Ruitong Huang, Tianyang Yu, Zihan Ding, Shanghang Zhang},
 editor={Hao Dong, Zihan Ding, Shanghang Zhang},
 booktitle={Deep Reinforcement Learning: Fundamentals, Research, and Applications},
 publisher={Springer Nature},
 pages={161-212},
 note={\url{http://www.deepreinforcementlearningbook.org}},
 year={2020}
}
```





If you find any typos or have suggestions for improving the book, do not hesitate to contact with the corresponding author (name with *).