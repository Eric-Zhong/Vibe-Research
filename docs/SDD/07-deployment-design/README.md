# 部署设计（Deployment Design）

在此分析项目的部署与运行形态。

建议内容：
- 本地模式：`scripts/setup` / `scripts/start`，默认端口 5930 / 8765 自动换端口（见 `AGENTS.md` §2）。
- 远程模式：`--remote --no-open --public-url`，页面可对外、API 只听回环；访问口令 `.local/access.token`。
- 免安装包：`.github/workflows/portable.yml`、`scripts/portable/`。
- 升级与版本检查（`VRA_UPDATE_CHECK`）。
