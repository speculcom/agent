# Agent 图谱 · 自己搭的底座

> <span data-zh>运行时、编排框架、SDK</span><span data-en>Runtimes, orchestration frameworks, SDKs</span>

**agent.specul.com/harness/** · 独立信息项目（非厂商官方榜单）

<span data-zh>Agent 运行时 / 编排框架 / SDK 的责任边界、状态持久化能力与权限模型。收录标准：提供 Agent 运行时或编排层、有官方文档可回溯、近 30 天有实质更新。</span><span data-en>The responsibility boundaries of agent runtimes, orchestration frameworks and SDKs, plus state persistence and permission models. Admission criteria: provides an agent runtime or orchestration layer, has official documentation that can be traced back, and has substantive updates within the last 30 days.</span>

本站共 3 个分区（`agents` / `harness` / `tools`），本 README 描述「Harness」这一个。

## 这个分区提供什么

- **10 个对象**，按固定 8 个维度记录
- 每个维度都能回溯到官方一手源，附来源类型与核验日期
- **不给总分排名**——缺少跨工具的统一实测，排名会误导
- **「未知」是合法答案**——查不到就写未知并说明原因，不用推测填充

## 收录对象

| 对象 | 形态 | 厂商 | 可信度 | 核验日 |
|---|---|---|---|---|
| [Claude Agent SDK](./claude-agent-sdk.html) | 编程底座 | Anthropic | partial | 2026-09-30 |
| [Codex SDK](./codex-sdk.html) | 编程底座 | OpenAI | partial | 2026-10-01 |
| [CrewAI](./crewai.html) | 编排框架 | CrewAI Inc | partial | 2026-10-01 |
| [Deep Agents](./deepagents.html) | 通用 Harness | LangChain | partial | 2026-09-30 |
| [Google ADK（Agent Development Kit）](./google-adk.html) | 编排框架 | Google | partial | 2026-10-01 |
| [Hermes Agent](./hermes-agent.html) | 通用 Harness | Nous Research | partial | 2026-10-01 |
| [LangGraph](./langgraph.html) | 编排框架 | LangChain Inc | partial | 2026-10-01 |
| [LlamaIndex Framework](./llamaindex.html) | 编排框架 | LlamaIndex（run-llama） | partial | 2026-10-01 |
| [OpenAI Agents SDK](./openai-agents-sdk.html) | 编程底座 | OpenAI | partial | 2026-09-30 |
| [OpenHands Agent Canvas](./openhands.html) | 通用 Harness | OpenHands（All-Hands-AI） | partial | 2026-10-01 |

## 可信度标记

| 标记 | 含义 |
|---|---|
| `verified` | all 8 dimensions backed by official sources, checked within 90 days |
| `partial` | some dimensions unknown, or official docs unreachable, or checked over 90 days ago |
| `stale` | 官方已发布重大变化，本站尚未核验 |

当前 10 个对象中，**0 个为 verified**。

## 数据来源

全部数据来自 **[speculcom/ai-agent-guide](https://github.com/speculcom/ai-agent-guide)**（CC BY 4.0），
由 `sites/build.mjs` 从该仓库的 Markdown + frontmatter 构建，本仓库只存产物。

发现错误或有新证据，欢迎去数据仓库提 Issue 或 PR。

## 站内分区

| 分区 | 主题 | 对象数 |
|---|---|---|
| [Agents](/) | <span data-zh>装在编辑器、终端，或厂商云里</span><span data-en>Installed in an editor, a terminal, or a vendor cloud</span> | 17 |
| [Harness](/harness/) | <span data-zh>运行时、编排框架、SDK</span><span data-en>Runtimes, orchestration frameworks, SDKs</span> | 10 |
| [Tools](/tools/) | <span data-zh>缺什么，装什么 —— 给 agent 装的 MCP 工具</span><span data-en>Fill the gap — MCP tools an agent can install</span> | 9 |

---

© 2026 Specul · 投机 · 推演
