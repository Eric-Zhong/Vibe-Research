# 软件设计文档（SDD / Software Design Document）

本目录用于存放对 Vibe-Research 整体项目的**软件设计**分析，与 `DDD/` 互补：
DDD 关注业务领域，SDD 关注技术实现层面的设计决策。

> 整体架构、编排器、命令行跑一次研究见 `orchestrator/README.md`；
> 服务层与接口（MCP 8 个工具、本机 HTTP API）也在其中。

## 目录结构（按常规阅读顺序）

| 序号 | 目录 | 用途 |
|------|------|------|
| 01 | `01-architecture/` | 总体架构与设计原则（分层、关键决策） |
| 02 | `02-module-design/` | 模块设计（各顶层模块的职责与内部结构） |
| 03 | `03-component-design/` | 组件设计（关键组件/类的设计与协作） |
| 04 | `04-data-design/` | 数据设计（数据模型、磁盘契约、存储） |
| 05 | `05-interface-design/` | 接口设计（MCP 工具、HTTP API、UI 接口） |
| 06 | `06-security-design/` | 安全设计（凭据、隔离、隐私边界） |
| 07 | `07-deployment-design/` | 部署设计（本地/远程模式、启动、端口、打包） |

## 小白从这里开始
建议**先读完 `docs/DDD/` 再读本目录**。本目录先读 **`00-给小白的导读：怎么读这套设计文档.md`**，再按 `01-` ~ `07-` 子目录顺序看。每个子目录内已放好一篇编号分析文件（如 `01-总体架构.md`）。

## 已生成的分析文件（按编号）
- `00-给小白的导读：怎么读这套设计文档.md`
- `01-architecture/01-总体架构.md`
- `02-module-design/01-模块设计.md`
- `03-component-design/01-组件设计.md`
- `04-data-design/01-数据设计.md`
- `05-interface-design/01-接口设计.md`
- `06-security-design/01-安全设计.md`
- `07-deployment-design/01-部署设计.md`

> 每个子目录的 `README.md` 保留作"该主题要写什么"的提纲；上面的编号文件是已经写好的分析正文。

## 使用方式

将后续对项目的分析结果整理到对应子目录中，每个子目录内放置 `README.md` 及必要的细分文档。
