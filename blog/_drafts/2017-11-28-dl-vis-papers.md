---
layout: post
title: Recent Publications on Visualizing Deep Neural Networks
---

The visualization research community has published a number of papers on the topic of visualizing and understanding deep neural networks. This article provides an overview of these publications.

[LSTMVis](http://lstm.seas.harvard.edu) provides a pretty neat visualization tool to study the hidden states in RNNs. It visualizes the change of hidden states over time as parallel coordinates. Users can observe the shape of hidden states, select a range of inputs and a threshold on hidden state values as the formulation of a hypothesis. The tool then matches inputs with similar hidden states patterns to support refinement of hypothesis. External linguistic information can be overlaid on the matched inputs to validate hypothesis. This tool is a great exploration tool in the sense that it lets users to freely formulate, refine and validate hypothesis with minimum restriction. It is open sourced and hosted online, go and play!

[CNNVis](https://arxiv.org/abs/1604.07043) focuses on convolutional networks. It proposed a DAG formulation, a matrix packing algorithm and edge bundling techniques to effectively visualize large CNNs. It preserves the global structure of a CNN and provides feature and activation information in the hidden layers. [Demo](http://shixialiu.com/publications/cnnvis/demo/) is online. For those who are interested in feature visualization of image-based models, it is more thoroughly explored in [this publication](https://distill.pub/2017/feature-visualization/) on [Distill](https://distill.pub).

Visualizing the Hidden Activity of Artificial Neural Networks

These are all forms of [design study](http://ieeexplore.ieee.org/document/6327248/). The first differentiation of these work are the problems and tasks identified. Based on the identified problems and tasks, analytical and visual solutions are designed to solve them. 