---
layout: archive
title: "Research topics"
permalink: /research/index.html
author_profile: true
---



## 1. Learn to linearize hard constraints (Constraint learning)
- Train a neural network (NN) that maps decisions to constraint violations (e.g., bus voltage or branch flow violation) 
- Equivalently reformulate the trained NN into mixed-integer linear constraints to replicate original hard constraints (e.g., power flow constraints)
- Can be interpreted as a piecewise linearization method
- [[Link](https://ieeexplore.ieee.org/abstract/document/9502573)] for replicating deterministic constraints, [[Link](https://ieeexplore.ieee.org/abstract/document/9956906)] for replicating probabilistic constraints, and [[Link](https://ieeexplore.ieee.org/abstract/document/10058008)] for its piecewise linearization-based intepretation  
![Editing](https://github.com/lelouchsola/ChenGe/blob/master/pages/constraint_learning.png?raw=true){:height="400px" width="800px"} 

## 2. End-to-end optimization proxy for power dispatch
- Design a data-driven formulation that can learn a decision rule from day-ahead observable information to cost-effective dispatch decisions for the future delivery interval [[Link](https://arxiv.org/abs/2402.00773)]
- Discuss the choice of loss functions for training end-to-end dispatch proxies [[Link](https://arxiv.org/abs/2402.00772)]
![Editing](https://github.com/lelouchsola/ChenGe/blob/master/pages/E2EProxy.png?raw=true){:height="400px" width="800px"} 

## 3. Power system operations under uncertainty
- A mixture model-based convexification for chance constraints with non-Gaussian uncertainty [[Link](https://ieeexplore.ieee.org/abstract/document/9794334)]
- A fast distributionally robust chance-constrained method that can quantify the impact of the uncertainty offline [[Link](https://ieeexplore.ieee.org/abstract/document/9417102)]
- A SVM-based approximation for chance constraints [[Link](https://ieeexplore.ieee.org/abstract/document/10058886)]
![Editing](https://github.com/lelouchsola/ChenGe/blob/master/pages/CCP.png?raw=true){:height="400px" width="800px"} 

