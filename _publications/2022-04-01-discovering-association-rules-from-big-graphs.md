---
title: "Discovering Association Rules from Big Graphs"
collection: publications
category: conferences
permalink: /publication/2022-discovering-association-rules-from-big-graphs
excerpt: 'Wenfei Fan, Wenzhi Fu, **Ruochun Jin**, Ping Lu, Chao Tian. **Proc. VLDB Endow.** 15(7): 1479-1492 (2022)，CCF推荐数据库A类会议，姓氏字母排序、主要贡献者，**作为代表作收录入本人博士学位论文**'
date: 2022-04-01
venue: 'Proceedings of the VLDB Endowment (VLDB 2022)'
paperurl: 'https://www.vldb.org/pvldb/vol15/p1479-tian.pdf'
citation: 'Wenfei Fan, Wenzhi Fu, Ruochun Jin, Ping Lu, Chao Tian. &quot;Discovering Association Rules from Big Graphs.&quot; <i>Proc. VLDB Endow.</i> 15(7): 1479-1492 (2022).'
---

**作者 Authors**: Wenfei Fan, Wenzhi Fu, **Ruochun Jin**, Ping Lu, Chao Tian

**摘要 Abstract**: This paper tackles two challenges to discovery of graph rules. Existing discovery methods often (a) return an excessive number of rules, and (b) do not scale with large graphs given the intractability of the discovery problem. We propose an application-driven strategy to cut back rules and data that are irrelevant to users’ interests, by training a machine learning (ML) model to identify data pertaining to a given application. Moreover, we introduce a sampling method to reduce a big graph G to a set H of small sample graphs. Given expected support and recall bounds, the method is able to deduce samples in H and mine rules from H to satisfy the bounds in the entire G. As proof of concept, we develop an algorithm to discover Graph Association Rules (GARs), which are a combination of graph patterns and attribute dependencies, and may embed ML classifiers as predicates. We show that the algorithm is parallelly scalable, i.e., it guarantees to reduce runtime when more machines are used. We experimentally verify that the method is able to discover rules with recall above 91% when using sample ratio 10%, with speedup of 61 times.
