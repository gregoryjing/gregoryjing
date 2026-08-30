# Hi, I'm Gregory Jing👋

AI 应用开发工程师，关注 **LLM Application Engineering**，目前主要探索如何让大模型应用从“能跑”走向 **可靠执行、可量化评估和持续演进**。

我目前主要关注两个方向：

* **Agent Reliability** —— 多步骤 Agent 的任务规划与可靠执行，包括工作流编排、DAG 并行、状态管理、容错与断点恢复。
* **LLM Quality Engineering** —— LLM 应用输出质量的量化评估与持续验证，包括验收标准、Benchmark、基线管理、回归测试与能力退化检测。

业余时间将这些思考落地为实际项目，并围绕核心执行链路与评估流程构建测试体系。

---

## 🚀 Projects

### [AgentFlow](https://github.com/gregoryjing/agentflow)

**A reliable execution engine for multi-step AI agents.**

面向多步骤 Agent 的轻量级工作流执行引擎，关注 Agent 从“能够调用工具”到“能够稳定完成复杂任务”的执行可靠性。

* 四阶段 Agent Pipeline
* DAG 工作流编排与并行执行
* 双模型协作的任务规划
* Checkpoint 状态持久化与断点恢复
* 异常处理与执行容错
* **95 项自动化测试**覆盖核心执行链路

> **Focus:** Agent Orchestration · DAG Execution · State Management · Fault Tolerance · Checkpoint Recovery

---

### [llm-intel-kb](https://github.com/gregoryjing/llm-intel-kb)

**An engineering-oriented RAG knowledge base with retrieval evaluation and regression testing.**

面向实际应用场景的工程化 RAG 知识库，不仅关注“能否检索到答案”，也关注检索与生成能力是否能够被持续评估、验证和回归。

* Hybrid Retrieval：融合多种检索策略
* RAG Pipeline 工程化
* Retrieval / Generation Benchmark
* 基线结果记录与 Regression Testing
* 能力变化与性能退化检测

> **Focus:** RAG Engineering · Hybrid Retrieval · Evaluation · Benchmark · Regression TestingFocus: RAG Engineering · Hybrid Retrieval · Evaluation · Benchmark · Regression Testing

---

## 📚 Research

### Research on Decoding EEG Signals Based on Grey Wolf Optimization Algorithm for Multi-Feature Fusion

**Yujing Guo · Pengfei Ma**

Published at **CAICE 2025 — The 4th International Conference on Computer, Artificial Intelligence and Control Engineering**

[**DOI: 10.1145/3727648.3727818**](https://doi.org/10.1145/3727648.3727818)

This work investigates **motor imagery EEG signal decoding** using the BCI Competition IV 2a dataset. A multi-feature fusion framework is developed by combining **Discrete Wavelet Transform (DWT)**, **Autoregressive (AR) modeling**, and **Common Spatial Patterns (CSP)**, with **Grey Wolf Optimization (GWO)** applied for feature selection.

### Method

```text
EEG Signal
    │
    ├── DWT ──→ Time-Frequency Features
    │
    ├── AR  ──→ Temporal Features
    │
    └── CSP ──→ Spatial Features
              │
              ▼
        Feature Fusion
              │
              ▼
        GWO Feature Selection
              │
              ▼
        Classification
```

### Experimental Results

* **Dataset:** BCI Competition IV 2a
* **Subjects:** 9
* **Motor Imagery Classes:** Left Hand · Right Hand · Both Feet · Tongue
* **Sampling Rate:** 250 Hz
* **Core Methods:** DWT · AR · CSP · GWOCore Methods: DWT · AR · CSP · GWO
* **Accuracy:** **96.20%**
* **Precision:** **97.71%**
* **Recall:** **94.81%**

The experimental results demonstrate the effectiveness of combining complementary time-frequency, temporal, and spatial features, while GWO-based feature selection further improves the overall classification performance.

> **Focus:** EEG Signal Processing · Feature Fusion · Feature Selection · Machine Learning · Optimization

**Paper:** [ACM Digital Library](https://dl.acm.org/doi/10.1145/3727648.3727818) · [DOI](https://doi.org/10.1145/3727648.3727818)

---

## 🎯 What I'm Exploring

`Agent Runtime` · `Workflow Orchestration` · `RAG` · `LLM Evaluation` · `LLM Quality Engineering` · `AI Application Infrastructure`

希望持续探索一个问题：

> **How do we make LLM applications more reliable, measurable, and maintainable?**

---

### 💡 Engineering Philosophy

LLM 应用真正进入生产环境后，核心问题往往不只是：

> **Can it work?**

而是：

> **Can it work reliably?**
> **Can we measure its quality?**
> **Can we detect when it gets worse?**

我希望围绕这些问题持续构建和实践。
