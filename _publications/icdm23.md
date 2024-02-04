---
title: "Promoting Robustness of Randomized Smoothing: Two Cost-Effective Approaches"
collection: publications
permalink: /publication/icdm23
excerpt: 'Linbo Liu, Trong Nghia Hoang, Lam Minh Nguyen and Tsui-Wei Weng'
date: 2023-12-01
venue: '23rd IEEE International Conference on Data Mining'
---
Abstract: Randomized smoothing has recently attracted attentions in the field of adversarial robustness to provide provable robustness guarantees on smoothed neural network classifiers. However, existing works show that vanilla randomized smoothing usually does not provide good robustness performance and often requires (re)training techniques on the base classifier in order to boost the robustness of the resulting smoothed classifier. In this work, we propose two cost-effective approaches to boost the robustness of randomized smoothing while preserving its clean performance. The first approach introduces a new robust training method AdvMacerwhich combines adversarial training and robustness certification maximization for randomized smoothing. We show that AdvMacer can improve the robustness performance of randomized smoothing classifiers compared to SOTA baselines, while being 3x faster to train than MACER baseline. The second approach introduces a post-processing method EsbRS which greatly improves the robustness certificate based on building model ensembles. We explore different aspects of model ensembles that has not been studied by prior works and propose a novel design methodology to further improve robustness of the ensemble based on our theoretical analysis.

[Paper](http://htnghia87.github.io/files/icdm23.pdf)
[Supplementary](http://htnghia87.github.io/files/icdm23.pdf)
[Bibtex](http://htnghia87.github.io/files/icdm23.bib)