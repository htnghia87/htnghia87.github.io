---
title: "Model Fusion for Personalized Federated Learning"
excerpt: "<br/><img src='/images/model-fusion-visualization.png'>"
collection: portfolio
---

<p align="justify">

**Research Funding:**

I and my collaborator, [Professor Patrick Jaillet](http://web.mit.edu/jaillet/www/) (MIT), were awarded an exploratory research grant **(150K USD)** to investigate new challenges in **On-Device Personalization with Meta Learning** by the MIT-IBM Watson AI Lab.

**Directions:**

I am interested in the problem of **meta or personalized federated learning** in practical domains where production systems hosting analytic services often require generating warm-start solution models for emerging tasks with limited data. One potential approach to address this warm-start challenge is to adopt meta learning to generate a base model that can be adapted to solve unseen tasks with minimal fine-tuning. This however requires the training processes of previous solution models of existing tasks to be synchronized. This is not possible if these models were **pre-trained separately** on private data owned **by different parties** and **cannot be synchronously re-trained**.

To accommodate for such scenarios, my research aims to develop a **new personalized learning framework** that synthesizes customized models for unseen tasks via **fusion of independently pre-trained models of related tasks**. One potential direction to tackle this problem is to train local models separately and treat them as observations drawn from stochastic process that defines the behaviors of a latent global model. This results in formal meta-Bayesian learning frameworks that can infer (or synthesize) a global model given observations of those local models. I coined this approach **model fusion**.

Preliminary works in this emerging area were published at AAAI-19, ICML-19:

Collective Online Learning via Decentralized Gaussian Processes in Massive Multi-Agent Systems (AAAI-19) [Paper](https://htnghia87.github.io/publication/aaai19)
Collective Model Fusion for Multiple Black-Box Experts (ICML-19) [Paper](https://htnghia87.github.io/publication/icml19a)

Related works in the context of neural networks (in collaboration with my amazing MIT-IBM colleagues) at ICML-19 and NeurIPS-19:

Bayesian Nonparametric Federated Learning of Neural Networks (ICML-19) [Paper](https://htnghia87.github.io/publication/icml19b)
Statistical Model Aggregation via Parameter Matching (NeurIPS-19) [Paper](https://htnghia87.github.io/publication/neurips19)

Most recent work in this topic at ICML-20:

Learning Task-Agnostic Embedding of Multiple Black-Box Experts for Multi-Task Model Fusion (ICML-20) [Paper](https://htnghia87.github.io/publication/icml20)

</p>

