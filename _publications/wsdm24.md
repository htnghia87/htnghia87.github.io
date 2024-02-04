---
title: "Pre-Trained Recommender Systems: A Causal Debiasing Perspective"
collection: publications
permalink: /publication/wsdm24
excerpt: 'Ziqian Lin, Hao Ding, Trong Nghia Hoang, Branislav Kveton, Anoop Deoras and Hao Wang'
date: 2024-03-04
venue: '17th ACM International Conference on Web Search and Data Mining'
---
Abstract: Recent studies on pre-trained vision/language models have demonstrated the practical benefit of a new, promising solution-building paradigm in AI where models can be pre-trained on broad data describing a generic task space and then adapted successfully to solve a wide range of downstream tasks, even when training data is severely limited (e.g., in zero- or few-shot learning scenarios). Inspired by such progress, we investigate in this paper the possibilities and challenges of adapting such a paradigm to recommender systems. In particular, we develop a generic recommender that captures universal interaction patterns by training on generic user-item interaction data extracted from different domains, which can then be fast adapted to improve few-shot learning performance in unseen new domains (with limited data). However, unlike vision/language data which share strong conformity in the semantic space, universal patterns underlying recommendation data collected across different domains (e.g., different countries) are often occluded by both in-domain and cross-domain biases implicitly imposed by the cultural differences in their user and item bases. Such heterogeneous biases tend to hinder the effectiveness of pre-trained models. To address this challenge, we further introduce and formalize a causal debiasing perspective, which is substantiated via a hierarchical Bayesian deep learning model, named PreRec. Our empirical studies on real-world data show that the proposed model could significantly improve the recommendation performance in zero- and few-shot learning settings under both cross-market and cross-platform scenarios.

[Paper](http://htnghia87.github.io/files/wsdm24.pdf)
[Supplementary](http://htnghia87.github.io/files/wsdm24.pdf)
[Bibtex](http://htnghia87.github.io/files/wsdm24.bib)