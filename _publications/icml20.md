---
title: "Learning Task-Agnostic Embedding of Multiple Black-Box Experts for Multi-Task Model Fusion"
collection: publications
permalink: /publication/icml20
excerpt: 'Trong Nghia Hoang, Chi Thanh Lam, Kian Hsiang Low and Patrick Jaillet'
date: 2020-06-12
venue: '37th International Conference on Machine Learning (ICML)'
---
Abstract: Model fusion is an emerging study in collective learning where heterogeneous experts with private data and learning architectures need to combine their black-box knowledge for better performance. Existing literature achieves this via a local knowledge distillation scheme that transfuses the predictive patterns of each pre-trained expert onto a white-box imitator model, which can be incorporated efficiently into a global model. This scheme however does not extend to multi-task scenarios where different experts were trained to solve different tasks and only part of their distilled knowledge is relevant to a new task. To address this multi-task challenge, we develop a new fusion paradigm that represents each expert as a distribution over a spectrum of predictive prototypes, which are isolated from task-specific information encoded within the prototype distribution. The task-agnostic prototypes can then be reintegrated to generate a new model that solves a new task encoded with a different prototype distribution. The fusion and adaptation performance of the proposed framework is demonstrated empirically on several real-world benchmark datasets.

[Paper](http://htnghia87.github.io/files/icml20.pdf)
[Supplementary](http://htnghia87.github.io/files/icml20-supp.pdf)
[Bibtex](http://htnghia87.github.io/files/icml20.bib)