---
title: "Adaptive Asynchronous Parallelization of Graph Algorithms"
collection: publications
category: manuscripts
permalink: /publication/2020-adaptive-asynchronous-parallelization-of-graph-algorithms
excerpt: 'Wenfei Fan, Ping Lu, Wenyuan Yu, Jingbo Xu, Qiang Yin, Xiaojian Luo, Jingren Zhou, **Ruochun Jin**. **ACM Trans. Database Syst. (TODS)** 45(2): 6:1-6:45 (2020)，CCF推荐数据库A类期刊，姓氏字母排序'
date: 2020-06-01
venue: 'ACM Transactions on Database Systems (TODS), 2020'
paperurl: 'https://dl.acm.org/doi/10.1145/3397491'
citation: 'Wenfei Fan, Ping Lu, Wenyuan Yu, Jingbo Xu, Qiang Yin, Xiaojian Luo, Jingren Zhou, Ruochun Jin. &quot;Adaptive Asynchronous Parallelization of Graph Algorithms.&quot; <i>ACM Trans. Database Syst.</i> 45(2): 6:1-6:45 (2020).'
---

**作者 Authors**: Wenfei Fan, Ping Lu, Wenyuan Yu, Jingbo Xu, Qiang Yin, Xiaojian Luo, Jingren Zhou, **Ruochun Jin**

**摘要 Abstract**: This article proposes an Adaptive Asynchronous Parallel (AAP) model for graph computations. As opposed to Bulk Synchronous Parallel (BSP) and Asynchronous Parallel (AP) models, AAP reduces both stragglers and stale computations by dynamically adjusting relative progress of workers. We show that BSP, AP, and Stale Synchronous Parallel model (SSP) are special cases of AAP. Better yet, AAP optimizes parallel processing by adaptively switching among these models at different stages of a single execution. Moreover, employing the programming model of GRAPE, AAP aims to parallelize existing sequential algorithms based on simultaneous fixpoint computation with partial and incremental evaluation. Under a monotone condition, AAP guarantees to converge at correct answers if the sequential algorithms are correct. Furthermore, we show that AAP can optimally simulate MapReduce, PRAM, BSP, AP, and SSP. Using real-life and synthetic graphs, we experimentally verify that AAP outperforms BSP, AP, and SSP for a variety of graph computations.
