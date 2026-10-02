---
title: "TALON: A Multi-Agent Framework for Long-Table Exploration and Question Answering"
collection: publications
category: conferences
permalink: /publication/2025-talon-multi-agent-framework-long-table-qa
excerpt: '**Ruochun Jin**, Xiyue Wang（协助指导硕士生）, Dong Wang, Haoqi Zheng, Yunpeng Qi, Silin Yang, Meng Zhang. **EMNLP 2025**，CCF推荐人工智能B类会议、自然语言处理顶级会议，**第一作者**'
date: 2025-11-01
venue: 'EMNLP 2025'
paperurl: 'https://aclanthology.org/2025.emnlp-main.1393.pdf'
citation: 'Ruochun Jin, Xiyue Wang, Dong Wang, Haoqi Zheng, Yunpeng Qi, Silin Yang, Meng Zhang. &quot;TALON: A Multi-Agent Framework for Long-Table Exploration and Question Answering.&quot; <i>EMNLP 2025</i>.'
---

**作者 Authors**: **Ruochun Jin**, Xiyue Wang, Dong Wang, Haoqi Zheng, Yunpeng Qi, Silin Yang, Meng Zhang

**摘要 Abstract**: Table question answering (TQA) requires accurate retrieval and reasoning over tabular data. Existing approaches attempt to retrieve query-relevant content before leveraging large language models (LLMs) to reason over long tables. However, these methods often fail to accurately retrieve contextually relevant data which results in information loss, and suffer from excessive encoding overhead. In this paper, we propose TALON, a multi-agent framework designed for question answering over long tables. TALON features a planning agent that iteratively invokes a tool agent to access and manipulate tabular data based on intermediate feedback, which progressively collects necessary information for answer generation, while a critic agent ensures accuracy and efficiency in tool usage and planning. In order to comprehensively assess the effectiveness of TALON, we introduce two benchmarks derived from the WikiTableQuestion and BIRD-SQL datasets, which contain tables ranging from 50 to over 10,000 rows. Experiments demonstrate that TALON achieves average accuracy improvements of 7.5% and 12.0% across all language models, establishing a new state-of-the-art in long-table question answering. Our code is publicly available at: https://github.com/Wwestmoon/TALON.
