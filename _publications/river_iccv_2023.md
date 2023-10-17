---
title: "Efficient Video Prediction via Sparsely Conditioned Flow Matching"
collection: publications
permalink: /publication/river_iccv_2023
date: 2023-10-02
venue: 'International Conference on Computer Vision'
citation: 'A. Davtyan, S. Sameni and P. Favaro. (2023). &quot;Efficient Video Prediction via Sparsely Conditioned Flow Matching.&quot; In <i>Proceedings of the International Conference on Computer Vision</i>.'
---

[[PDF]](https://arxiv.org/pdf/2211.14575.pdf) [[Project Page]](https://araachie.github.io/river/)

## Abstract

We introduce a novel generative model for video prediction based on latent flow matching, an efficient alternative to diffusion-based models. In contrast to prior work, we keep the high costs of modeling the past during training and inference at bay by conditioning only on a small random set of past frames at each integration step of the image generation process. Moreover, to enable the generation of high-resolution videos and to speed up the training, we work in the latent space of a pretrained VQGAN. Finally, we propose to approximate the initial condition of the flow ODE with the previous noisy frame. This allows to reduce the number of integration steps and hence, speed up the sampling at inference time. We call our model Random frame conditioned flow Integration for VidEo pRedition, or, in short, RIVER. We show that RIVER achieves superior or on par performance compared to prior work on common video prediction benchmarks, while requiring an order of magnitude fewer computational resources.
