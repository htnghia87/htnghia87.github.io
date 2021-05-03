---
title: "On the Design of Black-box Adversarial Examples by Leveraging Gradient-free Optimization and Operator Splitting Method"
collection: publications
permalink: /publication/iccv19
excerpt: 'Pu Zhao, Sijia Liu, Pin-Yu Chen, Nghia Hoang, Kaidi Xu, Bhavya Kailkhura and Xue Lin'
date: 2019-10-27
venue: 'International Conference on Computer Vision (ICCV)'
---
Abstract: Robust machine learning is currently one of the most prominent topics which could potentially help shaping a future of advanced AI platforms that not only perform well in average cases but also in worst cases or adverse situations. Despite the long-term vision, however, existing studies on black-box adversarial attacks are still restricted to very specific settings of threat models (e.g., single distortion metric and restrictive assumption on target model's feedback to queries) and/or suffer from prohibitively high query complexity. To push for further advances in this field, we introduce a general framework based on an operator splitting method, the alternating direction method of multipliers (ADMM) to devise efficient, robust black-box attacks that work with various distortion metrics and feedback settings without incurring high query complexity. Due to the black-box nature of the threat model, the proposed ADMM solution framework is integrated with zeroth-order (ZO) optimization and Bayesian optimization (BO), and thus is applicable to the gradient-free regime. This results in two new black-box adversarial attack generation methods, ZO-ADMM and BO-ADMM. Our empirical evaluations on image classification datasets show that our proposed approaches have much lower function query complexities compared to state-of-the-art attack methods, but achieve very competitive attack success rates.

[Paper](http://htnghia87.github.io/files/iccv19.pdf)
[Supplementary](http://htnghia87.github.io/files/iccv19-supp.pdf)
[Bibtex](http://htnghia87.github.io/files/iccv19.bib)