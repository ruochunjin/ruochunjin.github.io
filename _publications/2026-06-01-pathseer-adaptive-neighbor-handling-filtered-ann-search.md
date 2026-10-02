---
title: "PathSeer: Adaptive Neighbor Handling for Efficient Filtered ANN Search"
collection: publications
category: conferences
permalink: /publication/2026-pathseer-adaptive-neighbor-handling-filtered-ann-search
excerpt: 'Zhiyue Li（协助指导博士生）, Guangyan Zhang, **Ruochun Jin**, Bojun Li, Xiaoguang Ren, Wenjing Yang. **SIGMOD 2026** (Round 4)，CCF推荐数据库A类会议'
date: 2026-06-01
venue: 'SIGMOD 2026 (Round 4)'
paperurl: 'https://dl.acm.org/doi/10.1145/3802098'
citation: 'Zhiyue Li, Guangyan Zhang, Ruochun Jin, Bojun Li, Xiaoguang Ren, Wenjing Yang. &quot;PathSeer: Adaptive Neighbor Handling for Efficient Filtered ANN Search.&quot; <i>SIGMOD 2026</i> (Round 4).'
---

**作者 Authors**: Zhiyue Li, Guangyan Zhang, **Ruochun Jin**, Bojun Li, Xiaoguang Ren, Wenjing Yang

**摘要 Abstract**: Filtered approximate nearest neighbor (ANN) search over high-dimensional vectors and associated attributes is critical for recommendation systems and RAG-based LLMs. However, existing methods face performance bottlenecks under workloads of varying characteristics due to static and single neighbor-handling strategies—either computing distances before filtering or filtering before distance computation—which fail to adapt to diverse data and workload patterns. In this paper, we propose PathSeer, an approach that enables efficient filtered ANN search through dynamic and hybrid neighbor-handling strategies. PathSeer introduces three key techniques: (1) a fusion vector indexing scheme that supports two neighbor-handling strategies within a single index, (2) a dynamic neighbor traversal strategy that allows adjusting the ratios of different neighbor-handling strategies at each step of index traversal while preserving high search performance, and (3) a heuristic parameter tuning mechanism that adapts the ratios of neighbors employing different neighbor-handling strategies to workload characteristics. Evaluations on six workloads show that PathSeer delivers 1.17×–47.4× higher throughput for filtered ANN search compared to existing methods, without sacrificing recall.
