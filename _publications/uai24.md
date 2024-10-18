---
title: "Revisiting Kernel Attention with Correlated Gaussian Process Representation"
collection: publications
permalink: /publication/uai24
excerpt: 'Long Minh Bui, Tho Tran Huu, Duy Dinh, Tan Minh Nguyen, and Trong Nghia Hoang'
date: 2024-04-26
venue: '40th Conference on Uncertainty in Artificial Intelligence (UAI)'
---
Abstract: Transformers have increasingly become the de facto method to model sequential data with state-of-the-art performance. Due to its widespread use, being able to estimate and calibrate its modeling uncertainty is important to understand and design robust transformer models. To achieve this, previous works have used Gaussian processes (GPs) to perform uncertainty calibration for the attention units of transformers and attained notable successes. However, such approaches have to confine the transformers to the space of symmetric attention to ensure the necessary symmetric requirement of their GP's kernel specification, which reduces the representation capacity of the model. To mitigate this restriction, we propose the Correlated Gaussian Process Transformer (CGPT), a new class of transformers whose self-attention units are modeled as cross-covariance between two correlated GPs (CGPs). This allows asymmetries in attention and can enhance the representation capacity of GP-based transformers. We also derive a sparse approximation for CGP to make it scale better. Our empirical studies show that both CGP-based and sparse CGP-based transformers achieve better performance than state-of-the-art GP-based transformers on a variety of benchmark tasks.

[Paper](http://htnghia87.github.io/files/uai24.pdf)
[Supplementary](http://htnghia87.github.io/files/uai24-supp.pdf)
[Bibtex](http://htnghia87.github.io/files/uai24.bib)