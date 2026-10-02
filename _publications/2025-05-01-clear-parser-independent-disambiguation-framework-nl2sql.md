---
title: "CLEAR: A Parser-Independent Disambiguation Framework for NL2SQL"
collection: publications
category: conferences
permalink: /publication/2025-clear-parser-independent-disambiguation-framework-nl2sql
excerpt: 'Meng Zhang（协助指导博士生）, Kexin Ma, Liyang Xu, Kedi Zhang, Yuanxi Peng, **Ruochun Jin***. **ICDE 2025**，CCF推荐数据库A类会议，**通讯作者**'
date: 2025-05-01
venue: 'ICDE 2025'
paperurl: 'https://ieeexplore.ieee.org/document/11113237'
citation: 'Meng Zhang, Kexin Ma, Liyang Xu, Kedi Zhang, Yuanxi Peng, Ruochun Jin*. &quot;CLEAR: A Parser-Independent Disambiguation Framework for NL2SQL.&quot; <i>ICDE 2025</i>.'
---

**作者 Authors**: Meng Zhang, Kexin Ma, Liyang Xu, Kedi Zhang, Yuanxi Peng, **Ruochun Jin***

**摘要 Abstract**: Parsing Natural Language to SQL (NL2SQL) helps users who are not proficient in databases to efficiently query desired data through natural language. Although existing NL2SQL parsers demonstrate good capabilities in processing clear queries, ambiguity still remains an unresolved issue which makes parsers produce unstable outputs that deviate from the user’s actual intent. To bridge the gap, this paper introduces the CLEAR framework, a systematic study of disambiguation for NL2SQL, including ambiguity detection, clarification, and reformulation, which benefits any NL2SQL parsers. Firstly, CLEAR employs a pipeline using Large Language Models (LLMs) and a series of rules to detect ambiguities, thus obtaining the “candidate mapping” for ambiguity representation. Secondly, an interactive selection module is employed to collect the clarification information from users through multiple-choice questions, thus obtaining the “selection mapping”. Finally, rewriting rules are employed to reformulate the question and schema, thus obtaining a clear input for parsers to generate clear SQLs. Furthermore, we construct CLAMBSQL, a novel benchmark for systematic evaluation for NL2SQL disambiguation, which contains fine-grained ambiguity and clarification annotations. Experiments on various datasets and baselines demonstrate that CLEAR can successfully address seven types of ambiguity. When parsers are integrated with CLEAR, the performance of ambiguous SQLs detection achieves a significant improvement of 30.5% on AMBROSIA in the AllFound metric and 21.1% on AmbiQT in the BothInTop-5 metric, the performance of ambiguity clarification achieves a remarkable improvement of 16.2% on CLAMBSQL in the CEX metric, and the performance of the general prediction achieves an increase of 1.6% in the EX metric and 7.7% in the CSR metric on BIRD. The CLEAR code and CLAMBSQL dataset are available at https://github.com/mengzhang18/CLEAR.
