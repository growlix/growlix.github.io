---
title: "Linking average- and worst-case perturbation robustness via class selectivity and dimensionality"
collection: publications
date: 2020-07-17
venue: 'arXiv'
paperurl: "https://arxiv.org/abs/2010.07693"
citation: <b>ML Leavitt</b>, AS Morcos
image: /images/publications-2020-07-selectivity-robustness.png
---
Also appeared in <i>ICML Workshop on Uncertainty and Robustness in Deep Learning</i> (2020)\
Under review in an archival venue

**Featured on the Facebook AI Blog:** [Easy-to-interpret neurons may hinder learning in deep neural networks](https://ai.facebook.com/blog/easy-to-interpret-neurons-may-hinder-learning-in-deep-neural-networks/)

<i>Accessible abstract:</i> Deep neural networks (DNNs) deployed in the wild typically receive input data that aren’t quite as ideal as the benchmark datasets that most research gets conducted on in a lab environment. For example, consider the difference between identifying someone from a scanned passport photo vs. a photograph of a group of friends in a dimly-lit, chaotic bar. The noisiness of real-world data has motivated a lot of interest in understanding what makes DNNs robust to distorted inputs. Previous work of mine and Ari's found that reducing class selectivity can improve DNN performance on clean images (see the summary of <i>Selectivity considered harmful</i> below). We sought to extend this work: does class selectivity affect robustness to distorted images?

We found that decreased class selectivity makes DNNs more robust against naturalistic distortions such as blur and noise. In contrast, we found that decreasing class selectivity <i>decreases</i> a different kind of robustness: robustness to targeted attacks in which images are intentionally manipulated in order to fool the DNN (adversarial attacks). Interestingly, the causal relationship between selectivity and both kinds of robustness is bidirectional: methods that improve naturalistic robustness also reduce class selectivity, and methods that improve adversarial robustness also increase class selectivity. Our results demonstrate a novel link between naturalistic and adversarial robustness through class selectivity (and representational dimensionality, but I'll leave that part for the ML experts to read about in the paper).