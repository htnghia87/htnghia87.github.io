---
title: "Black-Box Optimization for Automated Machine Learning and Scientic Discovery"
excerpt: "<br/><img src='/images/bayesopt-visualize.png'>"
collection: portfolio
---

**Idea and Motivation:**

<p align="justify">

This research direction investigates a class of optimization algorithms for black-box functions. Examples of such black-box functions include model configuration and/or architecture of a large neural network and/or latent functions relating material designs to their performance. Often, such functions are not known explicitly and are only accessible via a set of offline input-output data points. The key idea is to learn a surrogate representation of the model’s behaviors at different combinatoric parameter setup and leverage this information to learn an optimal set of model parameter. This can be substantiated in either offline or online settings with different design principles. In online settings, the key challenge is to (1) figure out which parameter queries are most informative to accurately learn the correlation between the model’s behaviors at different parameter setup (which defines the surrogate representation), and (2) how to do that effectively in high-dimensional model space which is often the case in many practical applications.  In offline settings, without the ability to sample new data, the key challenge is to approximate (conservatively) the safe input regions where the surrogate predictions are most reliable and learn an effective search polices can also be learned together in a closed feedback loop. 

</p>

Relevant papers:

**Incorporating Surrogate Gradient Norm to Improve Offline Optimization Techniques (NeurIPS-24)** [Paper](https://htnghia87.github.io/publication/neurips24b)

**Boosting Offline Optimizers with Surrogate Sensitivity (ICML-24)** [Paper](https://htnghia87.github.io/publication/icml24a)

**Learning Surrogate for Offline Black-Box Optimization via Gradient Matching (ICML-24)** [Paper](https://htnghia87.github.io/publication/icml24b)

**Offline Model-based Optimization via Policy-Guided Gradient Search (AAAI-24)** [Paper](https://htnghia87.github.io/publication/aaai24a)

**On the Design of Black-box Adversarial Examples by Leveraging Gradient-free Optimization and Operator Splitting Method (ICCV-19)** [Paper](https://htnghia87.github.io/publication/iccv19)

**Decentralized High-Dimensional Bayesian Optimization with Factor Graphs (AAAI-18)** [Paper](https://htnghia87.github.io/publication/aaai18)

**Information-Based Multi-Fidelity Bayesian Optimization (BayesOpt Workshop, NIPS-17)** [Paper](https://htnghia87.github.io/publication/bayesopt17) 

**Near-Optimal Active Learning of Multi-Output Gaussian Processes (AAAI-16)** [Paper](https://htnghia87.github.io/publication/aaai16)

**Nonmyopic ϵ-Bayes-Optimal Active Learning of Gaussian Processes (ICML-14)** [Paper](https://htnghia87.github.io/publication/icml14)

**Active Learning is Planning: Nonmyopic ϵ-Bayes-Optimal Active Learning of Gaussian Processes (ECML-14/NECTAR TRACK)** [Paper](https://htnghia87.github.io/publication/ecml14)