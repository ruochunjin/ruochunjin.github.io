---
title: "Making It Tractable to Catch Duplicates and Conflicts in Graphs"
collection: publications
category: conferences
permalink: /publication/2023-making-it-tractable-catch-duplicates-conflicts-graphs
excerpt: 'Wenfei Fan, Wenzhi Fu, **Ruochun Jin**, Muyang Liu, Ping Lu, Chao Tian. **Proc. ACM Manag. Data (SIGMOD)** 1(1): 86:1-86:28 (2023)，CCF推荐数据库A类会议，姓氏字母排序'
date: 2023-05-01
venue: 'Proceedings of the ACM on Management of Data (SIGMOD 2023)'
paperurl: 'https://dl.acm.org/doi/10.1145/3588940'
citation: 'Wenfei Fan, Wenzhi Fu, Ruochun Jin, Muyang Liu, Ping Lu, Chao Tian. &quot;Making It Tractable to Catch Duplicates and Conflicts in Graphs.&quot; <i>Proc. ACM Manag. Data</i> 1(1): 86:1-86:28 (2023).'
---

**作者 Authors**: Wenfei Fan, Wenzhi Fu, **Ruochun Jin**, Muyang Liu, Ping Lu, Chao Tian

**摘要 Abstract**: This paper proposes an approach for entity resolution (ER) and conflict resolution (CR) in large-scale graphs. It is based on a class of Graph Cleaning Rules (GCRs), which support the primitives of relational data cleaning rules, and may embed machine learning classifiers as predicates. As opposed to previous graph rules, GCRs are defined with a dual graph pattern to accommodate irregular structures of schemaless graphs, and adopt patterns of a star form to reduce the complexity. We show that the satisfiability, implication and validation problems are all in polynomial time (PTIME) for GCRs, as opposed to the intractability of these classical problems for previous graph dependencies. We develop a parallel algorithm to discover GCRs by combining the generations of patterns and predicates, and a parallel PTIME algorithm for “deep” ER and CR by recursively applying the mined GCRs. We show that these algorithms guarantee to reduce runtime when more processors are used. Using real-life and synthetic graphs, we experimentally verify that rule discovery and error detection with GCRs are substantially faster than with previous graph dependencies, with improved accuracy.
