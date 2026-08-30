# Hi, I'm Gregory Jing

AI 应用开发工程师 / Agent 方向 | 2 年 AI 工程经验

---

## 我在做什么

把大模型能力变成**在跑的产品**——从需求拆解到上线交付，不只是调 API，而是设计执行引擎、建评测体系、做工具链。

## 个人项目

### [AgentFlow](https://github.com/gregoryjing/agentflow) — AI Agent 工作流与评测框架
独立设计的 Agent 执行引擎，实现四阶段管线（需求解析→任务规划→工具执行→基线回归验证）：
- DAG 依赖分层并行执行（ThreadPoolExecutor）
- Checkpoint 断点恢复（SQLite 持久化）
- 双模型协作规划（主模型生成计划 + 挑战模型审查反馈）
- 95 项单元测试全通过

### [llm-intel-kb](https://github.com/gregoryjing/llm-intel-kb) — 工程化 RAG 知识库
多源 LLM 情报聚合知识库，覆盖 10+ 技术信息源：
- 50 条金标准评测集（版本查询 / 多跳推理 / 负例拒绝）
- 评估门禁机制（检索命中率 + 关键词覆盖 + 来源匹配三维评分）
- 不达标自动告警，防止知识库退化

## 技术栈

| 领域 | 技能 |
|------|------|
| 大模型应用 | RAG 全流程 · Agent 执行引擎设计 · SFT/LoRA 微调 · Prompt/上下文工程 |
| 语言 | Python（主力）· JavaScript/HTML/CSS |
| 工具链 | Git · Docker · SQLite/PostgreSQL |
| AI 协作 | Cursor · Claude Code · TRAE · 多模型协作开发 |

## 联系方式

- GitHub: [@gregoryjing](https://github.com/gregoryjing)
- Email: gregoryjing@163.com

---

> 简历上的每一个数字，我都能讲出怎么测出来的。
