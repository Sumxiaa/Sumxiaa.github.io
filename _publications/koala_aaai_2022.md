---
title: "KOALA: A Kalman Optimization Algorithm with Loss Adaptivity"
collection: publications
permalink: /publication/koala_aaai_2022
date: 2022-02-22
venue: 'AAAI Conference on Artificial Intelligence 2022'
citation: 'A. Davtyan, S. Sameni, L. Cerkezi, G. Meishvili, A. Bielski and P. Favaro. &quot;KOALA: A Kalman Optimization Algorithm with Loss Adaptivity.&quot; In <i>AAAI 2022</i>.'
---

[[PDF]](https://arxiv.org/pdf/2107.03331.pdf)

## Abstract

Optimization is often cast as a deterministic problem, where the solution is found through some iterative procedure such as gradient descent. However, when training neural networks the loss function changes over (iteration) time due to the randomized selection of a subset of the samples. This randomization turns the optimization problem into a stochastic one. We propose to consider the loss as a noisy observation with respect to some reference optimum. This interpretation of the loss allows us to adopt Kalman filtering as an optimizer, as its recursive formulation is designed to estimate unknown parameters from noisy measurements. Moreover, we show that the Kalman Filter dynamical model for the evolution of the unknown parameters can be used to capture the gradient dynamics of advanced methods such as Momentum and Adam. We call this stochastic optimization method KOALA, which is short for Kalman Optimization Algorithm with Loss Adaptivity. KOALA is an easy to implement, scalable, and efficient method to train neural networks. We provide convergence analysis and show experimentally that it yields parameter estimates that are on par with or better than existing state of the art optimization algorithms across several neural network architectures and machine learning tasks, such as computer vision and language modeling.
