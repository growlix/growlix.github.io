---
title: "Selectivity considered harmful: evaluating the causal impact of class selectivity in DNNs"
collection: publications
date: 2020-03-01
venue: 'arXiv'
paperurl: "https://openreview.net/forum?id=8nl0k08uMi"
citation: <b>ML Leavitt</b>, AS Morcos 
image: /images/publications-2021-03-selectivity-considered-harmful-image.png
---
To appear in <i>ICLR</i> (2021)\
Also appeared in <i>ICML Workshop on Human Interpretability in Machine Learning</i> (2020)

<i>Accessible abstract:</i> Our ability to interpret deep neural networks (DNNs) greatly lags behind our ability to achieve useful outcomes with them. One common set of methods for understanding DNNs focuses on the properties of individual neurons — for example, finding an individual neuron that activates for images of cats but not for other types of images. This preference for a specific image type is called “class selectivity”. However, it remains an open question whether DNNs actually need to learn class selectivity to function. We tackled this question through a new approach to manipulate class selectivity: When training a network to classify images, we not only instructed the network to improve its ability to classify images, we also added an incentive to decrease (or increase) the amount of class selectivity in its neurons. Surprisingly, we found strong evidence showing that DNNs can function well even if their neurons largely aren’t class selective. In contrast, we found that increasing class selectivity consistently caused networks to perform worse. These results indicate that class selectivity in individual units is neither sufficient nor strictly necessary, and can even impair DNN performance. They also encourage caution when focusing on the properties of single units to interpret DNN function.


