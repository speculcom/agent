# Agent 图谱

> 让 AI 替你干活 —— 装在哪、连什么、边界在哪

**agent.specul.com** · 独立信息项目（非厂商官方榜单）

<span data-zh>按角色分三层：自己跑的成品 agent、自己搭的运行时与 SDK、给 agent 装的 MCP 工具。三层的坐标系不同，不做横向排名。</span><span data-en>Three layers by role: finished agents you run yourself, runtimes and SDKs you assemble yourself, and MCP tools you install for an agent. The three layers use different coordinate systems, so this site does not rank across them.</span>

## 三个分区，坐标系不同

| 分区 | 主题 | 对象数 | 主要坐标系 |
|---|---|---|---|
| [Agents](./) | <span data-zh>装在编辑器、终端，或厂商云里</span><span data-en>Installed in an editor, a terminal, or a vendor cloud</span> | 27 | 8 通用维度，按形态分组 |
| [Harness](./harness/) | <span data-zh>运行时、编排框架、SDK</span><span data-en>Runtimes, orchestration frameworks, SDKs</span> | 15 | 8 通用维度，按抽象层分组 |
| [Tools](./tools/) | <span data-zh>缺什么，装什么 —— 给 agent 装的 MCP 工具</span><span data-en>Fill the gap — MCP tools an agent can install</span> | 10 | 8 通用 + 3 MCP 特有 |

**为什么不给一张 33 行的总表**：三层的坐标系不同，混排会制造假的可比性。
成品 agent 与自己搭的底座都能进同一个八维坐标系，但它们解决的不是同一个问题；
MCP 工具层用的是另外三个维度（传输 / 认证 / 权限范围），八维套不上去。

## 方法

- **不给总分排名**——缺少跨工具的统一实测，排名会误导
- **「未知」是合法答案**——查不到就写未知并说明原因，不用推测填充
- **不同层不混排**——三条铁律都写在数据仓 `METHODOLOGY.md` 里

## 数据来源

全部数据来自 **[speculcom/ai-agent-guide](https://github.com/speculcom/ai-agent-guide)**（CC BY 4.0），
由 `sites/build.mjs` 构建，本仓库只存产物。

---

© 2026 Specul · 投机 · 推演
