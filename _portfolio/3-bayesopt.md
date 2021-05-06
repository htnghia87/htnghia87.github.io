---
title: "Bayesian Optimization for Automated Machine Learning"
excerpt: "<br/><img src='/images/bayesopt-visualize.png'>"
collection: portfolio
---

**Idea and Motivation:**

<p align="justify">

This research direction investigates Bayesian Optimization as a class of gradient-free optimization algorithm to aim to optimize non-differentiable model parameters (i.e. model configurations and/or architecture). The key idea is to learn a GP representation of the model’s behaviors at different combinatoric parameter setup and leverage this information to learn an optimal set of model parameter. The key challenge is to (1) figure out which parameter queries are most informative to accurately learn the correlation between the model’s behaviors at different parameter setup (which defines the GP representation), and (2) how to do that effectively in high-dimensional model space which is often the case in many practical applications. 

</p>

Relevant papers:

**Decentralized High-Dimensional Bayesian Optimization with Factor Graphs (AAAI-18)** [Paper](https://htnghia87.github.io/publication/aaai18)

**Information-Based Multi-Fidelity Bayesian Optimization (BayesOpt Workshop, NIPS-17)** [Paper](https://htnghia87.github.io/publication/bayesopt17) 

**Near-Optimal Active Learning of Multi-Output Gaussian Processes (AAAI-16)** [Paper](https://htnghia87.github.io/publication/aaai16)

**Nonmyopic ϵ-Bayes-Optimal Active Learning of Gaussian Processes (ICML-14)** [Paper](https://htnghia87.github.io/publication/icml14)

**Active Learning is Planning: Nonmyopic ϵ-Bayes-Optimal Active Learning of Gaussian Processes (ECML-14/NECTAR TRACK)** [Paper](https://htnghia87.github.io/publication/ecml14)

In addition (this is probably orthogonal but is still interesting to mention), BO can also be used to design black-box adversarial examples:

**On the Design of Black-box Adversarial Examples by Leveraging Gradient-free Optimization and Operator Splitting Method (ICCV-19)** [Paper](https://htnghia87.github.io/publication/iccv19)