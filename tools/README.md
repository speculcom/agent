# Agent 图谱 · 给 agent 装的工具

> 缺什么，装什么 —— 给 agent 装的 MCP 工具

**agent.specul.com/tools/** · 独立信息项目（非厂商官方榜单）

MCP server 的权限范围、传输方式与输出可用性。收录标准：已发布为可安装的 MCP server、有官方仓库或文档可回溯、近 30 天有实质更新。这里是能力缺口查表，不是选型对比。

本站共 3 个分区（`agents` / `harness` / `tools`），本 README 描述「Tools」这一个。

## 这个分区提供什么

- **9 个对象**，按固定 11 个维度记录（8 个通用维度 + 3 个 MCP 特有维度）
- 每个维度都能回溯到官方一手源，附来源类型与核验日期
- **不给总分排名**——缺少跨工具的统一实测，排名会误导
- **「未知」是合法答案**——查不到就写未知并说明原因，不用推测填充

## 收录对象

| 对象 | 形态 | 厂商 | 可信度 | 核验日 |
|---|---|---|---|---|
| [Context7](./context7.html) | MCP | Upstash | partial | 2026-10-01 |
| [Everything MCP Server](./everything.html) | MCP | Model Context Protocol | verified | 2026-09-29 |
| [Fetch MCP Server](./fetch.html) | MCP | Model Context Protocol | verified | 2026-09-29 |
| [Filesystem MCP Server](./filesystem.html) | MCP | Model Context Protocol | verified | 2026-09-29 |
| [Git MCP Server](./git.html) | MCP | Model Context Protocol | verified | 2026-09-29 |
| [Knowledge Graph Memory Server](./memory.html) | MCP | Model Context Protocol | verified | 2026-09-29 |
| [Playwright MCP Server](./playwright.html) | MCP | Microsoft | verified | 2026-09-29 |
| [Sequential Thinking MCP Server](./sequential-thinking.html) | MCP | Model Context Protocol | verified | 2026-09-29 |
| [Time MCP Server](./time.html) | MCP | Model Context Protocol | verified | 2026-09-29 |

## 可信度标记

| 标记 | 含义 |
|---|---|
| `verified` | 11 个维度均有官方源支撑，核验日在 90 天内 |
| `partial` | 部分维度标为未知，或官方文档不可访问，或核验日超过 90 天 |
| `stale` | 官方已发布重大变化，本站尚未核验 |

当前 9 个对象中，**8 个为 verified**。

## 数据来源

全部数据来自 **[speculcom/ai-agent-guide](https://github.com/speculcom/ai-agent-guide)**（CC BY 4.0），
由 `sites/build.mjs` 从该仓库的 Markdown + frontmatter 构建，本仓库只存产物。

发现错误或有新证据，欢迎去数据仓库提 Issue 或 PR。

## 站内分区

| 分区 | 主题 | 对象数 |
|---|---|---|
| [Agents](/) | 装在编辑器、终端，或厂商云里 | 17 |
| [Harness](/harness/) | 运行时、编排框架、SDK | 10 |
| [Tools](/tools/) | 缺什么，装什么 —— 给 agent 装的 MCP 工具 | 9 |

---

© 2026 Specul · 投机 · 推演
