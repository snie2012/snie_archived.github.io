---
layout: post
title: Deep Neural Network Interpretibility and Visualization
---

A venn diagram of the relationship between vis and interpreting deep learning:

![alt text](https://raw.githubusercontent.com/snie2012/snie2012.github.io/master/blog/assets/venn.png)

Deep learning interpretibility is a sub-area of deep learning. It focuses on understanding how deep models work, why they succeed or fail, in order to trust them in real applications, protect them from adversarial attack and discover more capable models. Visualization can be used to study interpretibility. For example, by studying networks' [activation patterns]((http://www.cs.rug.nl/~alext/PAPERS/VAST16/paper.pdf)) and [learned features](https://distill.pub/2017/feature-visualization/). These studies refer to *region 1* in the Venn diagram. Apart from visualization, different approaches, such as [local interpretable approximations](https://github.com/marcotcr/lime) and [hypothesis functions](http://sellam.me/assets/papers/sellam-sysML.pdf), are also effective at explainations. On the other hand, visualization usage is not restricted to interpretation. It is capable of [seeing a network's graph structure](https://idl.cs.washington.edu/files/2018-TensorFlowGraph-VAST.pdf) or [peeking into the training process to facilitate debugging](http://ieeexplore.ieee.org/document/8019879/). These work represent *region 2* in the diagram.

It is important to form a clear picture of interrelationship between these two areas, so one can steer a research direction more effectively. For example, as a visualization researcher, interpretibility is not the only aspect to study deep neural networks, network structure, gradient flow and debugging are all valuable venues to pursue.