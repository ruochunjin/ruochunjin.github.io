---
title: "HuFu 虎符：轻量级数据一致性校验工具"
excerpt: "Lightweight consistency checker——判断两段数据是否“相合”：查询与检索段落、记忆与记忆、陈述与文档<br/><a href='https://github.com/ruochunjin/hufu'>https://github.com/ruochunjin/hufu</a>"
collection: portfolio
---

> *虎符相合，方为可信。*

**HuFu（虎符）** 是轻量级一致性校验工具。向量相似度只能说明两段文本“相近”，HuFu 判定它们是否“一致”——给出可解释的证据链，并具有可证的多项式时间复杂度。符号结构（语言超图、超图模拟、质量规则）负责裁决，小型神经模型（嵌入、NLI）仅作为规则的可度量输入。

GitHub 仓库：[https://github.com/ruochunjin/hufu](https://github.com/ruochunjin/hufu)（Apache-2.0，PyPI 可安装，参考核心零依赖）

功能
======
* **RAG 检索后校验** — 位于检索与生成之间，与向量数据库无关；为每条检索文档标注 consistent / conflict 并给出证据
* **文档矛盾检测** — 文档内部陈述的星图规则：类型化值槽互换、数值不匹配（含单位换算）、角色反转、反义词对、极性翻转
* **向量记忆冲突检测与修剪** — CDR 式规则（同对象、相反动作/状态/取值），从检索判断推断冲突，并在证据/索引层修剪
* **训练数据离群点管理** — 按下游影响实测分类 good / bad / ugly，并提供修复族（KNN/RF 标签修复、值填补、删除）
* **统一质量规则语言** — 一套 JSON 规则模式（逻辑、NLI、相似度、数值/时序谓词），注册表可插拔

研究谱系
======
* **Catching Inconsistencies in Vector Similarity Retrieval**（SIGMOD 2027）—— 向量检索一致性
* **Detecting Contradictions Within and Across Documents**（SIGMOD 2027）—— 文档内/跨文档矛盾检测
* **Conflict-Aware Memory for Embodied Agents**（ACL 2026 Oral）—— 向量记忆冲突检测规则（CDR）
* **Outliers: The Good, the Bad and the Ugly**（SIGMOD 2026）—— 训练数据离群点管理（OMR）
