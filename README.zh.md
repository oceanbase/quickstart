# OceanBase 开发者快速索引

[English Version](./README.md)

这份面向开发者的快速指南, 帮助你快速选择合适的 OceanBase SDK、插件, 示例项目或应用项目，用于构建可落地的应用。每项都给出典型使用场景与关键能力，便于快速对比与选型。

欢迎贡献与反馈。如果你有项目想加入清单，或对内容有改进建议，欢迎提交 Issue 或 PR。

## 总览
- [SDK 项目](#sdk-projects)
- [插件项目](#plugin-projects)
- [应用项目](#application-projects)
- [MCP 资源](#mcp-resources)



<a id="sdk-projects"></a>
## SDK 项目

### AI
| 项目 | 使用场景 | 关键特性 |
| --- | --- | --- |
| [langchain-oceanbase](https://github.com/oceanbase/langchain-oceanbase) | 面向 OceanBase 的 LangChain 集成 | LangChain 与 OceanBase 的集成。 |
| [powermem](https://github.com/oceanbase/powermem) | AI 应用的记忆系统 | PowerMem：你的 AI 长期记忆系统——准确、敏捷、低成本。 |
| [pyseekdb](https://github.com/oceanbase/pyseekdb) | Python 新 SDK | 更高效且易用的统一的 Python SDK，支持 OceanBase 或 OceanBase seekdb。 |
| [pyobvector](https://github.com/oceanbase/pyobvector) | Python 旧版 SDK | 面向 OceanBase 多模态存储的 Python SDK，支持向量检索、全文检索和 JSON 表操作，提供 Milvus 兼容 API 与 SQLAlchemy SQL 模式(推荐可以切换PyObsql)，并支持 OceanBase 与 OceanBase seekdb。 |
| [seekdb-js](https://github.com/oceanbase/seekdb-js) | JavaScript/TypeScript SDK | 面向 OceanBase 或 OceanBase seekdb 的 JavaScript/TypeScript SDK。 |
| [obvec_jdbc](https://github.com/oceanbase/obvec_jdbc) | 用于 AI 能力的 Java SDK | 面向 OceanBase 多模态存储的 Java SDK，支持向量检索、全文检索与 JSON 表操作，支持 OceanBase 与 OceanBase seekdb。 |
| [seekdb-rs](https://github.com/ob-labs/seekdb-rs) | Rust SDK | 面向 OceanBase 或 OceanBase seekdb 的 Rust SDK。 |
| [seekdb-go](https://github.com/ob-labs/seekdb-go) | 用于 AI 能力的 Go SDK | 面向 OceanBase 或 OceanBase seekdb 的 Go SDK。 |

### 驱动或 ORM
| 项目 | 使用场景 | 关键特性 |
| --- | --- | --- |
| [OceanBase SQLAlchemy Plugin](https://github.com/oceanbase/ecology-plugins/tree/main/oceanbase-sqlalchemy-plugin) | Python ORM | OceanBase Oracle 模式 SQLAlchemy 方言，兼容 SQLAlchemy 1.3+ 与 2.0+。 |
| [PyObsql OceanBase Plugin](https://github.com/oceanbase/ecology-plugins/tree/main/pyobsql-oceanbase-plugin) | Python SDK | 面向 OceanBase SQL 模式的 Python SDK。 |
| [ob-connector-odbc](https://github.com/oceanbase/ob-connector-odbc) | OceanBase ODBC 驱动 | 用于连接 OceanBase 数据库的 ODBC 驱动，面向 C 应用。 |
| [obconnector-j](https://github.com/oceanbase/obconnector-j) | OceanBase JDBC 驱动 | JDBC 4.2 兼容驱动，支持 OceanBase MySQL 与 Oracle 兼容模式。 |
| [obconnector-c](https://github.com/oceanbase/obconnector-c) | OceanBase C 客户端驱动 | 原生 C 驱动，支持 C 应用连接 OceanBase 数据库。 |
| [go-oceanbase-driver](https://github.com/oceanbase/go-oceanbase-driver) | Go database/sql 接入 | 面向 Go 的 OceanBase 驱动。 |

### KV
| 项目 | 使用场景 | 关键特性 |
| --- | --- | --- |
| [obkv-hbase-client-java](https://github.com/oceanbase/obkv-hbase-client-java) | Java 版 OBKV HBase SDK | 支持 HBase 0.94、1.x、2.x API 访问 OceanBase。 |
| [obkv-table-client-java](https://github.com/oceanbase/obkv-table-client-java) | Java 版 OBKV Table SDK | 高性能访问 OceanBase Table SDK。 |
| [obkv-hbase-client-go](https://github.com/oceanbase/obkv-hbase-client-go) | Go 版 OBKV HBase SDK | 已弃用，不再推荐用于新项目。 |
| [obkv-table-client-go](https://github.com/oceanbase/obkv-table-client-go) | Go 版 OBKV Table SDK | 已弃用，不再推荐用于新项目。 |

<a id="plugin-projects"></a>
## 插件项目
插件将 OceanBase/SeekDB 能力带入开发工作流，提升检索与文档使用效率。

| 插件名称 | 使用场景 | 关键特性 |
| --- | --- | --- |
| [Flyway OceanBase Plugin](https://github.com/oceanbase/ecology-plugins/tree/main/flyway-oceanbase-plugin) | 数据库迁移 | 让 Flyway 支持 OceanBase,  支持 MySQL 或 Oracle 兼容模式。 |
| [WordPress OceanBase Plugin](https://github.com/oceanbase/ecology-plugins/tree/main/wordpress-oceanbase-plugin) | 内容管理 | 让 OceanBase 支持 WordPress,  仅支持 MySQL 模式。 |
| [Metabase OceanBase Plugin](https://github.com/oceanbase/ecology-plugins/tree/main/metabase-oceanbase-plugin) | 数据可视化 | 让 OceanBase 支持 Metabase,  支持 MySQL 或 Oracle 兼容模式。 |
| [LangGraph Checkpoint OceanBase Plugin](https://github.com/oceanbase/ecology-plugins/tree/main/langgraph-checkpoint-oceanbase-plugin) | LangGraph CheckpointSaver | 基于 OceanBase MySQL 模式, LangGraph CheckpointSaver 实现。 |
| [spark-connector-oceanbase](https://github.com/oceanbase/spark-connector-oceanbase) | Spark 数据接入 | OceanBase 的 Apache Spark 连接器。 |
| [flink-connector-oceanbase](https://github.com/oceanbase/flink-connector-oceanbase) | Flink 流式接入 | OceanBase 的 Apache Flink 连接器。 |
| [kafka-connect-oceanbase](https://github.com/oceanbase/kafka-connect-oceanbase) | Kafka Connect 集成 | 支持 OceanBase 双向数据传输的 Kafka Connect 连接器，支持OceanBase MySQL 或 Oracle 模式。 |
| [trino-oceanbase](https://github.com/oceanbase/trino-oceanbase) | Trino 查询引擎集成 | 让 Trino 连接 OceanBase（MySQL/Oracle 模式）。 |
| [OceanBase SQL Helper Plugin](https://github.com/oceanbase/ecology-plugins/tree/main/oceanbase-sql-helper-plugin/README.md)  | 开发工具 | 帮助开发者快速查找 OceanBase SQL 关键字文档的 VS Code 扩展。 |
| [seekdb Claude Code Plugin](https://github.com/oceanbase/ecology-plugins/tree/main/claudecode-plugin) | 开发工具 | 本插件包含 seekdb 的 Claude Code 技能，，旨在增强 Claude Code 在 seekdb 数据库场景下的能力 |
| [seekdb Cursor Extension](https://github.com/oceanbase/seekdb-ecology-plugins/tree/main/cursor-extension) | 开发工具 | 为 seekdb 提供 Agent 插件支持，便于在 Agent 应用中使用 seekdb 数据库。 |

### Dify
| 项目 | 使用场景 | 关键特性 |
| --- | --- | --- |
| [dify-on-mysql](https://github.com/oceanbase/dify-on-mysql) | 基于 OceanBase MySQL 模式 的 Dify  | 这是 Dify 的一个分支，通过将全部存储组件替换为 OceanBase，并引入多项企业特性：高可用、可扩展性能提升、基于 OceanBase 的多租户支持。 |
| [dify-plugin-powermem](https://github.com/oceanbase/dify-plugin-powermem) | Dify 记忆集成 | PowerMem 的 Dify 插件。 |
| [dify-plugin-oceanbase](https://github.com/oceanbase/dify-plugin-oceanbase) | Dify OceanBase 连接器 | 一个连接并查询 OceanBase 的 Dify 插件。 |
| [dify-plugin-daemon](https://github.com/oceanbase/dify-plugin-daemon) | Dify 插件运行时 |  |

<a id="application-projects"></a>
## 应用或示例项目
Demo 是验证能力与快速搭建 PoC/原型的最快方式。

| 项目 | 使用场景 | 关键特性 |
| --- | --- | --- |
| [ob-samples](https://github.com/oceanbase/ob-samples) | OceanBase 示例与最佳实践 | 展示 OceanBase 的使用方式，提供示例项目。 |
| [image-search](https://github.com/oceanbase/image-search) | 图像相似检索 | 基于 OceanBase 向量能力的图像检索应用。 |
| [ob-multi-model-search-demo](https://github.com/oceanbase/ob-multi-model-search-demo) | 多模态检索 Demo | OceanBase Demo 集合 |
| [oceanbase-demos](https://github.com/oceanbase/oceanbase-demos) | OceanBase Demo 集合 | OceanBase Demo 集合 |
| [devcon](https://github.com/oceanbase/devcon) | 开发者大会内容与 Demo |  |
| [ai-workshop-2024](https://github.com/oceanbase/ai-workshop-2024) | RAG workshop 教程 | OceanBase 2024 产品发布会 AI Workshop 项目 |
| [mine-kb](https://github.com/ob-labs/mine-kb) | 本地知识库应用 | 基于 SeekDB 的本地个人知识库应用。 |

<a id="mcp-resources"></a>
## MCP 资源
Model Context Protocol (MCP) 集成帮助 AI 工具与智能体连接 OceanBase/SeekDB 的数据与能力。如果你有 MCP 服务器、客户端或示例集成，欢迎贡献，方便他人复用。

[awesome-oceanbase-mcp](https://github.com/oceanbase/awesome-oceanbase-mcp)


<table>
<thead>
<tr>
<th width="25%">🔧 MCP 服务端</th>
<th width="60%">📝 说明</th>
<th width="15%">📚 文档</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>OceanBase MCP Server</strong></td>
<td>提供与 OceanBase 数据库安全交互的能力，支持 SQL 查询与数据管理操作</td>
<td><a href="https://github.com/oceanbase/awesome-oceanbase-mcp/blob/main/src/oceanbase_mcp_server/README.md">📖 查看</a></td>
</tr>
<tr>
<td><strong>OCP MCP Server</strong></td>
<td>与 OceanBase 云平台集成，提供集群管理与监控能力</td>
<td><a href="https://github.com/oceanbase/awesome-oceanbase-mcp/blob/main/src/ocp_mcp_server/README.md">📖 查看</a></td>
</tr>
<tr>
<td><strong>OBCloud MCP Server</strong></td>
<td>连接 OBCloud 服务，提供云数据库管理功能</td>
<td><a href="https://github.com/oceanbase/awesome-oceanbase-mcp/blob/main/src/obcloud_mcp_server/README.md">📖 查看</a></td>
</tr>
<tr>
<td><strong>OKCTL MCP Server</strong></td>
<td>在 Kubernetes 环境中管理 OceanBase 资源与部署</td>
<td><a href="https://github.com/oceanbase/awesome-oceanbase-mcp/blob/main/doc/okctl_mcp_server.md">📖 查看</a></td>
</tr>
<tr>
<td><strong>OBDIAG MCP Server</strong></td>
<td>提供 OceanBase 诊断工具集成，支持性能分析与故障排查</td>
<td><a href="https://github.com/oceanbase/awesome-oceanbase-mcp/blob/main/doc/obdiag_mcp_server.md">📖 查看</a></td>
</tr>
<tr>
<td><strong>obshell MCP Server</strong></td>
<td>通过 obshell 支持 OceanBase 集群创建、部署与运维管理</td>
<td><a href="https://github.com/oceanbase/awesome-oceanbase-mcp/blob/main/doc/obshell_mcp_server.md">📖 查看</a></td>
</tr>
<tr>
<td><strong>seekdb MCP Server</strong></td>
<td>为 seekdb 数据库提供向量操作、集合管理、SQL 查询与 AI 功能</td>
<td><a href="https://github.com/oceanbase/awesome-oceanbase-mcp/blob/main/src/seekdb_mcp_server/README.md">📖 查看</a></td>
</tr>
<tr>
<td><strong>PowerMem MCP Server</strong></td>
<td>提供 AI 记忆管理能力，支持记忆存储、检索与基于艾宾浩斯遗忘曲线的智能检索</td>
<td><a href="https://github.com/oceanbase/awesome-oceanbase-mcp/blob/main/src/powermem_mcp_server/README.md">📖 查看</a></td>
</tr>
</tbody>
</table>

<a id="contributing"></a>
## 贡献
我们欢迎 SDK、插件、Demo、教程与真实案例。请提交 PR，并简要说明使用场景与展示的关键能力。


## 社区与支持
<div align="center">

<p>
    <a href="https://h5.dingtalk.com/circle/joinCircle.html?corpId=ding320493024256007024f2f5cc6abecb85&token=be84625101d2c2b2b675e1835e5b7988&groupCode=v1,k1,EoWBexMbnAnivFZPFszVivlsxkpAYNcvXRdF071nRRY=&from=group&ext=%7B%22channel%22%3A%22QR_GROUP_NORMAL%22%2C%22extension%22%3A%7B%22groupCode%22%3A%22v1%2Ck1%2CEoWBexMbnAnivFZPFszVivlsxkpAYNcvXRdF071nRRY%3D%22%2C%22groupFrom%22%3A%22group%22%7D%2C%22inviteId%22%3A1057855%2C%22orgId%22%3A313467091%2C%22shareType%22%3A%22GROUP%22%7D&origin=11?#/">
        <img src="https://img.shields.io/badge/钉钉群-33254054-0084FF?style=for-the-badge&logo=dingtalk&logoColor=white" alt="钉钉群 33254054" />
    </a>
    <a href="https://ask.oceanbase.com/">
        <img src="https://img.shields.io/badge/社区-问答论坛-FF6900?style=for-the-badge" alt="Forum" />
    </a>
</p>

</div>

</div>
