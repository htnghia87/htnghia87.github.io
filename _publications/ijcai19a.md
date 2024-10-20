---
title: "RDPD: Rich Data Helps Poor Data via Imitation"
collection: publications
permalink: /publication/ijcai19a
excerpt: 'Shenda Hong, Cao Xiao, Trong Nghia Hoang, Tengfei Ma, Hongyan Li and Jimeng Sun'
date: 2019-08-10
venue: '28th International Joint Conference on Artificial Intelligence (IJCAI)'
---
Abstract: In many situations, we need to build and deploy separate models in related environments with different data qualities. For example, an environment with strong observation equipments (e.g., intensive care units) often provides high-quality multi-modal data, which are acquired from multiple sensory devices and have rich-feature representations. On the other hand, an environment with poor observation equipment (e.g., at home) only provides low-quality, uni-modal data with poor-feature representations. To deploy a competitive model in a poor-data environment without requiring direct access to multi-modal data acquired from a rich-data environment, this paper develops and presents a knowledge distillation (KD) method (RDPD) to enhance a predictive model trained on poor data using knowledge distilled from a high-complexity model trained on rich, private data. We evaluated RDPD on three real-world datasets and shown that its distilled model consistently outperformed all baselines across all datasets, especially achieving the greatest performance improvement over a model trained only on low-quality data by 24.56% on PR-AUC and 12.21% on ROC-AUC, and over that of a state-of-the-art KD model by 5.91% on PR-AUC and 4.44% on ROC-AUC.

[Paper](http://htnghia87.github.io/files/ijcai19a.pdf)
[Bibtex](http://htnghia87.github.io/files/ijcai19a.bib)