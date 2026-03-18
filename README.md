## Hey, I'm Yufeng 👋

Agent AI engineer at [Moonshot AI](https://www.moonshot.cn/) (Kimi), CS Master's student at HKU.

Previously competed in ACM-ICPC (silver medals, BUPT). These days I mostly think about how to make AI agents actually work in production.

### Projects

| Project | Stars | What it does |
|---------|:-----:|-------------|
| [MTSIR3-GAN](https://github.com/he-yufeng/MTSIR3-GAN) | 135+ | Adapting R3GAN (NeurIPS 2024) to multivariate time series imputation + adversarial refinement study |
| [FindJobs-Agent](https://github.com/he-yufeng/FindJobs-Agent) | 73+ | LLM-powered job toolkit — skill gap analysis, mock interviews, resume optimization |
| [DRL-MultiFactorTrading](https://github.com/he-yufeng/DRL-MultiFactorTrading) | 52+ | Deep RL trading strategies with Double DQN and multi-factor alpha signals |
| [Arxiv Paper Coding Agent](https://github.com/he-yufeng/Arxiv_Paper_Coding_Agent--HKU_COMP7103C_Data_mining_Assignment) | 31+ | Multi-LLM crew that reads a paper and produces a working implementation |
| [ContractGuard](https://github.com/he-yufeng/ContractGuard) | new | AI agent that reviews contracts for red flags before you sign |
| [TokenTracker](https://github.com/he-yufeng/TokenTracker) | new | Drop-in LLM cost tracker — change one import line, see where your money goes |
| [AgentProbe](https://github.com/he-yufeng/AgentProbe) | new | Pytest plugin for regression-testing AI agents — snapshot baselines, semantic comparison, mock LLMs |
| [PromptDiff](https://github.com/he-yufeng/PromptDiff) | new | Semantic diff for LLM prompts — compare prompt versions like git diff |
| [GitSense](https://github.com/he-yufeng/GitSense) | new | AI-powered open source contribution finder — tell it your skills, it finds issues |
| [RuleForge](https://github.com/he-yufeng/RuleForge) | new | Auto-generate AI assistant rules (CLAUDE.md, .cursorrules) from codebase analysis |
| [BatchLLM](https://github.com/he-yufeng/BatchLLM) | new | Batch LLM processing — CSV in, processed CSV out, with retries and cost tracking |

### Open Source Contributions

| Project | PR | What I Fixed |
|---------|:--:|-------------|
| [Mooncake](https://github.com/kvcache-ai/Mooncake) (5k★) | [#1629](https://github.com/kvcache-ai/Mooncake/pull/1629) | GB200 MNNVL EP hang — `cudaMalloc` → `cuMemCreate(FABRIC)` + `cuMemMap` for cross-node NVLink |
| [Mooncake](https://github.com/kvcache-ai/Mooncake) (5k★) | [#1626](https://github.com/kvcache-ai/Mooncake/pull/1626) | Silenced error log spam for non-memory replicas in metadata store |
| [Mooncake](https://github.com/kvcache-ai/Mooncake) (5k★) | [#1644](https://github.com/kvcache-ai/Mooncake/pull/1644) | MNNVL warmup hang — skip redundant handshake for fabric-connected nodes |
| [OpenClaw](https://github.com/openclaw/openclaw) | [#41271](https://github.com/openclaw/openclaw/pull/41271) | Log auth profile resolution failures instead of swallowing silently |
| [AstrBot](https://github.com/AstrBotDevs/AstrBot) (24k★) | [#6474](https://github.com/AstrBotDevs/AstrBot/pull/6474) | SQLite `database is locked` under concurrent writes — added busy timeout |
| [AstrBot](https://github.com/AstrBotDevs/AstrBot) (24k★) | [#6313](https://github.com/AstrBotDevs/AstrBot/pull/6313) | Null choices guard — OpenAI API returning `None` instead of empty list |
| [AstrBot](https://github.com/AstrBotDevs/AstrBot) (24k★) | [#6527](https://github.com/AstrBotDevs/AstrBot/pull/6527) | Fix LLM tool selection — rewrote ambiguous Upload/Download descriptions |
| [ClawTeam](https://github.com/HKUDS/ClawTeam) (200+★) | [#1](https://github.com/HKUDS/ClawTeam/pull/1) | First PR — 122 tests, CI, team templates, config bugfixes, task duration tracking |

### Tech

Python, C++, Go. Comfortable with Multi-agent system. I enjoy working at the intersection of systems and ML.

### Elsewhere

- LinkedIn: [yufenghe](https://www.linkedin.com/in/yufenghe)
- Location: Hong Kong

---

## 嘿，我是宇峰 👋

[Moonshot AI](https://www.moonshot.cn/)（Kimi）Agent AI 工程师，香港大学计算机硕士在读。

之前在北邮打 ACM-ICPC（银牌）。现在主要琢磨怎么让 AI Agent 在生产环境里真正跑起来。

### 项目

| 项目 | Stars | 简介 |
|------|:-----:|------|
| [MTSIR3-GAN](https://github.com/he-yufeng/MTSIR3-GAN) | 135+ | 将 R3GAN (NeurIPS 2024) 适配到多变量时序插补 + 对抗精炼实证研究 |
| [FindJobs-Agent](https://github.com/he-yufeng/FindJobs-Agent) | 73+ | LLM 求职工具箱 — 技能差距分析、模拟面试、简历优化 |
| [DRL-MultiFactorTrading](https://github.com/he-yufeng/DRL-MultiFactorTrading) | 52+ | 深度强化学习量化交易，Double DQN + 多因子 Alpha |
| [Arxiv Paper Coding Agent](https://github.com/he-yufeng/Arxiv_Paper_Coding_Agent--HKU_COMP7103C_Data_mining_Assignment) | 31+ | 多 LLM 协作 Agent，读论文自动生成可运行代码 |
| [ContractGuard](https://github.com/he-yufeng/ContractGuard) | new | AI 合同审查 Agent，签字前帮你找出霸王条款 |
| [TokenTracker](https://github.com/he-yufeng/TokenTracker) | new | LLM 开销追踪，改一行 import 就能用 |
| [AgentProbe](https://github.com/he-yufeng/AgentProbe) | new | AI Agent 回归测试 pytest 插件 — 快照基线、语义比较、Mock LLM |
| [PromptDiff](https://github.com/he-yufeng/PromptDiff) | new | LLM prompt 语义 diff 工具，像 git diff 一样对比 prompt 版本 |
| [GitSense](https://github.com/he-yufeng/GitSense) | new | AI 驱动的开源贡献发现器，输入技能自动找 issue |
| [RuleForge](https://github.com/he-yufeng/RuleForge) | new | 从代码库自动生成 AI 助手规则（CLAUDE.md、.cursorrules）|
| [BatchLLM](https://github.com/he-yufeng/BatchLLM) | new | LLM 批量处理 — CSV 进 CSV 出，自动重试 + 费用追踪 |

### 开源贡献

| 项目 | PR | 修了啥 |
|------|:--:|--------|
| [Mooncake](https://github.com/kvcache-ai/Mooncake) (5k★) | [#1629](https://github.com/kvcache-ai/Mooncake/pull/1629) | GB200 MNNVL EP hang — `cudaMalloc` → `cuMemCreate(FABRIC)` + `cuMemMap` 跨节点 NVLink 通信 |
| [Mooncake](https://github.com/kvcache-ai/Mooncake) (5k★) | [#1626](https://github.com/kvcache-ai/Mooncake/pull/1626) | 修复非内存副本的错误日志刷屏 |
| [Mooncake](https://github.com/kvcache-ai/Mooncake) (5k★) | [#1644](https://github.com/kvcache-ai/Mooncake/pull/1644) | MNNVL warmup hang — 跳过 fabric 连接节点的冗余握手 |
| [OpenClaw](https://github.com/openclaw/openclaw) | [#41271](https://github.com/openclaw/openclaw/pull/41271) | 认证配置解析失败时记录日志而非静默吞掉 |
| [AstrBot](https://github.com/AstrBotDevs/AstrBot) (24k★) | [#6474](https://github.com/AstrBotDevs/AstrBot/pull/6474) | 修复 SQLite 并发写入 `database is locked`，添加 busy timeout |
| [AstrBot](https://github.com/AstrBotDevs/AstrBot) (24k★) | [#6313](https://github.com/AstrBotDevs/AstrBot/pull/6313) | 修复 OpenAI API 返回 `None` choices 导致崩溃 |
| [AstrBot](https://github.com/AstrBotDevs/AstrBot) (24k★) | [#6527](https://github.com/AstrBotDevs/AstrBot/pull/6527) | 修复 LLM 工具选择 — 重写模糊的 Upload/Download 描述 |
| [ClawTeam](https://github.com/HKUDS/ClawTeam) (200+★) | [#1](https://github.com/HKUDS/ClawTeam/pull/1) | 首个 PR — 122 个测试、CI、团队模板、config 修复、任务耗时追踪 |

### 技术栈

Python, C++, Go。 最近在搞多智能体。喜欢在系统和 ML 的交叉地带干活。

### 联系

- LinkedIn: [yufenghe](https://www.linkedin.com/in/yufenghe)
- 坐标：香港
