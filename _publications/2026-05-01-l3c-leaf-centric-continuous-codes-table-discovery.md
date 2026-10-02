---
title: "L³C: Leaf-Centric Continuous Codes for Natural Language-Driven Table Discovery"
collection: publications
category: conferences
permalink: /publication/2026-l3c-leaf-centric-continuous-codes-table-discovery
excerpt: 'Qiyuan Zhang（协助指导博士生）, **Ruochun Jin***, Jixin Zhang, Yuhua Tang, Xiang Zhao, Shixuan Liu. **ICDE 2026**，CCF推荐数据库A类会议，**共同一作**'
date: 2026-05-01
venue: 'ICDE 2026'
paperurl: 'https://ieeexplore.ieee.org/document/11629295'
citation: 'Qiyuan Zhang, Ruochun Jin*, Jixin Zhang, Yuhua Tang, Xiang Zhao, Shixuan Liu. &quot;L³C: Leaf-Centric Continuous Codes for Natural Language-Driven Table Discovery.&quot; <i>ICDE 2026</i>.'
---

**作者 Authors**: Qiyuan Zhang, **Ruochun Jin***, Jixin Zhang, Yuhua Tang, Xiang Zhao, Shixuan Liu

**摘要 Abstract**: Natural language (NL)-driven table discovery aims to retrieve relevant tables from massive repositories using intuitive user queries. While recent approaches leverage dense vector retrieval or discrete identifier generation, they either suffer from limited semantic expressiveness or rigid hierarchical constraints that hinder fine-grained discrimination among structurally similar tables. In this work, we propose L3C (Leaf-Centric Continuous Code), a novel differentiable indexing framework that represents each table as a continuous vector anchored to its semantic cluster center with a learnable local offset. Unlike prior methods that rely on fixed embeddings or autoregressive discrete IDs, L3C decouples global semantic organization from local table uniqueness: a hierarchical clustering tree over multi-view table representations defines leaf-level semantic neighborhoods, while each table learns a residual offset that captures its distinctive content within that neighborhood. During training, an encoder-decoder model learns to map NL queries directly to these continuous codes, enabling end-to-end optimization of both indexing structure and query-table alignment. At inference time, the model generates a continuous code that is efficiently matched against precomputed table codes via approximate nearest neighbor search—combining the flexibility of dense retrieval with the semantic coherence of hierarchical indexing. To support dynamic table ingestion, we further introduce a memory-efficient continual learning strategy that freezes base representations and only adapts local offsets for new tables, effectively mitigating catastrophic forgetting. Extensive experiments on three benchmarks show that L3C outperforms state-of-the-art methods by up to 6.5 points in P@1, while maintaining scalable inference and robustness under continual updates.
