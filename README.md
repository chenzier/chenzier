### chenzier (chenwang)

在做 AI Agent 运行时与 Harness Engineering：关心 agent 的权限归谁、上下文怎么管、
任务和会话的生命周期由谁编排，以及一次真实的工具使用如何沉淀成可复用的架构。

**在做的项目**

| 项目 | 说明 |
| --- | --- |
| [kumin](https://github.com/chenzier/kumin) | 任务优先的 Agent Runtime。Agent 是可寻址的定义而非常驻进程，Task 代表工作、Run 代表一次执行尝试；先落 ADR 与垂直切片票据队列，再写实现。 |
| [bestman](https://github.com/chenzier/bestman) | Rust 写的「宠物船 + 健身打卡」CLI/TUI。事件溯源日志 + SQLite 投影，可从 `events.jsonl` 重建，终端里能画船。 |
| [我的博客](https://chenzier.github.io) | 说唱、旅行、读书，以及开发程序。近期写 AI 编码工具的迁移记录与 Harness 自进化实践。 |

**贡献过的上游**

- [agentscope-ai/QwenPaw#7614](https://github.com/agentscope-ai/QwenPaw/pull/7614) — `fix(computer-use): add control action to restart the native helper`
- [QoderAI/better-harness#157](https://github.com/QoderAI/better-harness/pull/157) — `fix(session-analysis): recognize lowercase edit tool names from Pi sessions`
- [javiermolinar/pi-cmux#16](https://github.com/javiermolinar/pi-cmux/pull/16) · [#14](https://github.com/javiermolinar/pi-cmux/pull/14) — cmux 下的通知边界与 opt-in 会话标题

**常用**　TypeScript · Rust · Python · Astro
