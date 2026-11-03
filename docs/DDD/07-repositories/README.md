# 仓储（Repositories）

在此分析领域对象的**持久化与检索抽象（Repository）**，关注接口而非具体存储。

建议内容：
- 各聚合/实体的仓储接口与生命周期管理。
- 实际落点：`.local/`（私有数据，已被 git 忽略）中的 manifest / evidence / calculations / report 等磁盘契约（见 `methodology/constitution.md` §4）。
- 取数脚本与数据源如何被仓储或编排器调用（见 `.agents/skills/data-access/SKILL.md`）。
