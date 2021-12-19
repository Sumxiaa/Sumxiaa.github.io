---
title: "Oil production forecast models based on sliding window regression"
collection: publications
permalink: /publication/oil_jopsae_2020
date: 2020-09-20
venue: 'Journal of Petroleum Science and Engineering'
citation: 'A. Davtyan, A. Rodin, I. Muchnik and A. Romashkin. &quot;Oil production forecast models based on sliding window regression.&quot; In <i>Journal of Petroleum Science and Engineering, Volume 195, 2020, 107916, ISSN 0920-4105, https://doi.org/10.1016/j.petrol.2020.107916</i>.'
---

[[Paper]](https://doi.org/10.1016/j.petrol.2020.107916)

## Abstract

The article presents a method of statistical modeling and forecasting of oil production rate at a real field that has been in operation for a long time. Nowadays such fields form the basis of the oil production industry. The “aging” of oil production on such fields requires continuous change of the management of the oil production system. Therefore, production modeling and forecast must be dynamic, varying over time. Moreover the system for measuring production parameters, like production and injection series that are used to fit the proposed model, does not work regularly and has a large number of random gaps. So the development of our model starts with combination of interpolation and averaging procedures to produce a regular grid of data points. On such a regular grid, we construct the desired dynamic regression model using a machine learning method that we refer to as the sliding window regression. Our model predicts the total oil production rate for the next month taking into account some manually designed features of the oil field from the bounded history interval. For convenience, the features of the model are divided into four groups: integral, local, pressure and autoregressive. After prediction for the next month the history window moves one step forward and the model is retrained to fit the new data. Further we generalize the idea of sliding window to obtain a model with stable coefficient dynamics and ability for long-term forecast. In particular, we consider two approaches: introducing some regularization terms to the objective loss functional or weighing sample objects with weights decreasing in the past. The model is verified on data from a real oil field and shows good results in terms of relative error.
