---
layout: archive
title: ""
permalink: /research/
author_profile: true
---
My research interests lie broadly in online learning and optimization, and asymptotic analysis, with a particular emphasis on the application of these methods in the field of inventory and revenue management.


Research Directions
==============

Low-dimensional Heuristics Design for Operations Management
--------

Many supply chain and revenue management problems have increasingly complicated features, e.g., positive lead times, multi-echelon, multi-products, and fluctuated demand environment. Therefore, the optimal policies for these problems usually have a complex structure, which may make the policies hard to implement and result in customers’ strategic behavior. When the dimensions of these features are large, the optimal policies are even computationally intractable due to the notorious curse of dimensionality. In this direction, we investigate how to design low-dimensional heuristics that are decided by a few parameters, such as base-stock, $(s,S)$, and static pricing policies. We want the new heuristic to be both easy to implement in practice and have a good theoretical guarantee.

* **Shilin Yuan**, Jiameng Lyu, Jinxing Xie, Yuan Zhou. Asymptotic Optimality of Base-Stock Policies for Lost-Sales Inventory Systems with Stochastic Lead Times. Forthcoming at *Operations Research Letters*.

* **Shilin Yuan**, Jinxing Xie, Xiaobo Zhao, Xiuli Chao. Asymptotic Optimality of $(s,S)$ Policies for Perishable Inventory Systems with Fixed Ordering Costs. Work in Process.



Learning and Optimization of Structured Policies for Markov Decision Processes
--------
Many Markov decision processes are shown to have structured optimal policies or near-optimal low-dimensional heuristics as discussed above. However, existing studies mainly show the (near) optimal policy falls into certain policy families, but do not give algorithmic methods to search for the best one. In this direction, we investigate how to design new algorithms for optimizing structured policies for Markov decision processes. For example, base-stock policies and constant order policies in inventory control. We also try to provide new insights into classical data-driven methods, such as Stochastic Gradient Descent (SGD) and Sample Average Approximation (SAA).

* (Alphabetical) Jiameng Lyu, Jinxing Xie, **Shilin Yuan**, Yuan Zhou. A Minibatch-SGD-Based Learning Meta-Policy for Inventory Systems with Myopic Optimal Policy. Forthcoming at *Management Science*. [[SSRN]](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4390778)
* (Alphabetical) Xin Chen, Jiameng Lyu, **Shilin Yuan**, Yuan Zhou. Learning in Lost-Sales Inventory Systems with Stochastic Lead Times and Random Supplies. Under major revision at *Management Science*. [[SSRN]](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4671416) 
* (Alphabetical) Jiameng Lyu, **Shilin Yuan**, Bingkun Zhou, Yuan Zhou. Closing the Gaps: Optimality of Sample Average Approximation for Data-Driven Newsvendor Problems. Submitted. [[SSRN]](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4880063) [[arXiv]](http://arxiv.org/abs/2407.04900)
* (Alphabetical) Xin Chen, Jiameng Lyu, **Shilin Yuan**, Yuan Zhou. Nonstationary Sample Average Approximation with Applications in Inventory Management. Work in Process.


