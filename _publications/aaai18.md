---
title: "Decentralized High-Dimensional Bayesian Optimization with Factor Graphs"
collection: publications
permalink: /publication/aaai18
excerpt: 'Trong Nghia Hoang, Quang Minh Hoang, Ruofei Ouyang and Kian Hsiang Low'
date: 2018-02-02
venue: '32nd AAAI Conference on Artificial Intelligence (AAAI)'
---
Abstract: This paper presents a novel decentralized high-dimensional Bayesian optimization (DEC-HBO) algorithm that, in contrast to existing HBO algorithms, can exploit the interdependent effects of various input components on the output of the unknown objective function f for boosting the BO performance and still preserve scalability in the number of input dimensions without requiring prior knowledge or the existence of a low (effective) dimension of the input space. To realize this, we propose a sparse yet rich factor graph representation of f to be exploited for designing an acquisition function that can be similarly represented by a sparse factor graph and hence be efficiently optimized in a decentralized manner using distributed message passing. Despite richly characterizing the interdependent effects of the input components on the output of f with a factor graph, DEC-HBO can still guarantee (asymptotic) no-regret performance. Empirical evaluation on synthetic and real-world experiments shows that DEC-HBO outperforms the state-of-the-art HBO algorithms. 

[Paper](http://htnghia87.github.io/files/aaai18.pdf)
[Supplementary](http://htnghia87.github.io/files/aaai18-supp.pdf)
[Bibtex](http://htnghia87.github.io/files/aaai18.bib)