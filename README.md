## Hey, I'm Yufeng He 👋

Agentic AI Researcher @ [Moonshot AI](https://www.moonshot.cn/) (Kimi) | MS CS @ HKU | Champion, Shanghai Global AI Contest | 3x ACM-ICPC Silver Medalist | Former Intern @ Baidu, Maimai, Kuaishou

### Projects

| Project | Stars | What it does |
|---------|:-----:|-------------|
| [CoreCoder](https://github.com/he-yufeng/CoreCoder) | 345+ | 512K lines of Claude Code → 1,400 lines of Python. Every key architectural pattern, runnable. Any LLM. 7 architecture deep-dive articles. |
| [AnyCoder](https://github.com/he-yufeng/AnyCoder) | new | AI coding agent CLI supporting 100+ LLMs via litellm. ~1,450 lines Python, dangerous command blocking, parallel tool execution, session persistence. |
| [FindJobs-Agent](https://github.com/he-yufeng/FindJobs-Agent) | 102+ | LLM-powered job toolkit: skill gap analysis, mock interviews, resume optimization |
| [MTSIR3-GAN](https://github.com/he-yufeng/MTSIR3-GAN) | 135+ | Adapting R3GAN (NeurIPS 2024) to multivariate time series imputation + adversarial refinement study |
| [DRL-MultiFactorTrading](https://github.com/he-yufeng/DRL-MultiFactorTrading) | 70+ | Deep RL trading strategies with Double DQN and multi-factor alpha signals |
| [Arxiv Paper Coding Agent](https://github.com/he-yufeng/Arxiv_Paper_Coding_Agent--HKU_COMP7103C_Data_mining_Assignment) | 36+ | Multi-LLM crew that reads a paper and produces a working implementation |
| [ContractGuard](https://github.com/he-yufeng/ContractGuard) | 49+ | AI agent that reviews contracts for red flags before you sign |
| [AgentProbe](https://github.com/he-yufeng/AgentProbe) | 33+ | Pytest plugin for regression-testing AI agents: snapshot baselines, semantic comparison, mock LLMs |
| [PromptDiff](https://github.com/he-yufeng/PromptDiff) | 25+ | Semantic diff for LLM prompts, compare prompt versions like git diff |
| [TokenTracker](https://github.com/he-yufeng/TokenTracker) | 14+ | Drop-in LLM cost tracker, change one import line, see where your money goes |
| [GitSense](https://github.com/he-yufeng/GitSense) | 13+ | AI-powered open source contribution finder, tell it your skills, it finds issues |
| [RuleForge](https://github.com/he-yufeng/RuleForge) | 11+ | Auto-generate AI assistant rules (CLAUDE.md, .cursorrules) from codebase analysis |
| [BatchLLM](https://github.com/he-yufeng/BatchLLM) | 8+ | Batch LLM processing: CSV in, processed CSV out, with retries and cost tracking |

### Open Source Contributions

| Project | PR | What I Fixed |
|---------|:--:|-------------|
| [Mooncake](https://github.com/kvcache-ai/Mooncake) (5k★) | [#1629](https://github.com/kvcache-ai/Mooncake/pull/1629) | GB200 MNNVL EP hang: `cudaMalloc` → `cuMemCreate(FABRIC)` + `cuMemMap` for cross-node NVLink |
| [Mooncake](https://github.com/kvcache-ai/Mooncake) (5k★) | [#1728](https://github.com/kvcache-ai/Mooncake/pull/1728) | Hard pin for eviction-protected objects: model weights never get evicted, const field + BatchEvict skip + backward-compat serialization |
| [Mooncake](https://github.com/kvcache-ai/Mooncake) (5k★) | [#1644](https://github.com/kvcache-ai/Mooncake/pull/1644) | MNNVL warmup hang: skip redundant handshake for fabric-connected nodes |
| [Mooncake](https://github.com/kvcache-ai/Mooncake) (5k★) | [#1825](https://github.com/kvcache-ai/Mooncake/pull/1825) | Fix `P2PClientService::Put` silently swallowing write errors: propagate actual error codes for non-idempotent failures |
| [Mooncake](https://github.com/kvcache-ai/Mooncake) (5k★) | [#1626](https://github.com/kvcache-ai/Mooncake/pull/1626) | Silenced error log spam for non-memory replicas in metadata store |
| [vLLM](https://github.com/vllm-project/vllm) (74k★) | [#37884](https://github.com/vllm-project/vllm/pull/37884) | RoBERTa position_ids in-place accumulation on CUDA graph padding: BGE-M3 crash after ~4000 requests |
| [vLLM](https://github.com/vllm-project/vllm) (74k★) | [#37301](https://github.com/vllm-project/vllm/pull/37301) | Base64 JPEG video frames returning empty metadata: populate frame count, fps, duration |
| [Transformers](https://github.com/huggingface/transformers) (158k★) | [#44710](https://github.com/huggingface/transformers/pull/44710) | Fix `AutoProcessor.from_pretrained` silently dropping hub kwargs (`revision`, `token`, etc.) |
| [FlashInfer](https://github.com/flashinfer-ai/flashinfer) (5k★) | [#2756](https://github.com/flashinfer-ai/flashinfer/pull/2756) | Fix autotuner crash when input tensor is `None`: proper None-checking for optional inputs (fixes #2749) |
| [AstrBot](https://github.com/AstrBotDevs/AstrBot) (28k★) | [#6596](https://github.com/AstrBotDevs/AstrBot/pull/6596) | Multimodal token counting: images, audio, chain-of-thought were invisible to context compression |
| [AstrBot](https://github.com/AstrBotDevs/AstrBot) (28k★) | [#6474](https://github.com/AstrBotDevs/AstrBot/pull/6474) | SQLite `database is locked` under concurrent writes: added busy timeout |
| [AstrBot](https://github.com/AstrBotDevs/AstrBot) (28k★) | [#7003](https://github.com/AstrBotDevs/AstrBot/pull/7003) | SSE heartbeat for WebChat: long context compression killed the connection |
| [AstrBot](https://github.com/AstrBotDevs/AstrBot) (28k★) | [#6581](https://github.com/AstrBotDevs/AstrBot/pull/6581) | Context truncation dropping the only user message: causes 400 from Zhipu/Gemini |
| [AstrBot](https://github.com/AstrBotDevs/AstrBot) (28k★) | [#6656](https://github.com/AstrBotDevs/AstrBot/pull/6656) | `/stop` follow-up race: agent_stop flag not checked during follow-up capture |
| [AstrBot](https://github.com/AstrBotDevs/AstrBot) (28k★) | [#6710](https://github.com/AstrBotDevs/AstrBot/pull/6710) | Skills-like re-query dropping image captions: `extra_user_content_parts` not forwarded |
| [AstrBot](https://github.com/AstrBotDevs/AstrBot) (28k★) | [#6527](https://github.com/AstrBotDevs/AstrBot/pull/6527) | Fix LLM tool selection: rewrote ambiguous Upload/Download descriptions |
| [AstrBot](https://github.com/AstrBotDevs/AstrBot) (28k★) | [#6313](https://github.com/AstrBotDevs/AstrBot/pull/6313) | Null choices guard: OpenAI API returning `None` instead of empty list |
| [AstrBot](https://github.com/AstrBotDevs/AstrBot) (28k★) | [#7217](https://github.com/AstrBotDevs/AstrBot/pull/7217) | Fix qwen3-rerank response parsing: handle both old and new Dashscope API formats |
| [AstrBot](https://github.com/AstrBotDevs/AstrBot) (28k★) | [#7216](https://github.com/AstrBotDevs/AstrBot/pull/7216) | Fix Gemini tool call 400: wrap plain-text tool results as Protobuf Struct |
| [AstrBot](https://github.com/AstrBotDevs/AstrBot) (28k★) | [#7196](https://github.com/AstrBotDevs/AstrBot/pull/7196) | Fix Gemini thinking parts leaking into user-facing response |
| [AstrBot](https://github.com/AstrBotDevs/AstrBot) (28k★) | [#6551](https://github.com/AstrBotDevs/AstrBot/pull/6551) | Fix empty content causing Grok 400: set content to None when empty |
| [ClawTeam](https://github.com/HKUDS/ClawTeam) (4.1k★) | [#1](https://github.com/HKUDS/ClawTeam/pull/1) | First PR: 122 tests, CI, team templates, config bugfixes, task duration tracking |
| [ClawTeam](https://github.com/HKUDS/ClawTeam) (4.1k★) | [#40](https://github.com/HKUDS/ClawTeam/pull/40) | Pluggable TaskStore: extract task persistence into swappable backend abstraction |
| [ClawTeam](https://github.com/HKUDS/ClawTeam) (4.1k★) | [#32](https://github.com/HKUDS/ClawTeam/pull/32) | Gemini CLI support: spawn, permissions, prompt injection for both backends |
| [ClawTeam](https://github.com/HKUDS/ClawTeam) (4.1k★) | [#36](https://github.com/HKUDS/ClawTeam/pull/36) | Kimi CLI support: spawn backend, permission handling, 3 new test cases |
| [ClawTeam](https://github.com/HKUDS/ClawTeam) (4.1k★) | [#24](https://github.com/HKUDS/ClawTeam/pull/24) | Team snapshot/restore: checkpoint and recovery for long-running agent swarms |
| [LightRAG](https://github.com/HKUDS/LightRAG) (31k★) | [#2796](https://github.com/HKUDS/LightRAG/pull/2796) | Fix `None` file_path propagating as `unknown_source`: fill gaps left by #2793 |
| [OpenClaw](https://github.com/openclaw/openclaw) (343k★) | [#41271](https://github.com/openclaw/openclaw/pull/41271) | Log auth profile resolution failures instead of swallowing silently |

### LinkedIn: https://www.linkedin.com/in/yufenghe




---

## Hi，我是何宇峰 👋

[Moonshot AI](https://www.moonshot.cn/) (Kimi) AI Agent 研究员 | 港大计算机硕士 | 上海全球AI大赛冠军 | 三次获ACM-ICPC银牌 | 曾在百度、脉脉、快手的AI 研发岗实习

### 项目

| 项目 | Stars | 简介 |
|------|:-----:|------|
| [CoreCoder](https://github.com/he-yufeng/CoreCoder) | 345+ | Claude Code 51万行源码 → 1400行 Python 核心重写，支持任意大模型，附 7 篇架构导读 |
| [AnyCoder](https://github.com/he-yufeng/AnyCoder) | new | 终端 AI 编程 Agent，通过 litellm 支持 100+ 大模型，~1450 行 Python，危险命令拦截、并行执行、会话持久化 |
| [FindJobs-Agent](https://github.com/he-yufeng/FindJobs-Agent) | 102+ | LLM 求职工具箱：技能差距分析、模拟面试、简历优化 |
| [MTSIR3-GAN](https://github.com/he-yufeng/MTSIR3-GAN) | 135+ | 将 R3GAN (NeurIPS 2024) 适配到多变量时序插补 + 对抗精炼实证研究 |
| [DRL-MultiFactorTrading](https://github.com/he-yufeng/DRL-MultiFactorTrading) | 70+ | 深度强化学习量化交易，Double DQN + 多因子 Alpha |
| [Arxiv Paper Coding Agent](https://github.com/he-yufeng/Arxiv_Paper_Coding_Agent--HKU_COMP7103C_Data_mining_Assignment) | 36+ | 多 LLM 协作 Agent，读论文自动生成可运行代码 |
| [ContractGuard](https://github.com/he-yufeng/ContractGuard) | 49+ | AI 合同审查 Agent，签字前帮你找出霸王条款 |
| [AgentProbe](https://github.com/he-yufeng/AgentProbe) | 33+ | AI Agent 回归测试 pytest 插件：快照基线、语义比较、Mock LLM |
| [PromptDiff](https://github.com/he-yufeng/PromptDiff) | 25+ | LLM prompt 语义 diff 工具，像 git diff 一样对比 prompt 版本 |
| [TokenTracker](https://github.com/he-yufeng/TokenTracker) | 14+ | LLM 开销追踪，改一行 import 就能用 |
| [GitSense](https://github.com/he-yufeng/GitSense) | 13+ | AI 驱动的开源贡献发现器，输入技能自动找 issue |
| [RuleForge](https://github.com/he-yufeng/RuleForge) | 11+ | 从代码库自动生成 AI 助手规则（CLAUDE.md、.cursorrules）|
| [BatchLLM](https://github.com/he-yufeng/BatchLLM) | 8+ | LLM 批量处理：CSV 进 CSV 出，自动重试 + 费用追踪 |

### 开源贡献

| 项目 | PR | 修了啥 |
|------|:--:|--------|
| [Mooncake](https://github.com/kvcache-ai/Mooncake) (5k★) | [#1629](https://github.com/kvcache-ai/Mooncake/pull/1629) | GB200 MNNVL EP hang：`cudaMalloc` → `cuMemCreate(FABRIC)` + `cuMemMap` 跨节点 NVLink 通信 |
| [Mooncake](https://github.com/kvcache-ai/Mooncake) (5k★) | [#1728](https://github.com/kvcache-ai/Mooncake/pull/1728) | Hard pin 驱逐保护：模型权重永不被驱逐，const 字段 + BatchEvict 跳过 + 向后兼容序列化 |
| [Mooncake](https://github.com/kvcache-ai/Mooncake) (5k★) | [#1644](https://github.com/kvcache-ai/Mooncake/pull/1644) | MNNVL warmup hang：跳过 fabric 连接节点的冗余握手 |
| [Mooncake](https://github.com/kvcache-ai/Mooncake) (5k★) | [#1825](https://github.com/kvcache-ai/Mooncake/pull/1825) | 修复 `P2PClientService::Put` 静默吞掉写入错误：传播实际错误码给调用方 |
| [Mooncake](https://github.com/kvcache-ai/Mooncake) (5k★) | [#1626](https://github.com/kvcache-ai/Mooncake/pull/1626) | 修复非内存副本的错误日志刷屏 |
| [vLLM](https://github.com/vllm-project/vllm) (74k★) | [#37884](https://github.com/vllm-project/vllm/pull/37884) | 修复 RoBERTa position_ids 原地累积溢出：BGE-M3 约 4000 请求后 CUDA graph padding crash |
| [vLLM](https://github.com/vllm-project/vllm) (74k★) | [#37301](https://github.com/vllm-project/vllm/pull/37301) | 修复 base64 JPEG 视频帧返回空 metadata：补充帧数、fps、时长 |
| [Transformers](https://github.com/huggingface/transformers) (158k★) | [#44710](https://github.com/huggingface/transformers/pull/44710) | 修复 `AutoProcessor.from_pretrained` 静默丢弃 hub kwargs（`revision`、`token` 等）|
| [FlashInfer](https://github.com/flashinfer-ai/flashinfer) (5k★) | [#2756](https://github.com/flashinfer-ai/flashinfer/pull/2756) | 修复 autotuner 在输入 tensor 为 `None` 时崩溃（fixes #2749）|
| [AstrBot](https://github.com/AstrBotDevs/AstrBot) (28k★) | [#6596](https://github.com/AstrBotDevs/AstrBot/pull/6596) | 多模态 token 计数：图片/音频/思考链对 context 压缩不可见的问题 |
| [AstrBot](https://github.com/AstrBotDevs/AstrBot) (28k★) | [#6474](https://github.com/AstrBotDevs/AstrBot/pull/6474) | 修复 SQLite 并发写入 `database is locked`，添加 busy timeout |
| [AstrBot](https://github.com/AstrBotDevs/AstrBot) (28k★) | [#7003](https://github.com/AstrBotDevs/AstrBot/pull/7003) | 修复 WebChat 长响应断连：SSE 心跳保活，context 压缩期间不再超时 |
| [AstrBot](https://github.com/AstrBotDevs/AstrBot) (28k★) | [#6581](https://github.com/AstrBotDevs/AstrBot/pull/6581) | 修复截断器丢失唯一 user 消息导致智谱/Gemini 返回 400 |
| [AstrBot](https://github.com/AstrBotDevs/AstrBot) (28k★) | [#6656](https://github.com/AstrBotDevs/AstrBot/pull/6656) | 修复 `/stop` 后新消息仍被 follow-up 捕获的竞态条件 |
| [AstrBot](https://github.com/AstrBotDevs/AstrBot) (28k★) | [#6710](https://github.com/AstrBotDevs/AstrBot/pull/6710) | 修复 skills-like re-query 丢失图片描述：`extra_user_content_parts` 未传递 |
| [AstrBot](https://github.com/AstrBotDevs/AstrBot) (28k★) | [#6527](https://github.com/AstrBotDevs/AstrBot/pull/6527) | 修复 LLM 工具选择：重写模糊的 Upload/Download 描述 |
| [AstrBot](https://github.com/AstrBotDevs/AstrBot) (28k★) | [#6313](https://github.com/AstrBotDevs/AstrBot/pull/6313) | 修复 OpenAI API 返回 `None` choices 导致崩溃 |
| [AstrBot](https://github.com/AstrBotDevs/AstrBot) (28k★) | [#7217](https://github.com/AstrBotDevs/AstrBot/pull/7217) | 修复 qwen3-rerank 响应解析：兼容新旧百炼 API 格式 |
| [AstrBot](https://github.com/AstrBotDevs/AstrBot) (28k★) | [#7216](https://github.com/AstrBotDevs/AstrBot/pull/7216) | 修复 Gemini tool call 400：纯文本 tool result 包装为 Protobuf Struct |
| [AstrBot](https://github.com/AstrBotDevs/AstrBot) (28k★) | [#7196](https://github.com/AstrBotDevs/AstrBot/pull/7196) | 修复 Gemini thinking parts 泄漏到用户可见的消息内容中 |
| [AstrBot](https://github.com/AstrBotDevs/AstrBot) (28k★) | [#6551](https://github.com/AstrBotDevs/AstrBot/pull/6551) | 修复空 content 导致 Grok 400：content 为空时设为 None |
| [ClawTeam](https://github.com/HKUDS/ClawTeam) (4.1k★) | [#1](https://github.com/HKUDS/ClawTeam/pull/1) | 首个 PR：122 个测试、CI、团队模板、config 修复、任务耗时追踪 |
| [ClawTeam](https://github.com/HKUDS/ClawTeam) (4.1k★) | [#40](https://github.com/HKUDS/ClawTeam/pull/40) | 可插拔 TaskStore：将任务持久化抽取为可替换的后端抽象层 |
| [ClawTeam](https://github.com/HKUDS/ClawTeam) (4.1k★) | [#32](https://github.com/HKUDS/ClawTeam/pull/32) | Gemini CLI 支持：spawn、权限、prompt 注入双 backend 适配 |
| [ClawTeam](https://github.com/HKUDS/ClawTeam) (4.1k★) | [#36](https://github.com/HKUDS/ClawTeam/pull/36) | Kimi CLI 支持：spawn backend、权限处理、3 个新测试 |
| [ClawTeam](https://github.com/HKUDS/ClawTeam) (4.1k★) | [#24](https://github.com/HKUDS/ClawTeam/pull/24) | 团队快照/恢复：长时间 agent swarm 的检查点和恢复机制 |
| [LightRAG](https://github.com/HKUDS/LightRAG) (31k★) | [#2796](https://github.com/HKUDS/LightRAG/pull/2796) | 修复 `None` file_path 传播为 `unknown_source`：补 #2793 遗漏的处理层 |
| [OpenClaw](https://github.com/openclaw/openclaw) (343k★) | [#41271](https://github.com/openclaw/openclaw/pull/41271) | 认证配置解析失败时记录日志而非静默吞掉 |

### 领英LinkedIn: https://www.linkedin.com/in/yufenghe
