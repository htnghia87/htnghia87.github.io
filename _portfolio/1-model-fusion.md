---
title: "Model Fusion for Personalized Learning"
excerpt: "<br/><img src='/images/1-model-fusion.png'>"
collection: portfolio
---

I am interested in the problem of meta learning in practical domains where production systems hosting analytic services often require generating warm-start solution models for emerging tasks with limited data. One potential approach to address this warm-start challenge is to adopt meta learning to generate a base model that can be adapted to solve unseen tasks with minimal fine-tuning. This however requires the training processes of previous solution models of existing tasks to be synchronized. This is not possible if these models were pre-trained separately on private data owned by different parties and cannot be synchronously re-trained.

To accommodate for such scenarios, my research aims to develop a new personalized learning framework that synthesizes customized models for unseen tasks via fusion of independently pre-trained models of related tasks. One potential direction to tackle this problem is to train local models separately and treat them as observations drawn from stochastic process that defines the behaviors of a latent global model. This results in formal meta-Bayesian learning frameworks that can infer (or synthesize) a global model given observations of those local models. I coined this approach model fusion.

My preliminary works in this emerging area were recently published at AAAI-19, ICML-19, NeurIPS-19 & ICML-20.

Research Highlight:

I and my collaborator, Patrick Jaillet (MIT), were awarded an exploratory research grant (150K USD) for On-Device Personalization with Meta Learning by the MIT-IBM board of directors (12/2020-12/2021) 