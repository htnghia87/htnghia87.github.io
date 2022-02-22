---
title: "Learning Personalized Item-to-Item Recommendation Metric via Implicit Feedback"
collection: publications
permalink: /publication/aistats22
excerpt: 'Trong Nghia Hoang, Anoop Deoras, Tong Zhao, Jin Li and George Karypis'
date: 2022-03-28
venue: '25th International Conference on Artificial Intelligence and Statistics (AISTATS)'
---
Abstract: This paper studies the item-to-item recommendation problem in recommender systems from a new perspective of metric learning via implicit feedback. We develop and investigate a personalizable deep metric model that captures both the internal contents of items and how they were interacted with by users. There are two key challenges in learning such model. First, there is no explicit similarity annotation, which deviates from the assumption of most metric learning methods. Second, these approaches ignore the fact that items are often represented by multiple sources of meta data and different users use different combinations of these sources to form their own notion of similarity. To address these challenges, we develop a new metric representation embedded as kernel parameters of a probabilistic model. This helps express the correlation between items that a user has interacted with, which can be used to predict user interaction with new items. Our approach hinges on the intuition that similar items induce similar interactions from the same user, thus fitting a metric-parameterized model to predict an implicit feedback signal could indirectly guide it towards finding the most suitable metric for each user. To this end, we also analyze how and when the proposed method is effective from a theoretical lens. Its empirical effectiveness is also demonstrated on several real-world datasets.

[Paper](http://htnghia87.github.io/files/aistats22.pdf)
[Supplementary](http://htnghia87.github.io/files/aistats22-supp.pdf)
[Bibtex](http://htnghia87.github.io/files/aistats22.bib)