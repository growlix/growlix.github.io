---
title: "Selectivity considered harmful: evaluating the causal impact of class selectivity in DNNs"
collection: publications
permalink:
date: 2021
venue: 'International Conference on Learning Representations (ICLR)'
paperurl: 'https://openreview.net/forum?id=8nl0k08uMi'
citation: <b>ML Leavitt</b>, AS Morcos
image: /images/publications-2021-iclr-selectivity-considered-harmful.png
---
<i>Accessible abstract:</i> Our ability to understand deep neural networks (DNNs) greatly lags behind our ability to achieve useful outcomes with them. One common set of methods for understanding DNNs focuses on the properties of individual neurons — for example, finding an individual neuron that activates for images of cats but not for other types of images. We call this preference for a specific image type “class selectivity.” Selectivity is widely used in part because it’s intuitive and easy-to-understand in human terms. We asked whether easy-to-interpret neurons are actually <i>necessary</i> for DNNs to function. We investigated this question through a new approach to manipulate class selectivity: When training a network to classify images, we not only instructed the network to improve its ability to classify images, we also added an incentive to decrease (or increase) the amount of class selectivity in its neurons (for ML folks: a regularizer).

We found that reducing class selectivity in DNNs can improve network performance, while increasing class selectivity has significant negative effect on performance. 
