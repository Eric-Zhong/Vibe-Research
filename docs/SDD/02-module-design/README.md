# 模块设计（Module Design）

在此分析各顶层模块的职责、内部结构及相互依赖。

建议内容（可每个模块一个文件）：
- `orchestrator/`：六阶段研究编排器、阶段推进、收工检查。
- `desktop/`：浏览器 UI（React/TSX），界面测试约定见 `docs/development-validation.md`。
- `calc/`：确定性计算库（契约见 `calc/SPEC.md`）。
- `backtest/`：回测逻辑与多空辩论归档。
- `providers/`：模型接入 provider 模板（兼容性测试见 `providers/README.md`、`docs/model-access.md`）。
- `.agents/skills/`、`datasources/`：取数与技能。
