---
title: "TableCritic: Refine Table Reasoning via Self-Criticism and Tool Library"
collection: publications
category: conferences
permalink: /publication/2025-tablecritic-refine-table-reasoning-self-criticism-tool-library
excerpt: '**Ruochun Jin**, Dong Wang, Xiyue Wang, Haoqi Zheng. **CogSci 2025**（第47届认知科学学会年会），**第一作者**。已集成至开源工具 [JiuJiuBiao 九九表](https://github.com/ruochunjin/jiujiubiao)'
date: 2025-07-30
venue: 'CogSci 2025'
citation: 'Ruochun Jin, Dong Wang, Xiyue Wang, Haoqi Zheng. &quot;TableCritic: Refine Table Reasoning via Self-Criticism and Tool Library.&quot; <i>Proceedings of the 47th Annual Meeting of the Cognitive Science Society (CogSci 2025)</i>.'
---

**作者 Authors**: **Ruochun Jin**, Dong Wang, Xiyue Wang, Haoqi Zheng

**摘要 Abstract**: The rapid development of large language models (LLMs) has spurred their applications to tabular data. Prior research has investigated prompt engineering and external tool integration (e.g., code interpreters) to enhance LLMs’ table comprehension, yet existing approaches struggle to generalize across diverse table-based reasoning tasks due to task-specific fixed workflows. Additionally, LLMs’ inherent limitations, including hallucination and unreliable reasoning, necessitate iterative refinement mechanisms for robust performance. Inspired by cognitive-inspired problem-solving strategies, where iterative reflection and tool augmentation improve decision-making, we propose TableCritic, a functionally grounded computational framework for adaptive table reasoning. Following the functional-structural model taxonomy, our framework operates at the algorithmic level, implementing a dynamic feedback loop: (1) LLM-driven self-critique evaluates intermediate outputs and (2) tool-guided error correction. This task-agnostic architecture achieves performance transparency through modular tool composition while avoiding neurobiological implementation constraints. Experiments show that TableCritic significantly improves accuracy and outperforms baselines across various table-based tasks.
