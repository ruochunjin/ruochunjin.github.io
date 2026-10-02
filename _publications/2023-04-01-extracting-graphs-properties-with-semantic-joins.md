---
title: "Extracting Graphs Properties with Semantic Joins"
collection: publications
category: conferences
permalink: /publication/2023-extracting-graphs-properties-with-semantic-joins
excerpt: 'Yang Cao, Wenfei Fan, Wenzhi Fu, **Ruochun Jin***, Weijie Ou, Wenliang Yi. **ICDE 2023**: 2262-2275，CCF推荐数据库A类会议，姓氏字母排序、主要贡献者，**作为代表作收录入本人博士学位论文**'
date: 2023-04-01
venue: 'ICDE 2023'
paperurl: 'https://ieeexplore.ieee.org/document/10184864'
citation: 'Yang Cao, Wenfei Fan, Wenzhi Fu, Ruochun Jin*, Weijie Ou, Wenliang Yi. &quot;Extracting Graphs Properties with Semantic Joins.&quot; <i>ICDE 2023</i>: 2262-2275.'
---

**作者 Authors**: Yang Cao, Wenfei Fan, Wenzhi Fu, **Ruochun Jin***, Weijie Ou, Wenliang Yi

**摘要 Abstract**: This paper proposes an approach to querying a relational database D and a graph G taken together in SQL. We introduce a semantic extension of joins across D and G such that if a tuple t in D and a vertex v in G refer to the same real-world entity, then we join t and v to correlate their information and complement tuple t with additional properties of vertex v from the graph. Moreover, we extract hidden relationships between t and other entities by exploring paths from v. To support the semantic joins, we develop an extraction scheme based on LSTM, path clustering and ranking, to fetch important properties from graphs, and incrementally maintain the extracted data in response to updates. We also provide methods for implementing static joins when t is a tuple in D, dynamic joins when t comes from the intermediate result of a sub-query, and heuristic joins to strike a balance between the complexity and accuracy. Using real-life data and queries, we experimentally verify the effectiveness, scalability and efficiency of the methods.
