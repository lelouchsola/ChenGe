---
layout: archive
title: "Research topics"
permalink: /research/index.html
author_profile: true
---



## 1. Neural piecewise linearization for hard constraints (Constraint learning)
- Train a neural network (NN) that maps decisions to constraint violations (e.g., bus voltage or branch flow violation)
- Equivalently reformulate the trained NN into mixed-integer linear constraints to replicate original hard constraints (e.g., power flow constraints)
- Can be interpreted as a piecewise linearization method
- [[1](https://ieeexplore.ieee.org/abstract/document/9502573)] for replicating deterministic constraints, [[2](https://ieeexplore.ieee.org/abstract/document/9956906)] for replicating probabilistic constraints, and [[3](https://ieeexplore.ieee.org/abstract/document/10058008)] for its piecewise linearization-based intepretation  
![Editing](/research_images/constraint_learning.png){:height="400px" width="800px"} 

## 2. Self-supervised learning proxy for ecomonic dispatch
- Train a predictive model to predict optimal dispatch decisions
- Propose a decision loss that can overcome the optimality and feasibility issue caused by the common used mean square error
- No need for any training label (e.g., historical optimal dispatch decision)
- References: Comming soon!

## 3. Power system operations under uncertainty
- A fast distributionally robust chance-constrained method that can quantify the impact of the uncertainty offline [[4](https://ieeexplore.ieee.org/abstract/document/9417102)]
- A SVM-based approximation for chance constraints [[5](https://ieeexplore.ieee.org/abstract/document/10058886)]
- A mixture model-based convexification for chance constraints with non-Gaussian uncertainty [[6](https://ieeexplore.ieee.org/abstract/document/9794334)]

