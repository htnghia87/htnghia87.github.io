---
title: "Probabilistic Federated Prompt-Tuning"
collection: publications
permalink: /publication/neurips24a
excerpt: 'Pei-Yau Weng, Minh Hoang, Lam M. Nguyen, My T. Thai, Tsui-Wei Weng, and Trong Nghia Hoang'
date: 2024-09-25
venue: '38th Annual Conference on Neural Information Processing Systems'
---
Abstract: Fine-tuning pre-trained models is a popular approach in machine learning for solving complex tasks with moderate data. However, fine-tuning the entire pre-trained model is ineffective in federated data scenarios where local data distributions are diversely skewed. To address this, we explore integrating federated learning with a more effective prompt-tuning method, optimizing for a small set of input prefixes to reprogram the pre-trained model's behavior. Our approach transforms federated learning into a distributed set modeling task, aggregating diverse sets of prompts to globally fine-tune the pre-trained model. We benchmark various baselines based on direct adaptations of existing federated model aggregation techniques and introduce a new probabilistic prompt aggregation method that substantially outperforms these baselines. Our reported results on a variety of computer vision datasets confirm that the proposed method is most effective to combat extreme data heterogeneity in federated learning.

[Paper](http://htnghia87.github.io/files/neurips24a.pdf)
[Supplementary](http://htnghia87.github.io/files/neurips24a-supp.pdf)
[Bibtex](http://htnghia87.github.io/files/neurips24a.bib)