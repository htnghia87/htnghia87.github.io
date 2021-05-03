---
title: "Collective Online Learning via Decentralized Gaussian Processes in Massive Multi-Agent Systems"
collection: publications
permalink: /publication/aaai19
excerpt: 'Trong Nghia Hoang (co-first author), Quang Minh Hoang (co-first author), Kian Hsiang Low and Jonathan How'
date: 2019-01-27
venue: '33rd AAAI Conference on Artificial Intelligence (AAAI)'
---
Abstract: This paper presents a novel Collective Online Learning of Gaussian Processes (COOL-GP) framework for enabling a massive number of GP inference agents to simultaneously perform (a) efficient online updates of their GP models using their local streaming data with varying correlation structures and (b) decentralized fusion of their resulting online GP models with different learned hyperparameter settings and inducing inputs. To realize this, we exploit the notion of a common encoding structure to encapsulate the local streaming data gathered by any GP inference agent into summary statistics based on our proposed representation, which is amenable to both an efficient online update via an importance sampling trick as well as multi-agent model fusion via decentralized message passing that can exploit sparse connectivity among agents for improving efficiency and enhance the robustness of our framework against transmission loss. We provide a rigorous theoretical analysis of the approximation loss arising from our proposed representation to achieve efficient online updates and model fusion. Empirical evaluations show that COOL-GP is highly effective in model fusion, resilient to information disparity between agents, robust to transmission loss, and can scale to thousands of agents.

[Paper](http://htnghia87.github.io/files/aaai19.pdf)
[Supplementary](http://htnghia87.github.io/files/aaai19-supp.pdf)
[Bibtex](http://htnghia87.github.io/files/aaai19.bib)