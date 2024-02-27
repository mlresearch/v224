---
title: Balanced Mixture of Supernets for Learning the CNN Pooling Architecture
openreview: 8-8k3okjpY
abstract: Downsampling layers, including pooling and strided convolutions, are crucial
  components of the convolutional neural network architecture that determine both
  the granularity/scale of image feature analysis as well as the receptive field size
  of a given layer. To fully understand this problem we analyse the performance of
  models independently trained with each pooling configurations on CIFAR10, using
  a ResNet20 network and show that the position of the downsampling layers can highly
  influence the performance of a network and predefined downsampling configurations
  are not optimal. Network Architecture Search (NAS) might be used to optimize downsampling
  configurations as an hyperparameter. However, we find that common one-shot NAS based
  on a single SuperNet do not work for this problem. We argue that this is because
  a SuperNet trained for finding the optimal pooling configuration fully shares its
  parameters among all pooling configurations. This makes its training hard because
  learning some configurations can harm the performance of others. Therefore, we propose
  a balanced mixture of SuperNets that automatically associates pooling configurations
  to different weight models and helps to reduce the weight-sharing and interinfluence
  of pooling configurations on the SuperNet parameters. We evaluate our proposed approach
  on CIFAR10, CIFAR100, as well as Food101, and show that in all cases our model outperforms
  other approaches and improves over the default pooling configurations.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: roshtkhari23a
month: 0
tex_title: Balanced Mixture of Supernets for Learning the CNN Pooling Architecture
firstpage: 8/1
lastpage: 23
page: 8/1-23
order: 8
cycles: false
bibtex_author: Roshtkhari, Mehraveh Javan and Toews, Matthew and Pedersoli, Marco
author:
- given: Mehraveh Javan
  family: Roshtkhari
- given: Matthew
  family: Toews
- given: Marco
  family: Pedersoli
date: 2023-12-02
address:
container-title: Proceedings of the Second International Conference on Automated Machine
  Learning
volume: '224'
genre: inproceedings
issued:
  date-parts:
  - 2023
  - 12
  - 2
pdf: https://proceedings.mlr.press/v224/roshtkhari23a/roshtkhari23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
