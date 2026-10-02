---
title: "Boosting Meaningful Dependency Mining with Clustering and Covariance Analysis"
collection: publications
category: conferences
permalink: /publication/2024-boosting-meaningful-dependency-mining-clustering-covariance
excerpt: 'Xi Wang（协助指导博士生）, **Ruochun Jin***, Wanrong Huang, Yuhua Tang. **ICDE 2024**: 639-652，CCF推荐数据库A类会议，**共同一作、通讯作者**。已集成至开源工具 [NeSyDep](https://github.com/ruochunjin/NeSyDep)'
date: 2024-05-01
venue: 'ICDE 2024'
paperurl: 'https://ieeexplore.ieee.org/document/10597728'
citation: 'Xi Wang, Ruochun Jin*, Wanrong Huang, Yuhua Tang. &quot;Boosting Meaningful Dependency Mining with Clustering and Covariance Analysis.&quot; <i>ICDE 2024</i>: 639-652.'
---

**作者 Authors**: Xi Wang, **Ruochun Jin***, Wanrong Huang, Yuhua Tang

**摘要 Abstract**: Functional dependencies (FDs) form a valuable ingredient for various data management tasks. However, existing methods can hardly discover practical and interpretable FDs, especially in large noisy real-life datasets. This paper studies the problem of discovering meaningful functional dependencies (FDms) that utilize support and error parameters to capture interesting dependencies in such datasets and proposes an efficient discovery algorithm called FDMε. In order to scale with large datasets, FDMε employs an efficient sampling method with accuracy guarantees to capture the differences between tuple pairs and to quantify the connection between support/error of dependencies on samples and those on the entire dataset. Moreover, it adopts a clustering-based correlated attributes extraction to divide the exponentially large search space into multiple small sub-spaces and proposes an easy-first traversal strategy with covariance-based guidance that quickly detects candidate dependencies and validates them. Additionally, we prove a covariance lower bound as an additional pruning criterion to reduce the search space. Extensive experiments on real-life and synthetic datasets demonstrate that FDMε is 14 times faster than existing discovery algorithms on average, up to 31 times, and scales to larger datasets with the least memory cost.
