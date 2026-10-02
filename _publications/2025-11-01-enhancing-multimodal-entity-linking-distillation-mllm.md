---
title: "Enhancing Multimodal Entity Linking via Distillation and Multimodal Large Language Models"
collection: publications
category: conferences
permalink: /publication/2025-enhancing-multimodal-entity-linking-distillation-mllm
excerpt: 'Jintao Huang（协助指导博士生）, Dong Wang, Shasha Li, Yuanxi Peng, **Ruochun Jin***. **CIKM 2025**，CCF推荐数据挖掘B类会议，**通讯作者**'
date: 2025-11-01
venue: 'CIKM 2025'
paperurl: 'https://dl.acm.org/doi/10.1145/3746252.3761053'
citation: 'Jintao Huang, Dong Wang, Shasha Li, Yuanxi Peng, Ruochun Jin*. &quot;Enhancing Multimodal Entity Linking via Distillation and Multimodal Large Language Models.&quot; <i>CIKM 2025</i>.'
---

**作者 Authors**: Jintao Huang, Dong Wang, Shasha Li, Yuanxi Peng, **Ruochun Jin***

**摘要 Abstract**: Multimodal entity linking (MEL) aims to link ambiguous multimodal mentions to their corresponding entities in a multimodal knowledge graph. Although many existing methods have been dedicated to exploring fine-grained intra- and cross-modal interactions between mentions and entities and have achieved good results, the discrepancies between the data distributions in training and real-world applications, as well as the noisy onehot labels, still impede the generalization of MEL models, which leads to poor performance when encountering unseen entities. Although general-purpose multimodal large language models (MLLMs) are powerful, it is costly and time-consuming to apply them directly to the MEL task. To address the above issues, we propose a Distillation-Enhanced framework for Multimodal Entity Linking (DEMEL). During training, DEMEL takes the best-trained MEL model so far as the teacher model, and distills the knowledge of the teacher model into the student model, i.e. the MEL model of the current iteration, when training it with onehot labels. This imposes regularization on the model, balances bias and variance in the training process, and improves the generalization ability of the MEL model. Moreover, DEMEL employs an MLLM to selectively rerank predictions for uncertain samples in the inference phase, improving accuracy while minimizing invocation costs. Extensive experiments on three public MEL datasets demonstrate that DEMEL outperforms state-of-the-art baselines, achieving 3.27% improvement with MLLM reranking for just 8.59% of test samples, and up to 4.8% H@1 enhancement in low-resource settings even without using MLLM reranking.
