---
title: "Capturing Associations in Graphs"
collection: publications
category: conferences
permalink: /publication/2020-capturing-associations-in-graphs
excerpt: 'Wenfei Fan, **Ruochun Jin**, Muyang Liu, Ping Lu, Chao Tian, Jingren Zhou. **Proc. VLDB Endow.** 13(11): 1863-1876 (2020)，CCF推荐数据库A类会议，姓氏字母排序、主要贡献者，**作为代表作收录入本人博士学位论文**'
date: 2020-08-01
venue: 'Proceedings of the VLDB Endowment (VLDB 2020)'
paperurl: 'https://www.vldb.org/pvldb/vol13/p1863-fan.pdf'
citation: 'Wenfei Fan, Ruochun Jin, Muyang Liu, Ping Lu, Chao Tian, Jingren Zhou. &quot;Capturing Associations in Graphs.&quot; <i>Proc. VLDB Endow.</i> 13(11): 1863-1876 (2020).'
---

**作者 Authors**: Wenfei Fan, **Ruochun Jin**, Muyang Liu, Ping Lu, Chao Tian, Jingren Zhou

**摘要 Abstract**: This paper proposes a class of graph association rules, denoted by GARs, to specify regularities between entities in graphs. A GAR is a combination of a graph pattern and a dependency; it may take as predicates ML (machine learning) classifiers for link prediction. We show that GARs help us catch incomplete information in schemaless graphs, predict links in social graphs, identify potential customers in digital marketing, and extend graph functional dependencies (GFDs) to capture both missing links and inconsistencies. We formalize association deduction with GARs in terms of the chase, and prove its Church-Rosser property. We show that the satisfiability, implication and association deduction problems for GARs are coNP-complete, NP-complete and NP-complete, respectively, retaining the same complexity bounds as their GFD counterparts, despite the increased expressive power of GARs. The incremental deduction problem is DP-complete for GARs versus coNP-complete for GFDs. In addition, we provide parallel algorithms for association deduction and incremental deduction. Using real-life and synthetic graphs, we experimentally verify the effectiveness, scalability and efficiency of the parallel algorithms.
