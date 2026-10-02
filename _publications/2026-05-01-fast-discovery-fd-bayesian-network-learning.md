---
title: "Fast Discovery of Functional Dependencies via Bayesian Network Learning"
collection: publications
category: conferences
permalink: /publication/2026-fast-discovery-fd-bayesian-network-learning
excerpt: 'Siyi Yang（协助指导博士生）, Shenglin Chen, Xi Wang, Yuhua Tang, **Ruochun Jin***. **ICDE 2026**，CCF推荐数据库A类会议，**通讯作者**。已集成至开源工具 [NeSyDep](https://github.com/ruochunjin/NeSyDep)'
date: 2026-05-01
venue: 'ICDE 2026'
paperurl: 'https://ieeexplore.ieee.org/document/11629445'
citation: 'Siyi Yang, Shenglin Chen, Xi Wang, Yuhua Tang, Ruochun Jin*. &quot;Fast Discovery of Functional Dependencies via Bayesian Network Learning.&quot; <i>ICDE 2026</i>.'
---

**作者 Authors**: Siyi Yang, Shenglin Chen, Xi Wang, Yuhua Tang, **Ruochun Jin***

**摘要 Abstract**: Functional dependencies (FDs) are fundamental to data quality and query optimization. However, discovering high-confidence FDs from large-scale, noisy real-life datasets remains challenging, especially for those with low-support which can be early pruned. In view of this challenge, we propose BSFD, a scalable and parallel framework that leverages Bayesian network (BN) structure learning to guide the discovery of meaningful FDs with low support and high confidence (FDσ,δs). We establish a numerical equivalence between FDs and parent-child relationships in BNs, which lays the statistical foundation of our approach. We have also proposed a stratified sampling strategy with a theoretical bound on structure correctness relative to the sampling ratio, which enables efficient BN learning with structural accuracy preserved. As for large datasets, BSFD vertically partitions the input relation into multiple smaller sub-tables using BN-derived correlated attribute sets, which significantly reduces the search space. Experiments on real-life and synthetic datasets demonstrate that BSFD achieves on average 490× and up to 7008× speedup over baseline methods while maintaining high discovery accuracy, with an average F1 score of 0.98.
