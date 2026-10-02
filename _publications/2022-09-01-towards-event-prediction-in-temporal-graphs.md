---
title: "Towards Event Prediction in Temporal Graphs"
collection: publications
category: conferences
permalink: /publication/2022-towards-event-prediction-in-temporal-graphs
excerpt: 'Wenfei Fan, **Ruochun Jin**, Ping Lu, Chao Tian, Ruiqi Xu. **Proc. VLDB Endow.** 15(9): 1861-1874 (2022)，CCF推荐数据库A类会议，姓氏字母排序、主要贡献者，**作为代表作收录入本人博士学位论文**'
date: 2022-09-01
venue: 'Proceedings of the VLDB Endowment (VLDB 2022)'
paperurl: 'https://www.vldb.org/pvldb/vol15/p1861-tian.pdf'
citation: 'Wenfei Fan, Ruochun Jin, Ping Lu, Chao Tian, Ruiqi Xu. &quot;Towards Event Prediction in Temporal Graphs.&quot; <i>Proc. VLDB Endow.</i> 15(9): 1861-1874 (2022).'
---

**作者 Authors**: Wenfei Fan, **Ruochun Jin**, Ping Lu, Chao Tian, Ruiqi Xu

**摘要 Abstract**: This paper proposes a class of temporal association rules, denoted by TACOs, for event prediction. As opposed to previous graph rules, TACOs monitor updates to graphs, and can be used to capture temporal interests in recommendation and catch frauds in response to behavior changes, among other things. TACOs are defined on temporal graphs in terms of change patterns and (temporal) conditions, and may carry machine learning (ML) predicates for temporal event prediction. We settle the complexity of reasoning about TACOs, including their satisfiability, implication and prediction problems. We develop a system, referred to as TASTE. TASTE discovers TACOs by iteratively training a rule creator based on generative ML models in a creator-critic framework. Moreover, it predicts events by applying the discovered TACOs. Using real-life and synthetic datasets, we experimentally verify that TASTE is on average 31.4 times faster than conventional data mining methods in TACO discovery, and it improves the accuracy of state-of-the-art event prediction models by 23.4%.
