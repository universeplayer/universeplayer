## Hey, I'm Yufeng 👋

Agentic AI engineer at [Moonshot AI](https://www.moonshot.cn/) (Kimi). CS Master's at HKU. Ex ACM-ICPC silver medalist.

I build AI agents that work in production, and I fix bugs in the ones other people build.

### Writing

- [我花了一晚上读完 Claude Code 泄露的 51 万行源码](https://zhuanlan.zhihu.com/p/1898642958) — 1300+ upvotes on Zhihu

### Open Source Contributions (merged)

Highlights from 22 merged PRs across PyTorch, vLLM, Transformers, FlashInfer, Mooncake and more:

| Project | PR | What I Fixed |
|---------|:--:|-------------|
| [Mooncake](https://github.com/kvcache-ai/Mooncake) (5k★) | [#1629](https://github.com/kvcache-ai/Mooncake/pull/1629) | GB200 MNNVL EP hang: `cudaMalloc` → `cuMemCreate(FABRIC)` + `cuMemMap` for cross-node NVLink |
| [Mooncake](https://github.com/kvcache-ai/Mooncake) (5k★) | [#1728](https://github.com/kvcache-ai/Mooncake/pull/1728) | Hard pin for eviction-protected objects: model weights never get evicted |
| [Mooncake](https://github.com/kvcache-ai/Mooncake) (5k★) | [#1644](https://github.com/kvcache-ai/Mooncake/pull/1644) | MNNVL warmup hang: skip redundant handshake for fabric-connected nodes |
| [vLLM](https://github.com/vllm-project/vllm) (50k★) | [#37884](https://github.com/vllm-project/vllm/pull/37884) | RoBERTa position_ids overflow on CUDA graph padding, BGE-M3 crash after ~4k requests |
| [vLLM](https://github.com/vllm-project/vllm) (50k★) | [#37301](https://github.com/vllm-project/vllm/pull/37301) | Base64 JPEG video frames returning empty metadata |
| [Transformers](https://github.com/huggingface/transformers) (145k★) | [#44710](https://github.com/huggingface/transformers/pull/44710) | `AutoProcessor.from_pretrained` silently dropping hub kwargs (`revision`, `token`) |
| [FlashInfer](https://github.com/flashinfer-ai/flashinfer) (3k★) | [#2756](https://github.com/flashinfer-ai/flashinfer/pull/2756) | Autotuner crash when input tensor is `None` |
| [AstrBot](https://github.com/AstrBotDevs/AstrBot) (24k★) | 8 PRs | SQLite locking, multimodal token counting, SSE heartbeat, context truncation, and more |
| [ClawTeam](https://github.com/HKUDS/ClawTeam) (1.9k★) | 5 PRs | First contributor: CI + 122 tests, Gemini/Kimi CLI support, snapshot/restore, pluggable TaskStore |
| [LightRAG](https://github.com/HKUDS/LightRAG) (29k★) | [#2796](https://github.com/HKUDS/LightRAG/pull/2796) | Fix `None` file_path propagating as `unknown_source` |

Plus 30+ open PRs in PyTorch, Triton, SGLang, vLLM, Binance Skills Hub, and others.

### Projects

| Project | Stars | What it does |
|---------|:-----:|-------------|
| [MTSIR3-GAN](https://github.com/he-yufeng/MTSIR3-GAN) | 135+ | Adapting R3GAN (NeurIPS 2024) to multivariate time series imputation |
| [FindJobs-Agent](https://github.com/he-yufeng/FindJobs-Agent) | 84+ | LLM-powered job toolkit: skill gap analysis, mock interviews, resume optimization |
| [DRL-MultiFactorTrading](https://github.com/he-yufeng/DRL-MultiFactorTrading) | 61+ | Deep RL trading with Double DQN and multi-factor alpha signals |
| [Arxiv Paper Coding Agent](https://github.com/he-yufeng/Arxiv_Paper_Coding_Agent--HKU_COMP7103C_Data_mining_Assignment) | 31+ | Multi-LLM crew that reads a paper and produces a working implementation |
| [ContractGuard](https://github.com/he-yufeng/ContractGuard) | new | AI agent that reviews contracts for red flags before you sign |
| [TokenTracker](https://github.com/he-yufeng/TokenTracker) | new | Drop-in LLM cost tracker, change one import line |
| [AgentProbe](https://github.com/he-yufeng/AgentProbe) | new | Pytest plugin for regression-testing AI agents |

### Tech

Python, C++, Go. Building at the intersection of systems and ML.

### Elsewhere

- LinkedIn: [yufenghe](https://www.linkedin.com/in/yufenghe)
- Zhihu: [何宇峰](https://www.zhihu.com/people/he-yufeng)
- Location: Hong Kong

---

## 嘿，我是宇峰 👋

[Moonshot AI](https://www.moonshot.cn/)（Kimi）Agentic AI 工程师，港大 CS 硕士在读，ACM-ICPC 银牌。

造能用的 AI Agent，也修别人造的 AI Agent 的 bug。

### 文章

- [我花了一晚上读完 Claude Code 泄露的 51 万行源码](https://zhuanlan.zhihu.com/p/1898642958) — 知乎 1300+ 赞同

### 开源贡献（已合并）

22 个已合并 PR，涉及 PyTorch、vLLM、Transformers、FlashInfer、Mooncake 等项目。精选：

| 项目 | PR | 修了啥 |
|------|:--:|--------|
| [Mooncake](https://github.com/kvcache-ai/Mooncake) (5k★) | [#1629](https://github.com/kvcache-ai/Mooncake/pull/1629) | GB200 MNNVL EP hang: `cudaMalloc` → `cuMemCreate(FABRIC)` + `cuMemMap` 跨节点 NVLink |
| [Mooncake](https://github.com/kvcache-ai/Mooncake) (5k★) | [#1728](https://github.com/kvcache-ai/Mooncake/pull/1728) | Hard pin 驱逐保护: 模型权重永不被驱逐 |
| [Mooncake](https://github.com/kvcache-ai/Mooncake) (5k★) | [#1644](https://github.com/kvcache-ai/Mooncake/pull/1644) | MNNVL warmup hang: 跳过 fabric 节点冗余握手 |
| [vLLM](https://github.com/vllm-project/vllm) (50k★) | [#37884](https://github.com/vllm-project/vllm/pull/37884) | RoBERTa position_ids 溢出, BGE-M3 约 4000 请求后崩溃 |
| [vLLM](https://github.com/vllm-project/vllm) (50k★) | [#37301](https://github.com/vllm-project/vllm/pull/37301) | base64 JPEG 视频帧返回空 metadata |
| [Transformers](https://github.com/huggingface/transformers) (145k★) | [#44710](https://github.com/huggingface/transformers/pull/44710) | `AutoProcessor.from_pretrained` 静默丢弃 hub kwargs |
| [FlashInfer](https://github.com/flashinfer-ai/flashinfer) (3k★) | [#2756](https://github.com/flashinfer-ai/flashinfer/pull/2756) | autotuner 输入 tensor 为 None 时崩溃 |
| [AstrBot](https://github.com/AstrBotDevs/AstrBot) (24k★) | 8 PRs | SQLite 并发锁、多模态 token 计数、SSE 心跳、上下文截断等 |
| [ClawTeam](https://github.com/HKUDS/ClawTeam) (1.9k★) | 5 PRs | 首位贡献者: CI + 122 测试、Gemini/Kimi CLI 支持、快照恢复、可插拔 TaskStore |
| [LightRAG](https://github.com/HKUDS/LightRAG) (29k★) | [#2796](https://github.com/HKUDS/LightRAG/pull/2796) | 修复 `None` file_path 传播为 `unknown_source` |

另有 30+ 个 open PR 在 PyTorch、Triton、SGLang、vLLM、Binance Skills Hub 等项目中。

### 项目

| 项目 | Stars | 简介 |
|------|:-----:|------|
| [MTSIR3-GAN](https://github.com/he-yufeng/MTSIR3-GAN) | 135+ | 将 R3GAN (NeurIPS 2024) 适配到多变量时序插补 |
| [FindJobs-Agent](https://github.com/he-yufeng/FindJobs-Agent) | 84+ | LLM 求职工具箱：技能差距分析、模拟面试、简历优化 |
| [DRL-MultiFactorTrading](https://github.com/he-yufeng/DRL-MultiFactorTrading) | 61+ | 深度 RL 量化交易, Double DQN + 多因子 Alpha |
| [Arxiv Paper Coding Agent](https://github.com/he-yufeng/Arxiv_Paper_Coding_Agent--HKU_COMP7103C_Data_mining_Assignment) | 31+ | 多 LLM 协作 Agent，读论文自动生成可运行代码 |
| [ContractGuard](https://github.com/he-yufeng/ContractGuard) | new | AI 合同审查 Agent |
| [TokenTracker](https://github.com/he-yufeng/TokenTracker) | new | LLM 开销追踪，改一行 import 就能用 |
| [AgentProbe](https://github.com/he-yufeng/AgentProbe) | new | AI Agent 回归测试 pytest 插件 |

### 技术栈

Python, C++, Go。在系统和 ML 的交叉地带干活。

### 联系

- LinkedIn: [yufenghe](https://www.linkedin.com/in/yufenghe)
- 知乎: [何宇峰](https://www.zhihu.com/people/he-yufeng)
- 坐标：香港
