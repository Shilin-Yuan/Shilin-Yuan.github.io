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
<details open>
  <summary> Research Context & Motivation: </summary>
  Many supply chain and revenue management problems have increasingly complex features, e.g., positive lead times, multi-echelon, multi-product, and fluctuating demand environments. Therefore, the optimal policies for these problems usually have a complex structure, which may make them hard to implement and lead to customers’ strategic behavior. When the dimensions of these features are large, the optimal policies are even computationally intractable due to the notorious curse of dimensionality. In this direction, we investigate how to design low-dimensional heuristics that are decided by a few parameters, such as base-stock, $(s,S)$, and static pricing policies. We want the new heuristic to be both easy to implement in practice and to have a good theoretical guarantee.
</details>

<details open>
<summary> Related Projects: </summary>
  
<ul>
  <li>
    Asymptotic Optimality of Base-Stock Policies for Lost-Sales Inventory Systems with Stochastic Lead Times.
    <ul>
      <li><strong>Shilin Yuan</strong>, Jiameng Lyu, Jinxing Xie, Yuan Zhou.</li>
      <li><em>Operations Research Letters</em>. <a href="https://www.sciencedirect.com/science/article/abs/pii/S0167637724001329">[Journal Link]</a></li>
    </ul>
  </li>
  <li>
    Asymptotic Optimality of $(s,S)$ Policies for Perishable Inventory Systems with Fixed Ordering Costs.
    <ul>
      <li>Work in Process.</li>
    </ul>
  </li>
</ul>
</details>




Learning and Optimization of Structured Policies for Markov Decision Processes
--------

<details open>
  <summary> Research Context & Motivation: </summary>
  Many Markov decision processes are shown to have structured optimal policies or near-optimal low-dimensional heuristics as discussed above. However, existing studies mainly show the (near) optimal policy falls into certain policy families, but do not give algorithmic methods to search for the best one. In this direction, we investigate how to design new algorithms for optimizing structured policies for Markov decision processes. For example, base-stock policies and constant order policies in inventory control. We also try to provide new insights into classical data-driven methods, such as Stochastic Gradient Descent (SGD) and Sample Average Approximation (SAA).
</details>

<details open>
  <summary> Related Projects: </summary>
  
* **A Minibatch-SGD-Based Learning Meta-Policy for Inventory Systems with Myopic Optimal Policy.**
  - (Alphabetical) Jiameng Lyu, Jinxing Xie, <ins>Shilin Yuan</ins>, Yuan Zhou.
  - *Management Science*. [[Journal Link]](https://pubsonline.informs.org/doi/abs/10.1287/mnsc.2023.00920) [[SSRN]](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4390778)
* <ins>Learning in Lost-Sales Inventory Systems with Stochastic Lead Times and Random Supplies.</ins> 
  - (Alphabetical) Xin Chen, Jiameng Lyu, **Shilin Yuan**, Yuan Zhou.
  - Under second round major revision at *Management Science*. [[SSRN]](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4671416)
* Joint Dynamic Advertising and Pricing with Demand Learning. 
  - (Alphabetical) Junyi Liu, Qihang Sun, Jinxing Xie, **Shilin Yuan**.
  - Under major revision at *Production Operations Management*.
* Closing the Gaps: Optimality of Sample Average Approximation for Data-Driven Newsvendor Problems. 
  - (Alphabetical) Jiameng Lyu, **Shilin Yuan**, Bingkun Zhou, Yuan Zhou.
  - Under review. [[SSRN]](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4880063) [[arXiv]](http://arxiv.org/abs/2407.04900)
* Learning When to Restart: Nonstationary Newsvendor from Uncensored to Censored Demand.
  - (Alphabetic) Xin Chen, Jiameng Lyu, **Shilin Yuan**, Yuan Zhou.
  - Under review. [[SSRN]](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5519298) [[arXiv]](https://arxiv.org/abs/2509.18709)
</details>

