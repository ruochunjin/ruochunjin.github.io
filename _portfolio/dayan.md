---
title: "DaYan 大衍：大模型推理过程的数据化建模与增强工具"
excerpt: "Modeling, evaluating, and enhancing LLM reasoning as data——把推理过程变成结构化数据（思维图）再分析<br/><a href='https://github.com/ruochunjin/dayan'>https://github.com/ruochunjin/dayan</a>"
collection: portfolio
---

> *大衍之数五十，其用四十有九。*

**DaYan（大衍）** 将大模型的推理过程建模为数据：标准评测只看最终答案，DaYan 回答模型“如何”推理——并把分析结果反馈为改进。通过 `@analysis` 插桩（基于 sys.settrace，无需改动源码），程序轨迹被转化为**思维图（Thought Graph）**：节点是 LLM 输出的“思维”，边是数据依赖。

GitHub 仓库：[https://github.com/ruochunjin/dayan](https://github.com/ruochunjin/dayan)（Apache-2.0，核心零依赖）

功能
======
* **推理插桩与思维图构建** — 程序轨迹 → 数据流图 → 思维图
* **过程评测** — 准确率之外的 5 个过程指标（推理效率、逐步一致性等）
* **模式挖掘** — 成功 vs. 失败轨迹的频繁思维模式对比挖掘
* **推理增强** — 挖掘出的模式可转化为提示规则或可验证的 RL 过程奖励
* **符号验证的数据增强**（`dayan.augment`，Logical DA）— LLM 生成样本的标签经 Z3 / Prover9 / 规则 / CSP 求解器验证后才进入训练集

研究谱系
======
* **Thought Mining for Large Language Model Reasoning**（VLDB 2027）—— 思维图数据模型、五个过程指标与两种增强策略
* **Logical DA**（ACL 2025 Findings）—— 带符号标签验证的多智能体数据增强
