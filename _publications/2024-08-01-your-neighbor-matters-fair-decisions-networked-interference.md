---
title: "Your Neighbor Matters: Towards Fair Decisions Under Networked Interference"
collection: publications
category: conferences
permalink: /publication/2024-your-neighbor-matters-fair-decisions-networked-interference
excerpt: 'Wenjing Yang, Haotian Wang, Haoxuan Li, Hao Zou, **Ruochun Jin**, Kun Kuang, Peng Cui. **KDD 2024**: 3829-3840，CCF推荐数据挖掘A类会议'
date: 2024-08-01
venue: 'KDD 2024'
paperurl: 'https://dl.acm.org/doi/10.1145/3637528.3671960'
citation: 'Wenjing Yang, Haotian Wang, Haoxuan Li, Hao Zou, Ruochun Jin, Kun Kuang, Peng Cui. &quot;Your Neighbor Matters: Towards Fair Decisions Under Networked Interference.&quot; <i>KDD 2024</i>: 3829-3840.'
---

**作者 Authors**: Wenjing Yang, Haotian Wang, Haoxuan Li, Hao Zou, **Ruochun Jin**, Kun Kuang, Peng Cui

**摘要 Abstract**: In the era of big data, decision-making in social networks may introduce bias due to interconnected individuals. For instance, in peer-to-peer loan platforms on the Web, considering an individual’s attributes along with those of their interconnected neighbors, including sensitive attributes, is vital for loan approval or rejection downstream. Unfortunately, conventional fairness approaches often assume independent individuals, overlooking the impact of one person’s sensitive attribute on others’ decisions. To fill this gap, we introduce "Interference-aware Fairness" (IAF) by defining two forms of discrimination as Self-Fairness (SF) and Peer-Fairness (PF), leveraging advances in interference analysis within causal inference. Specifically, SF and PF causally capture and distinguish discrimination stemming from an individual’s sensitive attributes (with fixed neighbors’ sensitive attributes) and from neighbors’ sensitive attributes (with fixed self’s sensitive attributes), separately. Hence, a network-informed decision model is fair only when SF and PF are satisfied simultaneously, as interventions in individuals’ sensitive attributes or those of their peers both yield equivalent outcomes. To achieve IAF, we develop a deep doubly robust framework to estimate and regularize SF and PF metrics for decision models. Extensive experiments on synthetic and real-world datasets validate our proposed concepts and methods.
