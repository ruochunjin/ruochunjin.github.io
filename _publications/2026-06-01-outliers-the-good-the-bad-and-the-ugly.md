---
title: "Outliers: The Good, the Bad and the Ugly"
collection: publications
category: conferences
permalink: /publication/2026-outliers-the-good-the-bad-and-the-ugly
excerpt: 'Shenglin Chen（协助指导博士生）, Wenfei Fan, **Ruochun Jin***. **SIGMOD 2026** (Round 1)，CCF推荐数据库A类会议，姓氏字母排序，**通讯作者**'
date: 2026-06-01
venue: 'SIGMOD 2026 (Round 1)'
paperurl: 'https://dl.acm.org/doi/10.1145/3749177'
citation: 'Shenglin Chen, Wenfei Fan, Ruochun Jin*. &quot;Outliers: The Good, the Bad and the Ugly.&quot; <i>SIGMOD 2026</i> (Round 1).'
---

**作者 Authors**: Shenglin Chen, Wenfei Fan, **Ruochun Jin***

**摘要 Abstract**: This paper studies the impact of outliers in relational dataset D on the accuracy of ML classifiers M, when D is used to train and evaluate M. Outliers are data points that statistically deviate from the distribution of the majority. We distinguish good outliers, i.e., novel data, from bad ones, i.e., those introduced by errors. Moreover, we separate ugly ones in influential features from the other bad ones. We find that only the ugly ones have negative impact on M, while the good (resp. the other bad) ones have positive (resp. neglectable) impact. To mitigate the negative impact, we propose a class of rules, denoted by OMRs, to identify ugly outliers by embedding ML outlier detectors and statistical functions as predicates. We develop algorithms to (a) learn OMRs from real-life data, and (b) catch and fix ugly outliers using the learned OMRs, instead of removing tuples. Using real-life data, we empirically show that OMRs improve the accuracy of various classifiers by 7.2% on average, up to 34.8%.
