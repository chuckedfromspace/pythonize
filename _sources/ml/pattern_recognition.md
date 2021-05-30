# Pattern Recognition

As a necessity of analyzing experimental data taken in turbulent flows, I have been working with various analytical and numerical tools for extracting important flow patterns. The most common one I use is Proper Orthogonal Decomposition (POD), also known as Principal Component Analysis (PCA) in Machine Learning.  Besides dimensional reduction, POD/PCA works great for extracting abstract representations of so-called coherent structures in the flow field that fluctuate periodically in a way resembling harmonic motions. However, due to its linear nature, POD/PCA is not always capable or efficient at capturing non-linear flow phenomena that are sporadic and chaotic. Increasingly, neural-network based unsupervised (or self-supervised) methods such as autoencoder have been adapted to tackle these problems in the field of fluid dynamics.

## Table of Content

| Initiated | Title                                    |
| --------- | ---------------------------------------- |
| 05.2021   | [PCA Autoencoder (Part 1)](pca_ae.ipynb) |
