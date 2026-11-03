# 限界上下文（Bounded Contexts）

在此分析 Vibe-Research 可以被划分为哪些**限界上下文**，以及每个上下文的职责边界、核心目标与对外依赖。

建议内容：
- 每个上下文的名称、职责与边界（哪些代码/模块从属于它）。
- 上下文的「通用语言」边界（同一个词在不同上下文中含义是否不同）。
- 上下文之间是否有重叠或需要拆分/合并的信号。

可参考的顶层模块：`orchestrator/`、`desktop/`、`calc/`、`backtest/`、`providers/`、`.agents/skills/`、`datasources/`。
