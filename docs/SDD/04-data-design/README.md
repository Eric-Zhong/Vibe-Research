# 数据设计（Data Design）

在此分析项目的数据模型与存储设计。

建议内容：
- 研究运行的磁盘契约：manifest / evidence / calculations / report（见 `methodology/constitution.md` §4）。
- 私有数据落点 `.local/`（配置、运行产物、对话、台账、上传资料），已被 git 忽略，不得外传。
- 取数端点与数据源（见 `.agents/skills/data-access/SKILL.md`、`datasources/`）。
- 报告正文上限（长报告约 10 万字符，不得为通过校验而截断）。
