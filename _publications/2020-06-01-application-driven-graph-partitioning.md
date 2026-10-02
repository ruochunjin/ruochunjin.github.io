---
title: "Application Driven Graph Partitioning"
collection: publications
category: conferences
permalink: /publication/2020-application-driven-graph-partitioning
excerpt: 'Wenfei Fan, **Ruochun Jin**, Muyang Liu, Ping Lu, Xiaojian Luo, Ruiqi Xu, Qiang Yin, Wenyuan Yu, Jingren Zhou. **SIGMOD 2020**: 1765-1779，CCF推荐数据库A类会议，姓氏字母排序'
date: 2020-06-01
venue: 'SIGMOD 2020'
paperurl: 'https://dl.acm.org/doi/10.1145/3318464.3389745'
citation: 'Wenfei Fan, Ruochun Jin, Muyang Liu, Ping Lu, Xiaojian Luo, Ruiqi Xu, Qiang Yin, Wenyuan Yu, Jingren Zhou. &quot;Application Driven Graph Partitioning.&quot; <i>SIGMOD 2020</i>: 1765-1779.'
---

**作者 Authors**: Wenfei Fan, **Ruochun Jin**, Muyang Liu, Ping Lu, Xiaojian Luo, Ruiqi Xu, Qiang Yin, Wenyuan Yu, Jingren Zhou

**摘要 Abstract**: Graph partitioning is crucial to parallel computations on large graphs. The choice of partitioning strategies has strong impact on not only the performance of graph algorithms, but also the design of the algorithms. For an algorithm of our interest, what partitioning strategy fits it the best and improves its parallel execution? Is it possible to develop graph algorithms with partition transparency, such that the algorithms work under different partitions without changes? This paper aims to answer these questions. We propose an application-driven hybrid partitioning strategy that, given a graph algorithm A, learns a cost model for A as polynomial regression. We develop partitioners that given the learned cost model, refine an edge-cut or vertex-cut partition to a hybrid partition and reduce the parallel cost of A. Moreover, we identify a general condition under which graph-centric algorithms are partition transparent. We show that a number of graph algorithms can be made partition transparent. Using real-life and synthetic graphs, we experimentally verify that our partitioning strategy improves the performance of a variety of graph computations, up to 22.5 times.
