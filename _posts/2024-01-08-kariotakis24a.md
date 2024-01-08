---
title: 'Leveraging Sparse Input and Sparse Models: Efficient Distributed Learning
  in Resource-Constrained Environments'
openreview: D9ggc3l0wi
abstract: 'Optimizing for reduced computational and bandwidth resources enables model
  training in less-than-ideal environments and paves the way for practical and accessible
  AI solutions. This work is about the study and design of a system that exploits
  sparsity in the input layer and intermediate layers of a neural network. Further,
  the system gets trained and operates in a distributed manner. Focusing on image
  classification tasks, our system efficiently utilizes reduced portions of the input
  image data. By exploiting transfer learning techniques, it employs a pre-trained
  feature extractor, with the encoded representations being subsequently introduced
  into selected subnets of the system’s final classification module, adopting the
  Independent Subnetwork Training (IST) algorithm. This way, the input and subsequent
  feedforward layers are trained via sparse “actions”, where input and intermediate
  features are subsampled and propagated in the forward layers.  We conduct experiments
  on several benchmark datasets, including CIFAR-$10$, NWPU-RESISC$45$, and the Aerial
  Image dataset. The results consistently showcase appealing accuracy despite sparsity:
  it is surprising that, empirically, there are cases where fixed masks could potentially
  outperform random masks and that the model achieves comparable or even superior
  accuracy with only a fraction ($50%$ or less) of the original image, making it particularly
  relevant in bandwidth-constrained scenarios. This further highlights the robustness
  of learned features extracted by ViT, offering the potential for parsimonious image
  data representation with sparse models in distributed learning.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: kariotakis24a
month: 0
tex_title: 'Leveraging Sparse Input and Sparse Models: Efficient Distributed Learning
  in Resource-Constrained Environments'
firstpage: 554
lastpage: 569
page: 554-569
order: 554
cycles: false
bibtex_author: Kariotakis, Emmanouil and Tsagkatakis, Grigorios and Tsakalides, Panagiotis
  and Kyrillidis, Anastasios
author:
- given: Emmanouil
  family: Kariotakis
- given: Grigorios
  family: Tsagkatakis
- given: Panagiotis
  family: Tsakalides
- given: Anastasios
  family: Kyrillidis
date: 2024-01-08
address:
container-title: Conference on Parsimony and Learning
volume: '234'
genre: inproceedings
issued:
  date-parts:
  - 2024
  - 1
  - 8
pdf: https://proceedings.mlr.press/v234/kariotakis24a/kariotakis24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
