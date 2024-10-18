---
title: "Model Fusion for Federated Learning across Heterogeneous Systems"
excerpt: "<br/><img src='/images/model-fusion-visualization.png'>"
collection: portfolio
---

**Research Funding:**

<p align="justify">

I and my academic collaborator, <a href="http://web.mit.edu/jaillet/www/">Patrick Jaillet</a> (MIT), were awarded (as co-PI) an exploratory research grant (150K USD) to investigate new challenges in <b>On-Device Personalization with Meta Learning</b> by the <a href="https://mitibmwatsonailab.mit.edu/">MIT-IBM Watson AI Lab</a> (2020-2021). 

</p>

<p align="justify">

This research is also part of another research funding under the <b>AI Singapore Research Programme: Toward Trustable Model-centric Sharing for Collaborative Machine Learning,
S$8,401,002.40, Apr 2021 - Mar 2025 </b> of which I am an affiliated collaborator working on the model fusion package.

</p>

[Media Article](https://medium.com/ncript/sharing-without-oversharing-in-collective-machine-learning-292ecd92a71e)

**Idea and Motivation:**

<p align="justify">

I am interested in the problem of <b>meta or personalized federated learning</b> in practical domains where production systems hosting analytic services often require generating warm-start solution models for emerging tasks with limited data. One potential approach to address this warm-start challenge is to adopt meta learning to generate a base model that can be adapted to solve unseen tasks with minimal fine-tuning. This however requires the training processes of previous solution models of existing tasks to be synchronized. This is not possible if these models were <b>pre-trained separately</b> on private data owned <b>by different parties</b> and <b>cannot be synchronously re-trained.</b>

</p>

<p align="justify">

To accommodate for such scenarios, my research aims to develop a <b>new personalized learning framework</b> that synthesizes customized models for unseen tasks via <b>fusion of independently pre-trained models of related tasks.</b> One potential direction to tackle this problem is to train local models separately and treat them as observations drawn from stochastic process that defines the behaviors of a latent global model. This results in formal meta-Bayesian learning frameworks that can infer (or synthesize) a global model given observations of those local models. I coined this approach <b>model fusion.</b>

</p>

Most recent work:

**Effective Knowledge Representation and Utilization for Sustainable Collaborative Learning across Heterogeneous Systems (AI Magazine, 2024)** [Paper](https://htnghia87.github.io/publication/ai-magazine-24)

**Probabilistic Federated Prompt-Tuning (NeurIPS-24)** [Paper](https://htnghia87.github.io/publication/neurips24a)

**Few-Shot Learning via Repurposing Ensemble of Black-Box Models (AAAI-24)** [Paper](https://htnghia87.github.io/publication/aaai24b)

**Federated Learning of Models Pre-Trained on Different Features with Consensus Graphs (UAI-23)** [Paper](https://htnghia87.github.io/publication/uai23a)

**Personalized Federated Domain Adaptation for Item-to-Item Recommendation (UAI-23)** [Paper](https://htnghia87.github.io/publication/uai23b)

**Bayesian Federated Estimation of Causal Effects from Observationsl Data (UAI-22)** [Paper](https://htnghia87.github.io/publication/uai22)

**Adaptive Multi-Source Causal Inference from Observational Data (CIKM-22)** [Paper](https://htnghia87.github.io/publication/cikm22)

**Model Fusion for Personalized Learning (ICML-21)** [Paper](https://htnghia87.github.io/publication/icml21)

**Learning Task-Agnostic Embedding of Multiple Black-Box Experts for Multi-Task Model Fusion (ICML-20)** [Paper](https://htnghia87.github.io/publication/icml20)

Preliminary works in this emerging area were published at AAAI-19, ICML-19:

**Collective Online Learning via Decentralized Gaussian Processes in Massive Multi-Agent Systems (AAAI-19)** [Paper](https://htnghia87.github.io/publication/aaai19)

**Collective Model Fusion for Multiple Black-Box Experts (ICML-19)** [Paper](https://htnghia87.github.io/publication/icml19a)

Related works in the context of neural networks (in collaboration with my MIT-IBM colleagues) at ICML-19 and NeurIPS-19:

**Bayesian Nonparametric Federated Learning of Neural Networks (ICML-19)** [Paper](https://htnghia87.github.io/publication/icml19b)

**Statistical Model Aggregation via Parameter Matching (NeurIPS-19)** [Paper](https://htnghia87.github.io/publication/neurips19)












