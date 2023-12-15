---
title: "Learn the Force We Can: Enabling Sparse Motion Control in Multi-Object Video Generation"
collection: publications
permalink: /publication/yoda_aaai_2024
date: 2024-02-22
venue: The 38th AAAI Conference on Artificial Intelligence
citation: 'A. Davtyan and P. Favaro. (2024). &quot;Learn the Force We Can: Enabling Sparse Motion Control in Multi-Object Video Generation.&quot; <i>Proceedings of the 38th AAAI Conference on Artificial Intelligence</i>.'
---

[[PDF]](https://arxiv.org/pdf/2306.03988.pdf) [[Project Page]](https://araachie.github.io/yoda/)

## Abstract

We propose a novel unsupervised method to autoregressively generate videos from a single frame and a sparse motion input. Our trained model can generate unseen realistic object-to-object interactions. Although our model has never been given the explicit segmentation and motion of each object in
the scene during training, it is able to implicitly separate their dynamics and extents. Key components in our method are the randomized conditioning scheme, the encoding of the input motion control, and the randomized and sparse sampling to
enable generalization to out of distribution but realistic correlations. Our model, which we call YODA, has therefore the ability to move objects without physically touching them.
Through extensive qualitative and quantitative evaluations on several datasets, we show that YODA is on par with or better than state of the art video generation prior work in terms of both controllability and video quality. For videos, visit our project website https://araachie.github.io/yoda.
