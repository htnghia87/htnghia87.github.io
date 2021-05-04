---
title: "Bayesian Optimization and Active Learning of Gaussian Processes"
excerpt: "<br/><img src='/images/500x300.png'>"
collection: portfolio
---

Another research direction that I am pursuing is Bayesian Optimization which investigates a class of gradient- free optimization algorithm to optimize non-differentiable model parameters, which aligns with the current auto ML initiative. The key idea is to learn a GP representation of the model’s behaviors at different combinatoric parameter setup and leverage this information to learn an optimal set of model parameter. The key challenge is to (1) figure out which parameter queries are most informative to accurately learn the correlation between the model’s behaviors at different parameter setup (which defines the GP representation), and (2) how to do that effectively in high-dimensional model space which is often the case in many practical applications. Relevant papers were published in ICML-14, AAAI-16, AAAI-18, ICCV-19 & NeurIPS-20