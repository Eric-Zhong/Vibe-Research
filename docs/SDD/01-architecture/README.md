# 总体架构与设计原则（Architecture）

在此分析 Vibe-Research 的总体架构与设计原则。

建议内容：
- 分层与组件图（浏览器页面 + 本机服务 + 六阶段编排器 + Python 取数层 + 确定性计算库）。
- 关键架构决策（如「大脑可替换、受控工具/方法论/校验/合规 gate 同一套」）。
- 垂类无关 Core 与 `src/finance/` 的边界约束（见 `AGENTS.md` §5）。
- 参考 `orchestrator/README.md` 的「服务层与接口」。
