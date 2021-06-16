# Pattern Recognition with Autoencoders: Binary Ellipses

As a necessity of analyzing experimental data taken in turbulent flows, I have been working with various analytical and numerical tools for extracting important flow patterns. The most common one I use is Proper Orthogonal Decomposition (POD), also known as Principal Component Analysis (PCA) in Machine Learning.  Besides dimensional reduction, POD/PCA works great for extracting abstract representations of so-called coherent structures in the flow field that fluctuate periodically in a way resembling harmonic motions. However, due to its linear nature, POD/PCA is not always capable or efficient at capturing non-linear flow phenomena that are sporadic and chaotic. Increasingly, neural-network based unsupervised (or self-supervised) methods such as autoencoder have been adapted to tackle these problems in the field of fluid dynamics.

## Table of Content

| Initiated | Title                                                                                            | Note                |
| --------- | ------------------------------------------------------------------------------------------------ | ------------------- |
| 05.2021   | [PCA Autoencoder (Part 1): Binary Ellipses](pca_ae.ipynb)                                        | with 2 latent codes |
| 06.2021   | [PCA Autoencoder (Part 2): Binary Ellipses with rotation](pca_ae_rotation.ipynb)                 | with 3 latent codes |
| 06.2021   | [PCA Autoencoder (Part 3): Hierarchy treatment (without rotation)](pca_ae_hierarchy.ipynb)       | with 2 sub-networks |
| 06.2021   | [PCA Autoencoder (Part 4): Hierarchy treatment (with rotation)](pca_ae_hierarchy_rotation.ipynb) | with 3 sub-networks |
