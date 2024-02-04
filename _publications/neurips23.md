---
title: "Incentives in Private Collaborative Machine Learning"
collection: publications
permalink: /publication/neurips23a
excerpt: 'Rachael Hwee Ling Sim, Yehong Zhang, Trong Nghia Hoang, Xinyi Xu, Bryan Kian Hsiang Low and Patrick Jaillet'
date: 2023-12-13
venue: '37th Annual Conference on Neural Information Processing Systems'
---
Abstract: Collaborative machine learning involves training models on data from multiple
parties but must incentivize their participation. Existing data valuation methods
fairly value and reward each party based on shared data or model parameters but
neglect the privacy risks involved. To address this, we introduce differential privacy
(DP) as an incentive. Each party can select its required DP guarantee and perturb
its sufficient statistic (SS) accordingly. The mediator values the perturbed SS
by the Bayesian surprise it elicits about the model parameters. As our valuation
function enforces a privacy-valuation trade-off, parties are deterred from selecting
excessive DP guarantees that reduce the utility of the grand coalition’s model.
Finally, the mediator rewards each party with different posterior samples of the
model parameters. Such rewards still satisfy existing incentives like fairness but
additionally preserve DP and a high similarity to the grand coalition’s posterior.
We empirically demonstrate the effectiveness and practicality of our approach on
synthetic and real-world datasets.

[Paper](http://htnghia87.github.io/files/neurips23.pdf)
[Supplementary](http://htnghia87.github.io/files/neurips23.pdf)
[Bibtex](http://htnghia87.github.io/files/neurips23.bib)