---
title: "Learning Surrogates for Offline Black-Box Optimization via Gradient Matching"
collection: publications
permalink: /publication/icml24b
excerpt: 'Minh Hoang, Azza Fadhel, Aryan Deshwal, Jana Doppa, and Trong Nghia Hoang'
date: 2024-05-01
venue: '42nd International Conference on Machine Learning (ICML)'
---
Abstract: Offline design optimization problem arises in numerous science and engineering applications including material and chemical design, where expensive online experimentation necessitates the use of in silico surrogate functions to predict and maximize the target objective over candidate designs. Although these surrogates can be learned from offline data, their predictions are often inaccurate outside the offline data regime. This challenge raises a fundamental question about the impact of imperfect surrogate model on the performance gap between its optima and the true optima, and to what extent the performance loss can be mitigated. Although prior work developed methods to improve the robustness of surrogate models and their associated optimization processes, a provably quantifiable relationship between an imperfect surrogate and the corresponding performance gap, as well as whether prior methods directly address it, remain elusive. To shed light on this important question, we present a theoretical framework to understand offline black-box optimization, by explicitly bounding the optimization quality based on how well the surrogate matches the latent gradient field that underlines the offline data. Inspired by our theoretical analysis, we propose a principled black-box gradient matching algorithm to create effective surrogate models for offline optimization, improving over prior approaches on various real-world benchmarks.

[Paper](http://htnghia87.github.io/files/icml24b.pdf)
[Supplementary](http://htnghia87.github.io/files/icml24b-supp.pdf)
[Bibtex](http://htnghia87.github.io/files/icml24b.bib)