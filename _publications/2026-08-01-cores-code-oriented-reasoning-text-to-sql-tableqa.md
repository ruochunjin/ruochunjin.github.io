---
title: "CORES: Code-Oriented Reasoning for Complex Text-to-SQL and Generalizable TableQA"
collection: publications
category: conferences
permalink: /publication/2026-cores-code-oriented-reasoning-text-to-sql-tableqa
excerpt: 'Meng Zhang（协助指导博士生）, **Ruochun Jin**, Wenjing Yang, Haotian Wang, Liting Sun, Kun Hu, Silin Yang, Kedi Zhang, Yuanxi Peng. **ACL 2026 Findings**，CCF推荐人工智能A类会议Findings'
date: 2026-08-01
venue: 'Findings of ACL 2026'
paperurl: 'https://aclanthology.org/2026.findings-acl.237.pdf'
citation: 'Meng Zhang, Ruochun Jin, Wenjing Yang, Haotian Wang, Liting Sun, Kun Hu, Silin Yang, Kedi Zhang, Yuanxi Peng. &quot;CORES: Code-Oriented Reasoning for Complex Text-to-SQL and Generalizable TableQA.&quot; <i>Findings of ACL 2026</i>.'
---

**作者 Authors**: Meng Zhang, **Ruochun Jin**, Wenjing Yang, Haotian Wang, Liting Sun, Kun Hu, Silin Yang, Kedi Zhang, Yuanxi Peng

**摘要 Abstract**: Text-to-SQL aims to bridge the gap between human intent and relational databases. While LLMs have shown proficiency in generating simple SQL queries, they struggle with complex analytical tasks. Moreover, models fine-tuned on SQL generation often suffer from catastrophic forgetting, which lose the versatility of procedural reasoning and pertaining to generation constraints. Inspired by the usage of high-resource programming languages as LLM reasoning intermediaries, we propose CORES model, which leverages Python as a procedural reasoning pivot to enhance both complex SQL generation and tabular reasoning. It decomposes complex queries into Python reasoning traces before generating the final SQL, which bridges the gap between procedural reasoning and declarative expression. In order to internalize this reasoning capability, we fine-tune LLMs via GRPO with tailored process reward functions that mitigate the sparse feedback problem. We experimentally verify the effectiveness of CORES on six text-to-SQL benchmarks, where ours outperforms baselines by 6.44% on average, while maintains good capability on three tableQA benchmarks.
