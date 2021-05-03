---
title: "Near-Optimal Active Learning of Multi-Output Gaussian Processes"
collection: publications
permalink: /publication/aaai16
excerpt: 'Yehong Zhang, Trong Nghia Hoang, Kian Hsiang Low and Mohan Kankanhalli'
date: 2016-02-12
venue: '30th AAAI Conference on Artificial Intelligence (AAAI)'
---
Abstract: This paper addresses the problem of active learning of a multi-output Gaussian process (MOGP) model representing multiple types of coexisting correlated environmental phenomena. In contrast to existing works, our active learning problem involves selecting not just the most informative sampling locations to be observed but also the types of measurements at each selected location for minimizing the predictive uncertainty (i.e., posterior joint entropy) of a target phenomenon of interest given a sampling budget. Unfortunately, such an entropy criterion scales poorly in the numbers of candidate sampling locations and selected observations when optimized. To resolve this issue, we first exploit a structure common to sparse MOGP models for deriving a novel active learning criterion. Then, we exploit a relaxed form of sub-modularity property of our new criterion for devising a polynomial-time approximation algorithm that guarantees a constant-factor approximation of that achieved by the optimal set of selected observations. Empirical evaluation on real-world datasets shows that our proposed approach outperforms existing algorithms for active learning of MOGP and single-output GP models. 

[Paper](http://htnghia87.github.io/files/aaai16.pdf)
[Supplementary](http://htnghia87.github.io/files/aaai16-supp.pdf)
[Bibtex](http://htnghia87.github.io/files/aaai16.bib)