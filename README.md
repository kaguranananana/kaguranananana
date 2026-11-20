# Hi, I'm anontokyo 👋

**AI Agent Engineering · Java Backend**

中国矿业大学（211）2028 届计算机本科生，国家奖学金获得者。关注 **AI Agent 可靠性、检索与评测**，也持续实践 **高并发后端、消息一致性与故障恢复**。

`Python` · `Java` · `Spring Boot` · `FastAPI` · `MySQL` · `Redis` · `RocketMQ` · `RAG`

## Featured Projects

### [Trivae — Group Conversation Intelligence](https://github.com/kaguranananana/Trivae)

面向高噪声群聊历史的智能检索与分析系统，让自然语言回答能够回溯到原始消息。

- **Agent & Retrieval**：基于 OpenAI Agents SDK，结合全文、语义、上下文和结构化查询工具，支持复杂问题的规划与多轮调查。
- **Reliability & Evaluation**：构建来源校验、执行 Trace、固定数据快照及对照评测链路，关注错误归因与可复现验证。
- **Stack**：Python · FastAPI · Vue 3 · SQLite FTS5 · sqlite-vec

[项目仓库](https://github.com/kaguranananana/Trivae) · [系统架构](https://github.com/kaguranananana/Trivae/blob/main/docs/architecture.md) · [评测方法](https://github.com/kaguranananana/Trivae/blob/main/docs/evaluation.md)

### [Lottery — Concurrent Lottery & Async Settlement](https://github.com/kaguranananana/lottery)

基于 Java / Spring Boot 的营销抽奖工程实践，重点研究并发库存控制、请求幂等、可靠异步结算与故障恢复。

- **Consistency**：Redis 原子预扣、MySQL 唯一账本与条件更新、RocketMQ 事务消息及失败补偿，处理重复请求和消息重投。
- **Performance**：针对约 43 万条历史订单的补偿空扫描，将平均耗时由 **248.87 ms 降至 6.15 ms**；8 桶库存方案在特定单机对照实验中减少约 **86%** 的 MySQL 行锁等待次数。
- **Stack**：Java · Spring Boot · MySQL · Redis · RocketMQ · Caffeine · JMeter

[项目仓库](https://github.com/kaguranananana/lottery) · [系统架构](https://github.com/kaguranananana/lottery/blob/main/docs/architecture.md) · [性能与验证](https://github.com/kaguranananana/lottery/blob/main/doc/performance/optimization-report.md)

> 性能数据来自仓库记录的本地测试场景，并非生产环境吞吐量或 SLA 承诺。

## Open Source Contributions

参与 **[OpenClaw](https://github.com/openclaw/openclaw)** 与 **[Raven](https://github.com/EverMind-AI/Raven)** 等开源项目，关注 Agent Runtime、上下文恢复与执行可靠性。部分已合并的修复：

- **[OpenClaw #185186](https://github.com/openclaw/openclaw/pull/185186)** — 修复纯媒体消息导致 Codex 会话上下文恢复失败的问题。
- **[OpenClaw #197035](https://github.com/openclaw/openclaw/pull/197035)** — 修复模型目录加载缓慢时图片未正确传入视觉模型的问题。
- **[Raven #1138](https://github.com/EverMind-AI/Raven/pull/1138)** — 为 Agent 异常报告中的不可信证据增加边界隔离与长度限制。

## Links

[个人博客](https://anontokyo114.top) · [简历仓库](https://github.com/kaguranananana/resume) · [更多项目](https://github.com/kaguranananana?tab=repositories)
