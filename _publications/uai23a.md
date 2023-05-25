---
title: "Merging Models Pre-Trained on Different Features with Consensus Graph"
collection: publications
permalink: /publication/uai23a
excerpt: 'Tengfei Ma, Trong Nghia Hoang and Jie Chen'
date: 2023-08-01
venue: '39th Conference on Uncertainty in Artificial Intelligence (UAI)'
---
Abstract: Learning an effective global model on private and decentralized datasets has become an increasingly important challenge of machine learning when applied in practice. Existing distributed learning paradigms, such as Federated Learning, enable this via model aggregation which enforces a strong form of modeling homogeneity and synchronicity across clients. This is however not suitable to many practical scenarios. For example, in distributed sensing, heterogeneous sensors reading data from different views of the same phenomenon would need to use different models for different data modalities. Local learning therefore happens in isolation but inference requires merging the local models to achieve consensus. To enable consensus among local models, we propose a feature fusion approach that extracts local representations from local models and incorporates them into a global representation that improves the prediction performance. Achieving this requires addressing two non-trivial problems. First, we need to learn an alignment between similar feature components which are arbitrarily arranged across clients to enable representation aggregation. Second, we need to learn a consensus graph that captures the high-order interactions between local feature spaces and how to combine them to achieve a better prediction. This paper presents solutions to these problems and demonstrates them in real-world applications such as power grids and traffic networks.

[Paper](http://htnghia87.github.io/files/uai23a.pdf)
[Supplementary](http://htnghia87.github.io/files/uai23a.pdf)
[Bibtex](http://htnghia87.github.io/files/uai23a.bib)