---
title: "Personalized Federated Domain Adaptation for Item-to-Item Recommendation"
collection: publications
permalink: /publication/uai23b
excerpt: 'Ziwei Fan, Trong Nghia Hoang, Hao Ding and Anoop Deoras'
date: 2023-08-11
venue: '39th Conference on Uncertainty in Artificial Intelligence (UAI)'
---
Abstract: Item-to-Item (I2I) recommendation is an important function in most recommendation systems, which generates replacement or complement suggestions for a particular item based on its semantic similarities to other cataloged items. Given that subsets of items in a recommendation system might be co-interacted with by the same set of customers, graph-based models, such as graph neural networks (GNNs), provide a natural framework to combine, ingest and extract valuable insights from such high-order relational interactions between cataloged items, as well as their metadata features, as has been shown in many recent studies. However, learning GNNs effectively for I2I requires ingesting a large amount of relational data, which might not always be available, especially in new, emerging market segments. To mitigate this data bottleneck, we postulate that recommendation patterns learned from existing mature market segments (with private data) could be adapted to build effective warm-start models for emerging ones. To achieve this, we propose and investigate a personalized federated modeling framework based on GNNs to summarize, assemble and adapt recommendation patterns across market segments with heterogeneous customer behaviors into effective local models. Our key contribution is a personalized graph adaptation model that bridges the gap between recent literature on federated GNNs and (non-graph) personalized federated learning, which either does not optimize for the adaptability of the federated model or is restricted to local models with homogeneous parameterization, excluding GNNs with heterogeneous local graphs. The effectiveness of our framework is demonstrated on a real-world dataset on multiple item categories spanning multiple market segments.

[Paper](http://htnghia87.github.io/files/uai23b.pdf)
[Supplementary](http://htnghia87.github.io/files/uai23b.pdf)
[Bibtex](http://htnghia87.github.io/files/uai23b.bib)