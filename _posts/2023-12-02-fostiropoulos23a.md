---
title: 'ABLATOR: Robust Horizontal-Scaling of Machine Learning Ablation Experiments'
openreview: eBLV3i7PG1c
abstract: Understanding the efficacy of a method requires ablation experiments. Current
  Machine Learning (ML) workflows emphasize the vertical scaling of large models with
  paradigms such as ‘data-parallelism’ or ‘model-parallelism’. As a consequence, there
  is a lack of methods for horizontal scaling of multiple experimental trials. Horizontal
  scaling is labor intensive when different tools are used for different experiment
  stages, such as for hyper-parameter optimization, distributed execution, or the
  consolidation of artifacts. We identify that errors in earlier stages of experimentation
  propagate to the analysis. Based on our observations, experimental results, and
  the current literature, we provide recommendations on best practices to prevent
  errors. To reduce the effort required to perform an accurate analysis and address
  common errors when scaling the execution of multiple experiments, we introduce ABLATOR.
  Our framework uses a stateful experiment design paradigm that provides experiment
  persistence and is robust to errors. Our actionable analysis artifacts are automatically
  produced by the experiment state and reduce the time to evaluate a hypothesis. We
  evaluate ABLATOR with ablation studies on a Transformer model, ‘Tablator’, where
  we study the effect of 6 architectural components, 8 model hyperparameters, 3 training
  hyperparameters, and 4 dataset preprocessing methodologies on 11 tabular datasets.
  We performed the largest ablation experiment for tabular data on Transformer models
  to date, evaluating 2,337 models in total. Finally, we open source ABLATOR; \url{https://github.com/fostiropoulos/ablator}
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: fostiropoulos23a
month: 0
tex_title: 'ABLATOR: Robust Horizontal-Scaling of Machine Learning Ablation Experiments'
firstpage: 19/1
lastpage: 15
page: 19/1-15
order: 19
cycles: false
bibtex_author: Fostiropoulos, Iordanis and Itti, Laurent
author:
- given: Iordanis
  family: Fostiropoulos
- given: Laurent
  family: Itti
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
pdf: https://proceedings.mlr.press/v224/fostiropoulos23a/fostiropoulos23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
