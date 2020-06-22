---
layout: default
title: Chap 14. Robust Image Enhancement
nav_order: 15
---

## Authors

- Yanhua Huang* - Xiaohongshu Technology Co. (iofficium[at]gmail.com)

## Abstract

Deep generative models  such as GAN and Unet have achieved significant progress over classic methods in several computer vision tasks like super-resolution and segmentation. However, such learning-based methods lack robustness and interpretability, which limits their applications in real-world situations. In this chapter, we discuss a robust way for image enhancement that can combine numbers of interpretable techniques through deep reinforcement learning. We first present some background about image enhancement. Then we formulate the image enhancement as a pipeline modeled by MDP. Finally, we show how to implement an agent on this MDP with PPO algorithm. The experimental environment is constructed by a real-world dataset that contains 5000 photographs with both the raw images and adjusted versions by experts.

**Keywords**: image processing, image enhancement, robust learning

## Code 

Codes for contents in this chapter are available [**here**](https://github.com/deep-reinforcement-learning-book/Chapter14-Robust-Image-Enhancement).

## Citation

To cite this book, please use this bibtex entry:

```
@incollection{deepRL-chapter14-2020,
 title={Robust Image Enhancement},
 chapter={14},
 author={Yanhua Huang},
 editor={Hao Dong, Zihan Ding, Shanghang Zhang},
 booktitle={Deep Reinforcement Learning: Fundamentals, Research, and Applications},
 publisher={Springer Nature},
 pages={379-390},
 note={\url{http://www.deepreinforcementlearningbook.org}},
 year={2020}
}
```



If you find any typos or have suggestions for improving the book, do not hesitate to contact with the corresponding author (name with *).