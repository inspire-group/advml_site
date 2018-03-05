---
layout: page
title: Using data transformations as a defense against adversarial examples
---

**Useful Links**: [Paper](https://arxiv.org/abs/1704.02654), [Code](https://github.com/inspire-group/ml_defense)

While data transformations such as Principal Component Analysis have been used to reduce computational resources and combat over-fitting, they have not been investigated from the viewpoint of securing learning systems. In this work, we show that adding a data transformation layer at the beginning of machine learning algorithms such as Support Vector Machines and neural networks can make them up to 50 times more robust against black-box attacks and up to 2 times more robust against white-box attacks. 

The PCA components define a lower-dimensional manifold on which the data lies, which helps reduce the attack space for an adversary. Ideally, the manifold that should be identified is the one from which the data is generated, but this is hard to find. In lieu of this, we use PCA to find a manifold which _explains_ most of the variance in the data. 