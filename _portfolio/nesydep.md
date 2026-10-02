---
title: "NeSyDep：神经-符号数据依赖挖掘工具"
excerpt: "Neural-Symbolic Dependency discovery——快速挖掘函数依赖（FD）与条件函数依赖（CFD）等数据依赖的开源工具<br/><a href='https://github.com/ruochunjin/NeSyDep'>https://github.com/ruochunjin/NeSyDep</a>"
collection: portfolio
---

**NeSyDep**（**Ne**ural-**Sy**mbolic **Dep**endency discovery）是将我们论文背后的研究原型打磨而成的开源数据依赖挖掘工具，面向数据科学家与数据工程师，支持快速挖掘函数依赖（FD）、条件函数依赖（CFD）等数据依赖（更多依赖类型持续加入）。

GitHub 仓库：[https://github.com/ruochunjin/NeSyDep](https://github.com/ruochunjin/NeSyDep)

集成的研究原型
======
* **BSFD** — 贝叶斯网络结构学习引导的快速 FD 挖掘（ICDE 2026）
* **SCFDM** — Transformer 引导关系划分的快速 CFD 挖掘（VLDB 2027）
* **FastAFD** — 聚类与协方差分析加速的近似 FD 挖掘（ICDE 2024），宽表上最快，具有统计召回保证

技术架构
======
挖掘内核为 C++（通过 pybind11 暴露接口），编排、采样、相关性提取与评估为纯 Python。

安装与使用
======
```bash
pip install nesydep            # 核心功能（FD/CFD 挖掘 + 轻量相关性分析）
pip install "nesydep[all]"     # 全部功能
```

```python
import pandas as pd
import nesydep as nd

df = pd.read_csv("hospital_sample.csv")

# 一行代码完成 FD 挖掘
fds = nd.discover(df, algo="bsfd", support=2, confidence=0.95)
for fd in fds.fds:
    print(fd)   # 例如 [Zip] -> City, [Zip] -> State
```

同时提供命令行工具：`nesydep discover data.csv --algo bsfd -o fds.txt`
