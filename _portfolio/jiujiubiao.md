---
title: "JiuJiuBiao 九九表：表格与数据库的统一问答工具"
excerpt: "Unified question-answering toolkit for tables and databases——一条流水线覆盖消歧、求解、输出校验全链路<br/><a href='https://github.com/ruochunjin/jiujiubiao'>https://github.com/ruochunjin/jiujiubiao</a>"
collection: portfolio
---

**JiuJiuBiao（九九表）** 是面向表格与数据库的统一问答工具包。正如九九表随问随答，JiuJiuBiao 让您的数据"一张表，应答所有问题"：一条流水线覆盖完整链路，每个阶段均可插拔替换。

GitHub 仓库：[https://github.com/ruochunjin/jiujiubiao](https://github.com/ruochunjin/jiujiubiao)（Apache-2.0，PyPI 可安装）

工作链路
======
```
问题 + 表格/数据库
  → [1] 消歧（可选，CLEAR 式）：歧义检测、澄清、重写
  → [2] 求解 —— 两个可互换引擎：
        • Solver：ReAct 智能体 + 自一致性 + 工具注册表（长表、脏格式、数据库）
        • Refiner：初始化 → 自我批评 → 多工具精化 → 多工具一致性投票
  → [3] 输出校验：规范化、拒答检测、格式门控
```

数据库是一等公民：求解器通过 schema 工具自行落地，执行真实 SQL。支持任意 OpenAI 兼容端点（vLLM、Ollama、DeepSeek、OpenAI 等）及 Anthropic 端点，并提供离线 FakeLLM 便于开发测试。

公开可复现基准（100 条抽样）：WikiTableQuestions 准确率 **0.82**，TabFact **0.97**。

研究谱系
======
JiuJiuBiao 沉淀了课题组五篇经同行评审的论文成果：
* **CLEAR**（ICDE 2025）—— 解析器无关的 NL2SQL 消歧 → 阶段 [1]
* **TALON**（EMNLP 2025）—— 多智能体长表探索 → Solver 引擎
* **RAISR**（ICASSP 2026）—— 协作式数据库智能体、执行落地、输出校验 → 数据库工具与阶段 [3]
* **TableCritic**（CogSci 2025）—— 自我批评 + 工具库 → Refiner 引擎
* **CORES**（ACL 2026 Findings）—— 代码导向推理（Python 作为中间枢纽）→ `def()` 代码工具与训练侧过程奖励
