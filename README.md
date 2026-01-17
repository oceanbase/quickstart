# OceanBase Developer Quickstart 🧭

[中文版本](./README.zh.md)

This developer-oriented guideline helps you pick the right SDKs, plugins, demos or applications to build practical applications on OceanBase. Each entry highlights typical use cases and key capabilities so you can choose quickly.

We welcome contributions and feedback. If you have a project to add or ideas to improve this index, please open an issue or a PR.

## Overview 🧾
- [SDK Projects](#sdk-projects)
- [Plugin Projects](#plugin-projects)
- [Application Projects](#application-projects)
- [MCP Resources](#mcp-resources)



<a id="sdk-projects"></a>
## SDK Projects 🧩

### AI 🤖
| Project | Use Case | Key Features |
| --- | --- | --- |
| [langchain-oceanbase](https://github.com/oceanbase/langchain-oceanbase) | LangChain integration for OceanBase | LangChain integration with OceanBase. |
| [powermem](https://github.com/oceanbase/powermem) | Memory system for AI apps | PowerMem: Your AI-Powered Long-Term Memory — Accurate, Agile, Affordable. |
| [pyseekdb](https://github.com/oceanbase/pyseekdb) | New SDK for Python | A unified python SDK supports OceanBase or OceanBase seekdb, more efficient and easy-to-use. |
| [pyobvector](https://github.com/oceanbase/pyobvector) | Old SDK for Python | A Python SDK for OceanBase Multimodal Store—enabling vector search, full-text search, and JSON table operations—offers both Milvus-compatible API and SQLAlchemy-based SQL mode, and supports both OceanBase and OceanBase seekdb. |
| [seekdb-js](https://github.com/oceanbase/seekdb-js) | SDK for JavaScript/TypeScript | The JavaScript/TypeScript SDK for OceanBase or OceanBase seekdb. |
| [obvec_jdbc](https://github.com/oceanbase/obvec_jdbc) | Java SDK for AI operation | A Java SDK for OceanBase Multimodal Store—enabling vector search, full-text search, and JSON table operations—supports both OceanBase and OceanBase seekdb. |
| [seekdb-rs](https://github.com/ob-labs/seekdb-rs) | Rust SDK  | The Rust SDK for OceanBase or OceanBase seekdb. |
| [seekdb-go](https://github.com/ob-labs/seekdb-go) | Go SDK for AI operation| The Go SDK for OceanBase or OceanBase seekdb. |

### Driver or ORM 🔌
| Project | Use Case | Key Features |
| --- | --- | --- |
| [OceanBase SQLAlchemy Plugin](https://github.com/oceanbase/ecology-plugins/tree/main/oceanbase-sqlalchemy-plugin) | Python ORM | SQLAlchemy ORM for OceanBase Oracle mode, compatible with SQLAlchemy 1.3+ and 2.0+ |
| [PyObsql OceanBase Plugin](https://github.com/oceanbase/ecology-plugins/tree/main/pyobsql-oceanbase-plugin)                             | Python SDK                | A Python SDK for OceanBase SQL mode |
| [ob-connector-odbc](https://github.com/oceanbase/ob-connector-odbc) | ODBC driver for OceanBase | An ODBC driver for connecting C applications to OceanBase Database. |
| [obconnector-j](https://github.com/oceanbase/obconnector-j) | JDBC driver for OceanBase | OceanBase Client for Java is a JDBC 4.2–compatible driver that enables Java applications to connect to the OceanBase Database Server, supporting OceanBase both MySQL and Oracle compatibility modes. |
| [obconnector-c](https://github.com/oceanbase/obconnector-c) | C client driver for OceanBase | OceanBase Client for C is a native driver that enables C applications to connect to the OceanBase Database. |
| [go-oceanbase-driver](https://github.com/oceanbase/go-oceanbase-driver) | Go database/sql access to OceanBase | Go OceanBase Driver is a OceanBase driver for Go's (golang) database/sql package |

### KV 🗂️
| Project | Use Case | Key Features |
| --- | --- | --- |
| [obkv-hbase-client-java](https://github.com/oceanbase/obkv-hbase-client-java) | OBKV HBase SDK in Java | OBKV HBase Client is a Java library that enables access to OceanBase data by the HBase 0.94, 1.x, or 2.x APIs. |
| [obkv-table-client-java](https://github.com/oceanbase/obkv-table-client-java) | OBKV Table SDK in Java | The OBKV Table Client is a Java library that provides high-performance access to table and key-value data in OceanBase’s storage layer. |
| [obkv-hbase-client-go](https://github.com/oceanbase/obkv-hbase-client-go) | OBKV HBase SDK in Go | This project is deprecated and no longer recommended for new development. |
| [obkv-table-client-go](https://github.com/oceanbase/obkv-table-client-go) | OBKV Table SDK in Go | This project is deprecated and no longer recommended for new development. |

<a id="application-projects"></a>
## Applicaiton or Demo Projects 🧪
Demos are the fastest way to validate capabilities and bootstrap a PoC or prototype.

| Project | Use Case | Key Features |
| --- | --- | --- |
| [image-search](https://github.com/ob-labs/image-search) | Image similarity search | Image search application built with the vector capabilities of OceanBase |
| [ob-samples](https://github.com/oceanbase/ob-samples) | OceanBase samples and best practices | Show how to use OceanBase, providing the sample projects for OceanBase. |
| [ob-multi-model-search-demo](https://github.com/oceanbase/ob-multi-model-search-demo) | Multimodal search demo |  |
| [oceanbase-demos](https://github.com/oceanbase/oceanbase-demos) | OceanBase demo collection | OceanBase Demos |
| [devcon](https://github.com/oceanbase/devcon) | Developer conference content and demos |  |
| [ai-workshop-2024](https://github.com/oceanbase/ai-workshop-2024) | RAG workshop and tutorial | AI Workshop Project of OceanBase 2024 Product Launch |
| [mine-kb](https://github.com/ob-labs/mine-kb) | Local knowledge base app | A local personal knowledge base on SeekDB. |


<a id="plugin-projects"></a>
## Plugin Projects 🔌
Plugins bring OceanBase/SeekDB capabilities into the developer workflow to improve search and documentation usage.

| Plugin Name | Use Case | Key Features |
| --- | --- | --- |
| [Flyway OceanBase Plugin](https://github.com/oceanbase/ecology-plugins/tree/main/flyway-oceanbase-plugin) | Database Migration | This plugin enables Flyway to support OceanBase in both MySQL and Oracle compatibility modes. |
| [WordPress OceanBase Plugin](https://github.com/oceanbase/ecology-plugins/tree/main/wordpress-oceanbase-plugin) | Content Management | This plugin enables WordPress to support OceanBase in both MySQL modes. |
| [Metabase OceanBase Plugin](https://github.com/oceanbase/ecology-plugins/tree/main/metabase-oceanbase-plugin) | Data Visualization | This plugin enables [Metabase](https://www.metabase.com) to support OceanBase in both MySQL and Oracle compatibility modes. |
| [LangGraph Checkpoint OceanBase Plugin](https://github.com/oceanbase/ecology-plugins/tree/main/langgraph-checkpoint-oceanbase-plugin) | LangGraph CheckpointSaver | Implementation of LangGraph CheckpointSaver in OceanBase MySQL mode |
| [spark-connector-oceanbase](https://github.com/oceanbase/spark-connector-oceanbase) | Data ingestion with Spark | Apache Spark Connectors for OceanBase. |
| [flink-connector-oceanbase](https://github.com/oceanbase/flink-connector-oceanbase) | Streaming ingestion with Flink | Apache Flink Connectors for OceanBase. |
| [kafka-connect-oceanbase](https://github.com/oceanbase/kafka-connect-oceanbase) | Kafka Connect integration | kafka-connect-oceanbase is a [Kafka Connector](http://kafka.apache.org/documentation.html#connect) that enables bidirectional data transfer between Apache Kafka and OceanBase, supporting both MySQL and Oracle compatibility modes. |
| [trino-oceanbase](https://github.com/oceanbase/trino-oceanbase) | Trino query engine integration | Enables Trino to connect to OceanBase (MySQL/Oracle mode)  |
| [OceanBase SQL Helper Plugin](https://github.com/oceanbase/ecology-plugins/tree/main/oceanbase-sql-helper-plugin) | Development Tools | A VSCode extension that helps developers quickly find OceanBase SQL keywords documentation. |
| [seekdb Claude Code Plugin](https://github.com/oceanbase/seekdb-ecology-plugins/tree/main/claudecode-plugin) | Development Tools | This plugin contains seekdb skill that is designed specifically for Claude Code, aimed at enhancing Claude's capabilities in seekdb database scenarios.  |
| [seekdb Cursor Extension](https://github.com/oceanbase/seekdb-ecology-plugins/tree/main/cursor-extension) | Development Tools | Provide Agent plugin support for seekdb, facilitating developers' use of the seekdb database within the Agent APP. |

### Dify 🧠
| Project | Use Case | Key Features |
| --- | --- | --- |
| [dify-on-mysql](https://github.com/oceanbase/dify-on-mysql) | Dify deployment on OceanBase MySQL mode | This is a branch for Dify, which provides several enhancements for Dify by replacing all storage components with OceanBase and introducing numerous enterprise features: High availability Scalable performance improvement Multi-tenancy support through OceanBase |
| [dify-plugin-powermem](https://github.com/oceanbase/dify-plugin-powermem) | Dify memory integration | Dify plugin for powermem |
| [dify-plugin-oceanbase](https://github.com/oceanbase/dify-plugin-oceanbase) | Dify OceanBase connector | A Dify plugin that connects to and queries OceanBase. |
| [dify-plugin-daemon](https://github.com/oceanbase/dify-plugin-daemon) | Dify plugin runtime |  |


<a id="mcp-resources"></a>
## MCP Resources 🧰
Model Context Protocol (MCP) integrations help AI tools and agents connect to OceanBase/SeekDB data and capabilities. If you have MCP servers, clients, or example integrations, please contribute them here so others can reuse them.

[awesome-oceanbase-mcp](https://github.com/oceanbase/awesome-oceanbase-mcp)


<table>
<thead>
<tr>
<th width="25%">🔧 MCP Server</th>
<th width="60%">📝 Description</th>
<th width="15%">📚 Documentation</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>OceanBase MCP Server</strong></td>
<td>Provides secure interaction capabilities with OceanBase databases, supporting SQL queries, data management operations</td>
<td><a href="https://github.com/oceanbase/awesome-oceanbase-mcp/blob/main/src/oceanbase_mcp_server/README.md">📖 View</a></td>
</tr>
<tr>
<td><strong>OCP MCP Server</strong></td>
<td>Integrates with OceanBase Cloud Platform, providing cluster management and monitoring capabilities</td>
<td><a href="https://github.com/oceanbase/awesome-oceanbase-mcp/blob/main/src/ocp_mcp_server/README.md">📖 View</a></td>
</tr>
<tr>
<td><strong>OBCloud MCP Server</strong></td>
<td>Connects to OBCloud services, providing cloud database management functionality</td>
<td><a href="https://github.com/oceanbase/awesome-oceanbase-mcp/blob/main/src/obcloud_mcp_server/README.md">📖 View</a></td>
</tr>
<tr>
<td><strong>OKCTL MCP Server</strong></td>
<td>Manages OceanBase resources and deployments in Kubernetes environments</td>
<td><a href="https://github.com/oceanbase/awesome-oceanbase-mcp/blob/main/doc/okctl_mcp_server.md">📖 View</a></td>
</tr>
<tr>
<td><strong>OBDIAG MCP Server</strong></td>
<td>Provides OceanBase diagnostic tool integration, supporting performance analysis and troubleshooting</td>
<td><a href="https://github.com/oceanbase/awesome-oceanbase-mcp/blob/main/doc/obdiag_mcp_server.md">📖 View</a></td>
</tr>
<tr>
<td><strong>obshell MCP Server</strong></td>
<td>Enables OceanBase cluster creation, deployment and operations management through obshell</td>
<td><a href="https://github.com/oceanbase/awesome-oceanbase-mcp/blob/main/doc/obshell_mcp_server.md">📖 View</a></td>
</tr>
<tr>
<td><strong>seekdb MCP Server</strong></td>
<td>Provides vector operations, collection management, SQL queries and AI functions for seekdb database</td>
<td><a href="https://github.com/oceanbase/awesome-oceanbase-mcp/blob/main/src/seekdb_mcp_server/README.md">📖 View</a></td>
</tr>
<tr>
<td><strong>PowerMem MCP Server</strong></td>
<td>Provides AI memory management capabilities, supporting memory storage, search, and intelligent retrieval with Ebbinghaus forgetting curve</td>
<td><a href="https://github.com/oceanbase/awesome-oceanbase-mcp/blob/main/src/powermem_mcp_server/README.md">📖 View</a></td>
</tr>
</tbody>
</table>

<a id="contributing"></a>
## Contributing 🤝
We welcome SDKs, plugins, demos, tutorials, and real-world case studies. Please submit a PR with a short description of the use case and the key capabilities it demonstrates.


## Community & Support 💬
<div align="center">

<p>
    <a href="https://discord.gg/74cF8vbNEs">
        <img src="https://img.shields.io/badge/Discord-Join%20Chat-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" />
    </a>
    <a href="https://github.com/oceanbase/seekdb/discussions">
        <img src="https://img.shields.io/badge/GitHub%20Discussion-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Discussion" />
    </a>
    <a href="https://ask.oceanbase.com/">
        <img src="https://img.shields.io/badge/Forum-Chinese%20Community-FF6900?style=for-the-badge" alt="Forum" />
    </a>
</p>

</div>
