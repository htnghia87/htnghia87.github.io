---
title: "Offline Model-based Optimization via Policy-Guided Gradient Search"
collection: publications
permalink: /publication/aaai24a
excerpt: 'Yassine Chemingui, Aryan Deshwal, Trong Nghia Hoang and Janardhan Rao Doppa'
date: 2024-02-20
venue: '38th Annual AAAI Conference on Artificial Intelligence'
---
Abstract: Offline optimization is an emerging problem in many experimental engineering domains including protein, drug or aircraft design, where online experimentation to collect evaluation data is too expensive or dangerous. To avoid that, one has to optimize an unknown function given only its offline evaluation at a fixed set of inputs. A naive solution to this problem is to learn a surrogate model of the unknown function and optimize this surrogate instead. However, such a naive optimizer is prone to erroneous overestimation of the surrogate (possibly due to over-fitting on a biased sample of function evaluation) on inputs outside the offline dataset. Prior approaches addressing this challenge have primarily focused on learning robust surrogate models. However, their search strategies are derived from the surrogate model rather than the actual offline data. To fill this important gap, we introduce a new learning-to-search perspective for offline optimization by reformulating it as an offline reinforcement learning problem. Our proposed policy-guided gradient search approach explicitly learns the best policy for a given surrogate model created from the offline data. Our empirical results on multiple benchmarks demonstrate that the learned optimization policy can be combined with existing offline surrogates to significantly improve the optimization performance.

[Paper](http://htnghia87.github.io/files/aaai24a.pdf)
[Supplementary](http://htnghia87.github.io/files/aaai24a.pdf)
[Bibtex](http://htnghia87.github.io/files/aaai24a.bib)