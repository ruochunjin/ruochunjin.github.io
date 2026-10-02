---
title: "Linking Entities across Relations and Graphs"
collection: publications
category: manuscripts
permalink: /publication/2024-linking-entities-across-relations-and-graphs
excerpt: 'Wenfei Fan, Ping Lu, Kehan Pang, **Ruochun Jin***, Wenyuan Yu. **ACM Trans. Database Syst. (TODS)** 49(1): 2:1-2:50 (2024)，CCF推荐数据库A类期刊，**通讯作者**'
date: 2024-03-01
venue: 'ACM Transactions on Database Systems (TODS), 2024'
paperurl: 'https://dl.acm.org/doi/full/10.1145/3639363'
citation: 'Wenfei Fan, Ping Lu, Kehan Pang, Ruochun Jin*, Wenyuan Yu. &quot;Linking Entities across Relations and Graphs.&quot; <i>ACM Trans. Database Syst.</i> 49(1): 2:1-2:50 (2024).'
---

**作者 Authors**: Wenfei Fan, Ping Lu, Kehan Pang, **Ruochun Jin***, Wenyuan Yu

**摘要 Abstract**: This article proposes a notion of parametric simulation to link entities across a relational database D and a graph G. Taking functions and thresholds for measuring vertex closeness, path associations, and important properties as parameters, parametric simulation identifies tuples t in D and vertices v in G that refer to the same real-world entity, based on both topological and semantic matching. We develop machine learning methods to learn the parameter functions and thresholds. We show that parametric simulation is in quadratic-time by providing such an algorithm. Moreover, we develop an incremental algorithm for parametric simulation; we show that the incremental algorithm is bounded relative to its batch counterpart, i.e., it incurs the minimum cost for incrementalizing the batch algorithm. Putting these together, we develop HER, a parallel system to check whether (t, v) makes a match, find all vertex matches of t in G, and compute all matches across D and G, all in quadratic-time; moreover, HER supports incremental computation of these in response to updates to D and G. Using real-life and synthetic data, we empirically verify that HER is accurate with F-measure of 0.94 on average, and is able to scale with database D and graph G for both batch and incremental computations.
