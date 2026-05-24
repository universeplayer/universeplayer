## Hey, I'm Yufeng He 👋

Agentic AI Researcher @ [Moonshot AI](https://www.moonshot.cn/) (Kimi) | MS CS @ HKU | Champion, Shanghai Global AI Contest | 3x ACM-ICPC Silver Medalist | Former Intern @ Baidu, Maimai, Kuaishou

### Projects

| Project | Stars | What it does |
|---------|:-----:|-------------|
| [CoreCoder](https://github.com/he-yufeng/CoreCoder) | 694+ | 512K lines of Claude Code → 1,400 lines of Python. Every key architectural pattern, runnable. Any LLM. 7 architecture deep-dive articles. |
| [FindJobs-Agent](https://github.com/he-yufeng/FindJobs-Agent) | 217+ | LLM-powered job toolkit: skill gap analysis, mock interviews, resume optimization |
| [MTSIR3-GAN](https://github.com/he-yufeng/MTSIR3-GAN) | 135+ | Adapting R3GAN (NeurIPS 2024) to multivariate time series imputation + adversarial refinement study |
| [ContractGuard](https://github.com/he-yufeng/ContractGuard) | 110+ | AI agent that reviews contracts for red flags before you sign |
| [DRL-MultiFactorTrading](https://github.com/he-yufeng/DRL-MultiFactorTrading) | 75+ | Deep RL trading strategies with Double DQN and multi-factor alpha signals |
| [Arxiv Paper Coding Agent](https://github.com/he-yufeng/Arxiv_Paper_Coding_Agent--HKU_COMP7103C_Data_mining_Assignment) | 38+ | Multi-LLM crew that reads a paper and produces a working implementation |
| [AgentProbe](https://github.com/he-yufeng/AgentProbe) | 34+ | Pytest plugin for regression-testing AI agents: snapshot baselines, semantic comparison, mock LLMs |
| [MCPReady](https://github.com/he-yufeng/MCPReady) | 1+ | CI gate for MCP servers: handshake, tools/list, schema checks, secret-leak scan, Markdown/JSON reports, GitHub Action |
| [PromptDiff](https://github.com/he-yufeng/PromptDiff) | 25+ | Semantic diff for LLM prompts, compare prompt versions like git diff |
| [RuleForge](https://github.com/he-yufeng/RuleForge) | 55+ | Auto-generate AI assistant rules (CLAUDE.md, .cursorrules) from codebase analysis |
| [GitSense](https://github.com/he-yufeng/GitSense) | 38+ | AI-powered contribution finder and repo radar: find matching issues, then check PR merge signals |
| [TokenTracker](https://github.com/he-yufeng/TokenTracker) | 32+ | Drop-in LLM cost tracker, change one import line, see where your money goes |
| [AnyCoder](https://github.com/he-yufeng/AnyCoder) | 18+ | AI coding agent CLI supporting 100+ LLMs via litellm. ~1,450 lines Python, dangerous command blocking, parallel tool execution, session persistence. |
| [BatchLLM](https://github.com/he-yufeng/BatchLLM) | 26+ | Batch LLM processing: CSV in, processed CSV out, with retries and cost tracking |
| [RepoWiki](https://github.com/he-yufeng/RepoWiki) | 102+ | Open-source DeepWiki alternative: generate wiki docs for any codebase from CLI or browser. PageRank file ranking, Mermaid diagrams, reading guides. |
| [CodeABC](https://github.com/he-yufeng/CodeABC) | 43+ | AI code reader for non-programmers: drag in a project, get plain-language explanations with hover annotations |
| [LiteBench](https://github.com/he-yufeng/LiteBench) | 2+ | Pip-installable LLM/agent benchmark CLI + web dashboard. 6 built-in tasks + agent mode (tool-use eval) + custom YAML + LLM-as-judge + `litebench serve`. 100+ models via litellm. |
| [CodeJoust](https://github.com/he-yufeng/CodeJoust) | 4+ | A CLI arena for AI coding agents. Throw one bug at Claude Code + aider + Codex + Gemini (Cursor next), each runs in its own `git worktree`, scored by tests + cost + diff + time. `pip install codejoust`. |

### Open Source Contributions

| Project | PR | What I Fixed |
|---------|:--:|-------------|
| [Mooncake](https://github.com/kvcache-ai/Mooncake) (5k★) | [#1629](https://github.com/kvcache-ai/Mooncake/pull/1629) | GB200 MNNVL EP hang: `cudaMalloc` → `cuMemCreate(FABRIC)` + `cuMemMap` for cross-node NVLink |
| [Mooncake](https://github.com/kvcache-ai/Mooncake) (5k★) | [#1728](https://github.com/kvcache-ai/Mooncake/pull/1728) | Hard pin for eviction-protected objects: model weights never get evicted, const field + BatchEvict skip + backward-compat serialization |
| [Mooncake](https://github.com/kvcache-ai/Mooncake) (5k★) | [#1719](https://github.com/kvcache-ai/Mooncake/pull/1719) | Add `ObjectDataType` metadata classification for KV cache, weights, tensors, and snapshots, with backward-compatible serialization and Python bindings |
| [Mooncake](https://github.com/kvcache-ai/Mooncake) (5k★) | [#1644](https://github.com/kvcache-ai/Mooncake/pull/1644) | MNNVL warmup hang: skip redundant handshake for fabric-connected nodes |
| [Mooncake](https://github.com/kvcache-ai/Mooncake) (5k★) | [#1831](https://github.com/kvcache-ai/Mooncake/pull/1831) | TENT NVLink IPC fix: use base pointer for sub-allocated GPU tensors, porting #1622 fix to TENT path |
| [Mooncake](https://github.com/kvcache-ai/Mooncake) (5k★) | [#1825](https://github.com/kvcache-ai/Mooncake/pull/1825) | Fix `P2PClientService::Put` silently swallowing write errors: propagate actual error codes for non-idempotent failures |
| [Mooncake](https://github.com/kvcache-ai/Mooncake) (5k★) | [#1626](https://github.com/kvcache-ai/Mooncake/pull/1626) | Silenced error log spam for non-memory replicas in metadata store |
| [Microsoft Agent Framework](https://github.com/microsoft/agent-framework) (10k★) | [#5462](https://github.com/microsoft/agent-framework/pull/5462) | Fix `background=True` + tools infinite-retrieve loop: clear completed continuation state so tool results get posted |
| [Microsoft Agent Framework](https://github.com/microsoft/agent-framework) (10k★) | [#5778](https://github.com/microsoft/agent-framework/pull/5778) | Declare Magentic protocol messages so orchestrator chat/reset signals deserialize instead of failing on unknown types |
| [Microsoft Agent Framework](https://github.com/microsoft/agent-framework) (10k★) | [#5808](https://github.com/microsoft/agent-framework/pull/5808) | Fix handoff message role mutation so retries reuse sanitized messages without leaking role changes |
| [Microsoft Agent Framework](https://github.com/microsoft/agent-framework) (10k★) | [#5799](https://github.com/microsoft/agent-framework/pull/5799) | Add handoff workflow naming metadata so names and descriptions flow through builder and hosting registration |
| [Microsoft Agent Framework](https://github.com/microsoft/agent-framework) (10k★) | [#5815](https://github.com/microsoft/agent-framework/pull/5815) | Forward MCP tool-call metadata from `tools/list` into `call_tool` instrumentation so traces keep tool annotations |
| [Microsoft Agent Framework](https://github.com/microsoft/agent-framework) (10k★) | [#5800](https://github.com/microsoft/agent-framework/pull/5800) | Avoid AG-UI tool result message id collisions when providers omit update ids |
| [Microsoft Agent Framework](https://github.com/microsoft/agent-framework) (10k★) | [#5974](https://github.com/microsoft/agent-framework/pull/5974) | Include Foundry agent tool definitions in eval mappings so evaluator runs can call code-defined tools |
| [Microsoft Agent Framework](https://github.com/microsoft/agent-framework) (10k★) | [#5861](https://github.com/microsoft/agent-framework/pull/5861) | Preserve structured Foundry handoff arguments so delegated agent calls survive response conversion |
| [Microsoft Agent Framework](https://github.com/microsoft/agent-framework) (10k★) | [#5976](https://github.com/microsoft/agent-framework/pull/5976) | Fix sequential workflow sample output so all participant responses are shown from non-streaming results |
| [LiveKit Agents](https://github.com/livekit/agents) (10k★) | [#5820](https://github.com/livekit/agents/pull/5820) | Recreate Anthropic streaming requests on retry so transient stream creation failures do not re-await the same coroutine |
| [AG-UI](https://github.com/ag-ui-protocol/ag-ui) (7k★) | [#1735](https://github.com/ag-ui-protocol/ag-ui/pull/1735) | Avoid stale ADK session writes after human-in-the-loop tool calls |
| [Triton](https://github.com/triton-lang/triton) (15k★) | [#9613](https://github.com/triton-lang/triton/pull/9613) | Fix AxisInfo correctness: signed constants, unknown shift divisibility, and shift UB guards |
| [LiteLLM](https://github.com/BerriAI/litellm) (20k★) | [#26401](https://github.com/BerriAI/litellm/pull/26401) | Fix `LITELLM_LOG=INFO` missing `verbose_logger`: proxy INFO logs now include all verbose logger sources |
| [Pydantic AI](https://github.com/pydantic/pydantic-ai) (17k★) | [#5474](https://github.com/pydantic/pydantic-ai/pull/5474) | Accept `providerExecuted` and `title` on Vercel AI dynamic-tool message parts so strict validation preserves provider metadata |
| [vLLM](https://github.com/vllm-project/vllm) (74k★) | [#37699](https://github.com/vllm-project/vllm/pull/37699) | Fix weight offloading ignoring `VLLM_WEIGHT_OFFLOADING_DISABLE_PIN_MEMORY` in prefetch offloader |
| [vLLM](https://github.com/vllm-project/vllm) (74k★) | [#37884](https://github.com/vllm-project/vllm/pull/37884) | RoBERTa position_ids in-place accumulation on CUDA graph padding: BGE-M3 crash after ~4000 requests |
| [vLLM](https://github.com/vllm-project/vllm) (74k★) | [#37301](https://github.com/vllm-project/vllm/pull/37301) | Base64 JPEG video frames returning empty metadata: populate frame count, fps, duration |
| [vLLM](https://github.com/vllm-project/vllm) (74k★) | [#40789](https://github.com/vllm-project/vllm/pull/40789) | Support tuple model outputs in the V1 ubatch wrapper so DBO and speculative decoding stop crashing on tuple-returning models |
| [Transformers](https://github.com/huggingface/transformers) (158k★) | [#44710](https://github.com/huggingface/transformers/pull/44710) | Fix `AutoProcessor.from_pretrained` silently dropping hub kwargs (`revision`, `token`, etc.) |
| [FlashInfer](https://github.com/flashinfer-ai/flashinfer) (5k★) | [#2756](https://github.com/flashinfer-ai/flashinfer/pull/2756) | Fix autotuner crash when input tensor is `None`: proper None-checking for optional inputs (fixes #2749) |
| [FlashInfer](https://github.com/flashinfer-ai/flashinfer) (5k★) | [#2772](https://github.com/flashinfer-ai/flashinfer/pull/2772) | Fix compilation error: add missing `<optional>` header for `std::optional` usage in CUTLASS headers |
| [vLLM](https://github.com/vllm-project/vllm) (74k★) | [#37727](https://github.com/vllm-project/vllm/pull/37727) | Fix Responses API `instructions` leaking across turns via `previous_response_id` chain |
| [vLLM](https://github.com/vllm-project/vllm) (74k★) | [#38732](https://github.com/vllm-project/vllm/pull/38732) | Fix bench_serve UTF-8 decode crash on split multi-byte chars in streaming chunks |
| [vLLM](https://github.com/vllm-project/vllm) (74k★) | [#40749](https://github.com/vllm-project/vllm/pull/40749) | Helped unblock async PP fix with independent repro evidence for the last-rank sampled-token receive assertion |
| [SGLang](https://github.com/sgl-project/sglang) (25k★) | [#20739](https://github.com/sgl-project/sglang/pull/20739) | Fix hybrid_linear_attn_backend crash when used with ngram speculative decoding |
| [OpenHands SDK](https://github.com/OpenHands/software-agent-sdk) (712★) | [#3248](https://github.com/OpenHands/software-agent-sdk/pull/3248) | Serialize LiteLLM `modify_params` updates with an RLock so concurrent completions do not leak global parameter state |
| [OpenHands SDK](https://github.com/OpenHands/software-agent-sdk) (712★) | [#3225](https://github.com/OpenHands/software-agent-sdk/pull/3225) | Write remote completion logs as UTF-8 so non-ASCII output survives local replay and debugging |
| [Inspect AI](https://github.com/UKGovernmentBEIS/inspect_ai) (2k★) | [#3895](https://github.com/UKGovernmentBEIS/inspect_ai/pull/3895) | Honor `COLUMNS` for `TERM=dumb`: log output no longer hard-wraps at Rich's default 80 columns |
| [Inspect AI](https://github.com/UKGovernmentBEIS/inspect_ai) (2k★) | [#3902](https://github.com/UKGovernmentBEIS/inspect_ai/pull/3902) | Parse OpenRouter `reasoning_details` in OpenAI-compatible responses instead of surfacing Python repr blocks |
| [Inspect AI](https://github.com/UKGovernmentBEIS/inspect_ai) (2k★) | [#3896](https://github.com/UKGovernmentBEIS/inspect_ai/pull/3896) | Fix filestore recovery append mode: preserve carried message/tool-call pools without rehashing old segments |
| [Inspect AI](https://github.com/UKGovernmentBEIS/inspect_ai) (2k★) | [#3924](https://github.com/UKGovernmentBEIS/inspect_ai/pull/3924) | Reject unknown `GenerateConfig` fields early so misspelled generation options do not get silently ignored |
| [Inspect AI](https://github.com/UKGovernmentBEIS/inspect_ai) (2k★) | [#3941](https://github.com/UKGovernmentBEIS/inspect_ai/pull/3941) | Route Bedrock Nova `top_k` through the inference config instead of dropping the sampling control |
| [Inspect AI](https://github.com/UKGovernmentBEIS/inspect_ai) (2k★) | [#3975](https://github.com/UKGovernmentBEIS/inspect_ai/pull/3975) | Preserve call-site generation defaults when role model overrides are resolved, so eval roles can switch models without dropping config like max tokens or reasoning effort |
| [Inspect AI](https://github.com/UKGovernmentBEIS/inspect_ai) (2k★) | [#3982](https://github.com/UKGovernmentBEIS/inspect_ai/pull/3982) | Preserve wrapped OpenAI reasoning payloads in the agent bridge so encrypted provider-native reasoning items survive transcript conversion |
| [Phoenix](https://github.com/Arize-ai/phoenix) (9k★) | [#13139](https://github.com/Arize-ai/phoenix/pull/13139) | Surface playground validation errors instead of returning empty subscription payloads |
| [Phoenix](https://github.com/Arize-ai/phoenix) (9k★) | [#13210](https://github.com/Arize-ai/phoenix/pull/13210) | Return NotFound-style errors for invalid GraphQL node ids instead of leaking decoder failures to clients |
| [Phoenix](https://github.com/Arize-ai/phoenix) (9k★) | [#13261](https://github.com/Arize-ai/phoenix/pull/13261) | Refresh span annotation notes after create so the UI shows newly added notes without a manual reload |
| [Phoenix](https://github.com/Arize-ai/phoenix) (9k★) | [#13245](https://github.com/Arize-ai/phoenix/pull/13245) | Keep the generative model fetch cursor monotonic so lower-id updates cannot make later polling skip newer model changes |
| [AstrBot](https://github.com/AstrBotDevs/AstrBot) (28k★) | [#8255](https://github.com/AstrBotDevs/AstrBot/pull/8255) | Support RST and AsciiDoc knowledge uploads by keeping backend parser checks and dashboard file validation in sync |
| [AstrBot](https://github.com/AstrBotDevs/AstrBot) (28k★) | [#8195](https://github.com/AstrBotDevs/AstrBot/pull/8195) | Skip empty LLM summaries so context compression keeps the original history instead of inserting blank placeholders |
| [AstrBot](https://github.com/AstrBotDevs/AstrBot) (28k★) | [#6596](https://github.com/AstrBotDevs/AstrBot/pull/6596) | Multimodal token counting: images, audio, chain-of-thought were invisible to context compression |
| [AstrBot](https://github.com/AstrBotDevs/AstrBot) (28k★) | [#7758](https://github.com/AstrBotDevs/AstrBot/pull/7758) | Apply empty-assistant message filter to streaming OpenAI path: strict providers no longer 400 on reasoning-only turns |
| [AstrBot](https://github.com/AstrBotDevs/AstrBot) (28k★) | [#8073](https://github.com/AstrBotDevs/AstrBot/pull/8073) | Fix image-only KB retrieval: skip blank prompts so embedding APIs are not called with empty text |
| [AstrBot](https://github.com/AstrBotDevs/AstrBot) (28k★) | [#8061](https://github.com/AstrBotDevs/AstrBot/pull/8061) | Keep Discord startup alive when command sync hits the daily create quota; only quota errors become warnings |
| [AstrBot](https://github.com/AstrBotDevs/AstrBot) (28k★) | [#8172](https://github.com/AstrBotDevs/AstrBot/pull/8172) | Prefer bundled dashboard assets over stale data dist so releases do not serve an outdated WebUI |
| [AstrBot](https://github.com/AstrBotDevs/AstrBot) (28k★) | [#8175](https://github.com/AstrBotDevs/AstrBot/pull/8175) | Surface WeChat OA media send failures instead of reporting success after prepare/send timeouts |
| [AstrBot](https://github.com/AstrBotDevs/AstrBot) (28k★) | [#8119](https://github.com/AstrBotDevs/AstrBot/pull/8119) | Pass image inputs through active replies so image-triggered mentions reach the LLM as image URLs |
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
| [AstrBot](https://github.com/AstrBotDevs/AstrBot) (28k★) | [#7398](https://github.com/AstrBotDevs/AstrBot/pull/7398) | Fix Telegram sendMessageDraft spamming 400 errors on empty text in streaming mode |
| [AstrBot](https://github.com/AstrBotDevs/AstrBot) (28k★) | [#7407](https://github.com/AstrBotDevs/AstrBot/pull/7407) | Fix Gemini native search 400 when no function tools: skip FunctionCallingConfig |
| [AstrBot](https://github.com/AstrBotDevs/AstrBot) (28k★) | [#7537](https://github.com/AstrBotDevs/AstrBot/pull/7537) | Prevent Telegram media group exceptions from being silently swallowed by APScheduler |
| [AstrBot](https://github.com/AstrBotDevs/AstrBot) (28k★) | [#6551](https://github.com/AstrBotDevs/AstrBot/pull/6551) | Fix empty content causing Grok 400: set content to None when empty |
| [ClawTeam](https://github.com/HKUDS/ClawTeam) (4.1k★) | [#1](https://github.com/HKUDS/ClawTeam/pull/1) | First PR: 122 tests, CI, team templates, config bugfixes, task duration tracking |
| [ClawTeam](https://github.com/HKUDS/ClawTeam) (4.1k★) | [#40](https://github.com/HKUDS/ClawTeam/pull/40) | Pluggable TaskStore: extract task persistence into swappable backend abstraction |
| [ClawTeam](https://github.com/HKUDS/ClawTeam) (4.1k★) | [#32](https://github.com/HKUDS/ClawTeam/pull/32) | Gemini CLI support: spawn, permissions, prompt injection for both backends |
| [ClawTeam](https://github.com/HKUDS/ClawTeam) (4.1k★) | [#36](https://github.com/HKUDS/ClawTeam/pull/36) | Kimi CLI support: spawn backend, permission handling, 3 new test cases |
| [LightRAG](https://github.com/HKUDS/LightRAG) (31k★) | [#2796](https://github.com/HKUDS/LightRAG/pull/2796) | Fix `None` file_path propagating as `unknown_source`: fill gaps left by #2793 |
| [LightRAG](https://github.com/HKUDS/LightRAG) (31k★) | [#3031](https://github.com/HKUDS/LightRAG/pull/3031) | Extract Docling async markdown results from the response envelope so RAG chunks contain clean document text |
| [LightRAG](https://github.com/HKUDS/LightRAG) (35k★) | [#3123](https://github.com/HKUDS/LightRAG/pull/3123) | Sync API documentation colors with the dark theme so endpoint examples stay readable in dark mode |
| [OpenHarness](https://github.com/HKUDS/OpenHarness) (11k★) | [#185](https://github.com/HKUDS/OpenHarness/pull/185) | TUI tab-completion: fix cursor jump, strip trailing space, accept `/quit` alias |
| [OpenClaw](https://github.com/openclaw/openclaw) (343k★) | [#41259](https://github.com/openclaw/openclaw/pull/41259) | Propagate memory directory creation failures instead of continuing after a failed `ensureDir` |
| [OpenClaw](https://github.com/openclaw/openclaw) (343k★) | [#41271](https://github.com/openclaw/openclaw/pull/41271) | Log auth profile resolution failures instead of swallowing silently |

### LinkedIn: https://www.linkedin.com/in/yufenghe




---

## Hi，我是何宇峰 👋

[Moonshot AI](https://www.moonshot.cn/) (Kimi) AI Agent 研究员 | 港大计算机硕士 | 上海全球AI大赛冠军 | 三次获ACM-ICPC银牌 | 曾在百度、脉脉、快手的AI 研发岗实习

### 项目

| 项目 | Stars | 简介 |
|------|:-----:|------|
| [CoreCoder](https://github.com/he-yufeng/CoreCoder) | 694+ | Claude Code 51万行源码 → 1400行 Python 核心重写，支持任意大模型，附 7 篇架构导读 |
| [FindJobs-Agent](https://github.com/he-yufeng/FindJobs-Agent) | 217+ | LLM 求职工具箱：技能差距分析、模拟面试、简历优化 |
| [MTSIR3-GAN](https://github.com/he-yufeng/MTSIR3-GAN) | 135+ | 将 R3GAN (NeurIPS 2024) 适配到多变量时序插补 + 对抗精炼实证研究 |
| [ContractGuard](https://github.com/he-yufeng/ContractGuard) | 110+ | AI 合同审查 Agent，签字前帮你找出霸王条款 |
| [DRL-MultiFactorTrading](https://github.com/he-yufeng/DRL-MultiFactorTrading) | 75+ | 深度强化学习量化交易，Double DQN + 多因子 Alpha |
| [Arxiv Paper Coding Agent](https://github.com/he-yufeng/Arxiv_Paper_Coding_Agent--HKU_COMP7103C_Data_mining_Assignment) | 38+ | 多 LLM 协作 Agent，读论文自动生成可运行代码 |
| [AgentProbe](https://github.com/he-yufeng/AgentProbe) | 34+ | AI Agent 回归测试 pytest 插件：快照基线、语义比较、Mock LLM |
| [MCPReady](https://github.com/he-yufeng/MCPReady) | 1+ | MCP Server CI 质量门禁：握手、tools/list、schema 检查、明显 token 泄露扫描，输出 Markdown/JSON 报告并提供 GitHub Action |
| [PromptDiff](https://github.com/he-yufeng/PromptDiff) | 25+ | LLM prompt 语义 diff 工具，像 git diff 一样对比 prompt 版本 |
| [RuleForge](https://github.com/he-yufeng/RuleForge) | 55+ | 从代码库自动生成 AI 助手规则（CLAUDE.md、.cursorrules）|
| [GitSense](https://github.com/he-yufeng/GitSense) | 38+ | AI 开源贡献发现器 + 仓库雷达：找匹配 issue，也评估 PR 合入友好度 |
| [TokenTracker](https://github.com/he-yufeng/TokenTracker) | 32+ | LLM 开销追踪，改一行 import 就能用 |
| [AnyCoder](https://github.com/he-yufeng/AnyCoder) | 18+ | 终端 AI 编程 Agent，通过 litellm 支持 100+ 大模型，~1450 行 Python，危险命令拦截、并行执行、会话持久化 |
| [BatchLLM](https://github.com/he-yufeng/BatchLLM) | 26+ | LLM 批量处理：CSV 进 CSV 出，自动重试 + 费用追踪 |
| [RepoWiki](https://github.com/he-yufeng/RepoWiki) | 102+ | 开源 DeepWiki 替代品：CLI 或浏览器生成仓库 wiki 文档，PageRank 文件排名、Mermaid 架构图、阅读指南 |
| [CodeABC](https://github.com/he-yufeng/CodeABC) | 43+ | 面向非程序员的 AI 代码阅读器：拖入项目，生成大白话逐行批注 |
| [LiteBench](https://github.com/he-yufeng/LiteBench) | 2+ | 一条命令跑 LLM / Agent benchmark 的轻量 CLI + Web 面板：6 个内置任务 + agent 模式 + 自定义 YAML + LLM judge + `litebench serve`。litellm 支持 100+ 模型 |
| [CodeJoust](https://github.com/he-yufeng/CodeJoust) | 4+ | AI 编程 Agent 擂台：一条命令让 Claude Code、aider、Codex、Gemini（下一步 Cursor）在独立 git worktree 里解同一个 bug，按测试通过率、成本、diff 大小、耗时打分选最优 patch。`pip install codejoust` |

### 开源贡献

| 项目 | PR | 修了啥 |
|------|:--:|--------|
| [Mooncake](https://github.com/kvcache-ai/Mooncake) (5k★) | [#1629](https://github.com/kvcache-ai/Mooncake/pull/1629) | GB200 MNNVL EP hang：`cudaMalloc` → `cuMemCreate(FABRIC)` + `cuMemMap` 跨节点 NVLink 通信 |
| [Mooncake](https://github.com/kvcache-ai/Mooncake) (5k★) | [#1728](https://github.com/kvcache-ai/Mooncake/pull/1728) | Hard pin 驱逐保护：模型权重永不被驱逐，const 字段 + BatchEvict 跳过 + 向后兼容序列化 |
| [Mooncake](https://github.com/kvcache-ai/Mooncake) (5k★) | [#1719](https://github.com/kvcache-ai/Mooncake/pull/1719) | 新增 `ObjectDataType` 元数据分类：KV cache、weights、tensors 等对象类型可在 metadata、snapshot 和 Python binding 中稳定传递 |
| [Mooncake](https://github.com/kvcache-ai/Mooncake) (5k★) | [#1644](https://github.com/kvcache-ai/Mooncake/pull/1644) | MNNVL warmup hang：跳过 fabric 连接节点的冗余握手 |
| [Mooncake](https://github.com/kvcache-ai/Mooncake) (5k★) | [#1831](https://github.com/kvcache-ai/Mooncake/pull/1831) | TENT NVLink IPC 修复：sub-allocated GPU tensor 使用 base pointer，将 #1622 修复移植到 TENT 路径 |
| [Mooncake](https://github.com/kvcache-ai/Mooncake) (5k★) | [#1825](https://github.com/kvcache-ai/Mooncake/pull/1825) | 修复 `P2PClientService::Put` 静默吞掉写入错误：传播实际错误码给调用方 |
| [Mooncake](https://github.com/kvcache-ai/Mooncake) (5k★) | [#1626](https://github.com/kvcache-ai/Mooncake/pull/1626) | 修复非内存副本的错误日志刷屏 |
| [Microsoft Agent Framework](https://github.com/microsoft/agent-framework) (10k★) | [#5462](https://github.com/microsoft/agent-framework/pull/5462) | 修复 `background=True` + tools 无限 retrieve loop：清掉已完成的 continuation 状态，让 tool results 正常提交 |
| [Microsoft Agent Framework](https://github.com/microsoft/agent-framework) (10k★) | [#5778](https://github.com/microsoft/agent-framework/pull/5778) | 补齐 Magentic protocol 的 chat/reset message 声明，避免 orchestrator 反序列化未知类型失败 |
| [Microsoft Agent Framework](https://github.com/microsoft/agent-framework) (10k★) | [#5808](https://github.com/microsoft/agent-framework/pull/5808) | 修复 handoff message role 原地修改：重试复用消息时不再把角色变更泄漏到后续流程 |
| [Microsoft Agent Framework](https://github.com/microsoft/agent-framework) (10k★) | [#5799](https://github.com/microsoft/agent-framework/pull/5799) | 补齐 Handoff workflow 的 name/description 元数据传递，让 builder 和 hosting 注册都能命名工作流 |
| [Microsoft Agent Framework](https://github.com/microsoft/agent-framework) (10k★) | [#5815](https://github.com/microsoft/agent-framework/pull/5815) | 转发 MCP `tools/list` 元数据到 `call_tool` instrumentation，让 trace 保留工具注解 |
| [Microsoft Agent Framework](https://github.com/microsoft/agent-framework) (10k★) | [#5800](https://github.com/microsoft/agent-framework/pull/5800) | 修复 AG-UI tool result message id 冲突：provider 省略 update id 时仍能生成独立 fallback id |
| [Microsoft Agent Framework](https://github.com/microsoft/agent-framework) (10k★) | [#5974](https://github.com/microsoft/agent-framework/pull/5974) | 让 Foundry agent eval 映射保留工具定义，评测运行能正常调用代码定义的 tools |
| [Microsoft Agent Framework](https://github.com/microsoft/agent-framework) (10k★) | [#5861](https://github.com/microsoft/agent-framework/pull/5861) | 修复 Foundry handoff 参数序列化，delegated agent 调用不再丢失结构化参数 |
| [Microsoft Agent Framework](https://github.com/microsoft/agent-framework) (10k★) | [#5976](https://github.com/microsoft/agent-framework/pull/5976) | 修复 sequential workflow 示例输出，让非 streaming 结果展示所有参与 agent 的回复 |
| [LiveKit Agents](https://github.com/livekit/agents) (10k★) | [#5820](https://github.com/livekit/agents/pull/5820) | 修复 Anthropic streaming retry：瞬时建流失败后重新创建 stream，不再重复 await 同一个 coroutine |
| [AG-UI](https://github.com/ag-ui-protocol/ag-ui) (7k★) | [#1735](https://github.com/ag-ui-protocol/ag-ui/pull/1735) | 修复 HITL tool call 后 ADK session 可能被旧状态回写的问题 |
| [Triton](https://github.com/triton-lang/triton) (15k★) | [#9613](https://github.com/triton-lang/triton/pull/9613) | 修复 AxisInfo 正确性：有符号常量、未知 shift 和 shift UB 都保守处理 |
| [LiteLLM](https://github.com/BerriAI/litellm) (20k★) | [#26401](https://github.com/BerriAI/litellm/pull/26401) | 修复 `LITELLM_LOG=INFO` 漏设 `verbose_logger`：proxy INFO 日志不再静默丢失 |
| [Pydantic AI](https://github.com/pydantic/pydantic-ai) (17k★) | [#5474](https://github.com/pydantic/pydantic-ai/pull/5474) | 兼容 Vercel AI dynamic-tool 消息里的 `providerExecuted` 和 `title` 字段，保留 provider 元数据而不是被严格校验拒绝 |
| [vLLM](https://github.com/vllm-project/vllm) (74k★) | [#37699](https://github.com/vllm-project/vllm/pull/37699) | 修复 weight offloading 忽略 `VLLM_WEIGHT_OFFLOADING_DISABLE_PIN_MEMORY` 环境变量 |
| [vLLM](https://github.com/vllm-project/vllm) (74k★) | [#37884](https://github.com/vllm-project/vllm/pull/37884) | 修复 RoBERTa position_ids 原地累积溢出：BGE-M3 约 4000 请求后 CUDA graph padding crash |
| [vLLM](https://github.com/vllm-project/vllm) (74k★) | [#37301](https://github.com/vllm-project/vllm/pull/37301) | 修复 base64 JPEG 视频帧返回空 metadata：补充帧数、fps、时长 |
| [vLLM](https://github.com/vllm-project/vllm) (74k★) | [#40789](https://github.com/vllm-project/vllm/pull/40789) | 修复 V1 ubatch wrapper 不支持 tuple model outputs：DBO / speculative decoding 不再因 tuple 返回值崩溃 |
| [Transformers](https://github.com/huggingface/transformers) (158k★) | [#44710](https://github.com/huggingface/transformers/pull/44710) | 修复 `AutoProcessor.from_pretrained` 静默丢弃 hub kwargs（`revision`、`token` 等）|
| [FlashInfer](https://github.com/flashinfer-ai/flashinfer) (5k★) | [#2756](https://github.com/flashinfer-ai/flashinfer/pull/2756) | 修复 autotuner 在输入 tensor 为 `None` 时崩溃（fixes #2749）|
| [FlashInfer](https://github.com/flashinfer-ai/flashinfer) (5k★) | [#2772](https://github.com/flashinfer-ai/flashinfer/pull/2772) | 修复编译错误：CUTLASS 头文件缺少 `<optional>` include 导致 `std::optional` 未定义 |
| [vLLM](https://github.com/vllm-project/vllm) (74k★) | [#37727](https://github.com/vllm-project/vllm/pull/37727) | 修复 Responses API 的 `instructions` 通过 `previous_response_id` 链泄漏到后续轮次 |
| [vLLM](https://github.com/vllm-project/vllm) (74k★) | [#38732](https://github.com/vllm-project/vllm/pull/38732) | 修复 bench_serve 流式响应拆分多字节 UTF-8 字符导致 decode 崩溃 |
| [vLLM](https://github.com/vllm-project/vllm) (74k★) | [#40749](https://github.com/vllm-project/vllm/pull/40749) | 补充独立复现证据，帮助确认 async PP last-rank sampled-token receive assertion 的真实可达路径 |
| [SGLang](https://github.com/sgl-project/sglang) (25k★) | [#20739](https://github.com/sgl-project/sglang/pull/20739) | 修复 hybrid_linear_attn_backend 与 ngram 投机采样同时使用时崩溃 |
| [OpenHands SDK](https://github.com/OpenHands/software-agent-sdk) (712★) | [#3248](https://github.com/OpenHands/software-agent-sdk/pull/3248) | 用 RLock 串行化 LiteLLM `modify_params` 的保存、设置和恢复，避免并发 completion 泄漏全局参数状态 |
| [OpenHands SDK](https://github.com/OpenHands/software-agent-sdk) (712★) | [#3225](https://github.com/OpenHands/software-agent-sdk/pull/3225) | 按 UTF-8 写入 remote completion 日志，避免中文和非 ASCII 输出在本地回放、排查时损坏 |
| [Inspect AI](https://github.com/UKGovernmentBEIS/inspect_ai) (2k★) | [#3895](https://github.com/UKGovernmentBEIS/inspect_ai/pull/3895) | 修复 `TERM=dumb` 下终端宽度：尊重 `COLUMNS`，日志输出不再固定按 Rich 默认 80 列硬换行 |
| [Inspect AI](https://github.com/UKGovernmentBEIS/inspect_ai) (2k★) | [#3902](https://github.com/UKGovernmentBEIS/inspect_ai/pull/3902) | 修复 OpenAI-compatible 响应里的 OpenRouter `reasoning_details`：解析为可读 reasoning 文本，而不是暴露 Python repr |
| [Inspect AI](https://github.com/UKGovernmentBEIS/inspect_ai) (2k★) | [#3896](https://github.com/UKGovernmentBEIS/inspect_ai/pull/3896) | 修复 filestore recovery append 模式：保留已恢复 message/tool-call 池，同时避免重复哈希旧片段 |
| [Inspect AI](https://github.com/UKGovernmentBEIS/inspect_ai) (2k★) | [#3924](https://github.com/UKGovernmentBEIS/inspect_ai/pull/3924) | 让未知 `GenerateConfig` 字段提前报错，避免拼错的生成参数被静默忽略 |
| [Inspect AI](https://github.com/UKGovernmentBEIS/inspect_ai) (2k★) | [#3941](https://github.com/UKGovernmentBEIS/inspect_ai/pull/3941) | 修复 Bedrock Nova `top_k` 路由：把采样控制传到 inference config，而不是被静默丢弃 |
| [Inspect AI](https://github.com/UKGovernmentBEIS/inspect_ai) (2k★) | [#3975](https://github.com/UKGovernmentBEIS/inspect_ai/pull/3975) | 修复 role model override 合并配置：角色切换模型时保留调用侧 `GenerateConfig` 默认值，不再丢掉 max tokens / reasoning effort 等设置 |
| [Inspect AI](https://github.com/UKGovernmentBEIS/inspect_ai) (2k★) | [#3982](https://github.com/UKGovernmentBEIS/inspect_ai/pull/3982) | 保留 agent bridge 转换中的 OpenAI wrapped reasoning payload，避免 encrypted provider-native reasoning item 在 transcript 转换时丢失 |
| [Phoenix](https://github.com/Arize-ai/phoenix) (9k★) | [#13139](https://github.com/Arize-ai/phoenix/pull/13139) | 修复 Playground 校验错误被吞掉的问题：失败时返回明确错误，而不是空 subscription payload |
| [Phoenix](https://github.com/Arize-ai/phoenix) (9k★) | [#13210](https://github.com/Arize-ai/phoenix/pull/13210) | 修复非法 GraphQL node id 的错误处理：返回 NotFound 风格错误，而不是把 decoder failure 泄漏给客户端 |
| [Phoenix](https://github.com/Arize-ai/phoenix) (9k★) | [#13261](https://github.com/Arize-ai/phoenix/pull/13261) | 修复 span annotation note 新建后的刷新问题：创建成功后立即重新拉取列表，前端不再需要手动刷新才能看到新 note |
| [Phoenix](https://github.com/Arize-ai/phoenix) (9k★) | [#13245](https://github.com/Arize-ai/phoenix/pull/13245) | 修复 generative model fetch 游标回退：低 id 更新不会让后续轮询跳过更新的模型变更 |
| [AstrBot](https://github.com/AstrBotDevs/AstrBot) (28k★) | [#8255](https://github.com/AstrBotDevs/AstrBot/pull/8255) | 支持 RST / AsciiDoc 知识库上传：后端解析白名单和前端文件校验同步扩展，避免支持的文档格式被入口拦截 |
| [AstrBot](https://github.com/AstrBotDevs/AstrBot) (28k★) | [#8195](https://github.com/AstrBotDevs/AstrBot/pull/8195) | 修复空 LLM summary：压缩器在模型返回空摘要时保留原始历史，不再插入空 summary 占位 |
| [AstrBot](https://github.com/AstrBotDevs/AstrBot) (28k★) | [#6596](https://github.com/AstrBotDevs/AstrBot/pull/6596) | 多模态 token 计数：图片/音频/思考链对 context 压缩不可见的问题 |
| [AstrBot](https://github.com/AstrBotDevs/AstrBot) (28k★) | [#7758](https://github.com/AstrBotDevs/AstrBot/pull/7758) | 修复 OpenAI streaming 路径复用 empty-assistant 过滤：reasoning-only 历史不再让严格 provider 返回 400 |
| [AstrBot](https://github.com/AstrBotDevs/AstrBot) (28k★) | [#8073](https://github.com/AstrBotDevs/AstrBot/pull/8073) | 修复纯图片/表情消息的知识库空 prompt：空白文本时跳过 KB 检索，避免 embedding API 400 |
| [AstrBot](https://github.com/AstrBotDevs/AstrBot) (28k★) | [#8061](https://github.com/AstrBotDevs/AstrBot/pull/8061) | 修复 Discord 启动同步命令触发 daily create quota 时打断 bot 启动：只把配额错误降级为 warning，其它异常继续抛出 |
| [AstrBot](https://github.com/AstrBotDevs/AstrBot) (28k★) | [#8172](https://github.com/AstrBotDevs/AstrBot/pull/8172) | 修复 release 使用过期 dashboard dist 的问题：优先加载 bundled WebUI 资产，避免发版后仍展示旧前端 |
| [AstrBot](https://github.com/AstrBotDevs/AstrBot) (28k★) | [#8175](https://github.com/AstrBotDevs/AstrBot/pull/8175) | 修复 WeChat OA 媒体发送失败仍上报成功：prepare/send 超时或失败时向调用方抛出明确错误 |
| [AstrBot](https://github.com/AstrBotDevs/AstrBot) (28k★) | [#8119](https://github.com/AstrBotDevs/AstrBot/pull/8119) | 修复 active reply 图片输入丢失：把图片组件转成 image URLs 传给 LLM，保留原有文本 prompt 行为 |
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
| [AstrBot](https://github.com/AstrBotDevs/AstrBot) (28k★) | [#7398](https://github.com/AstrBotDevs/AstrBot/pull/7398) | 修复 Telegram 流式模式下空文本 sendMessageDraft 导致 400 错误刷屏 |
| [AstrBot](https://github.com/AstrBotDevs/AstrBot) (28k★) | [#7407](https://github.com/AstrBotDevs/AstrBot/pull/7407) | 修复 Gemini 原生搜索无 function tools 时 400：跳过 FunctionCallingConfig |
| [AstrBot](https://github.com/AstrBotDevs/AstrBot) (28k★) | [#7537](https://github.com/AstrBotDevs/AstrBot/pull/7537) | 修复 Telegram media group 异常被 APScheduler 静默吞掉：try/except + EVENT_JOB_ERROR listener |
| [AstrBot](https://github.com/AstrBotDevs/AstrBot) (28k★) | [#6551](https://github.com/AstrBotDevs/AstrBot/pull/6551) | 修复空 content 导致 Grok 400：content 为空时设为 None |
| [ClawTeam](https://github.com/HKUDS/ClawTeam) (4.1k★) | [#1](https://github.com/HKUDS/ClawTeam/pull/1) | 首个 PR：122 个测试、CI、团队模板、config 修复、任务耗时追踪 |
| [ClawTeam](https://github.com/HKUDS/ClawTeam) (4.1k★) | [#40](https://github.com/HKUDS/ClawTeam/pull/40) | 可插拔 TaskStore：将任务持久化抽取为可替换的后端抽象层 |
| [ClawTeam](https://github.com/HKUDS/ClawTeam) (4.1k★) | [#32](https://github.com/HKUDS/ClawTeam/pull/32) | Gemini CLI 支持：spawn、权限、prompt 注入双 backend 适配 |
| [ClawTeam](https://github.com/HKUDS/ClawTeam) (4.1k★) | [#36](https://github.com/HKUDS/ClawTeam/pull/36) | Kimi CLI 支持：spawn backend、权限处理、3 个新测试 |
| [LightRAG](https://github.com/HKUDS/LightRAG) (31k★) | [#2796](https://github.com/HKUDS/LightRAG/pull/2796) | 修复 `None` file_path 传播为 `unknown_source`：补 #2793 遗漏的处理层 |
| [LightRAG](https://github.com/HKUDS/LightRAG) (31k★) | [#3031](https://github.com/HKUDS/LightRAG/pull/3031) | 从 Docling 异步结果 envelope 中抽取 Markdown 正文，避免 RAG chunk 混入 JSON/base64 噪声 |
| [LightRAG](https://github.com/HKUDS/LightRAG) (35k★) | [#3123](https://github.com/HKUDS/LightRAG/pull/3123) | 同步 API 文档暗色主题配色，避免 endpoint 示例在 dark mode 下变得不可读 |
| [OpenHarness](https://github.com/HKUDS/OpenHarness) (11k★) | [#185](https://github.com/HKUDS/OpenHarness/pull/185) | TUI tab 补全三合一修复：光标跳回、去除尾部空格、接受 `/quit` 别名 |
| [OpenClaw](https://github.com/openclaw/openclaw) (343k★) | [#41259](https://github.com/openclaw/openclaw/pull/41259) | 目录创建失败时向上传递错误，避免 memory `ensureDir` 静默失败后继续执行 |
| [OpenClaw](https://github.com/openclaw/openclaw) (343k★) | [#41271](https://github.com/openclaw/openclaw/pull/41271) | 认证配置解析失败时记录日志而非静默吞掉 |

### 领英LinkedIn: https://www.linkedin.com/in/yufenghe
