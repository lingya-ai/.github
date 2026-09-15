<p align="center">
  <a href="https://www.lingya.tech/">
    <img src="https://avatars.githubusercontent.com/u/244903660?s=180&v=4" width="120" alt="Lingya logo">
  </a>
</p>

<h1 align="center">Lingya · 灵涯</h1>

<p align="center">
  让 AI Agent 进入真实业务，也让它始终可治理。<br>
  AI agents for real work—built to stay governed.
</p>

<p align="center">
  <a href="https://www.lingya.tech/">官网</a> ·
  <a href="#开源项目">开源项目</a> ·
  <a href="#open-source">Open source</a>
</p>

## 让智能体可靠地工作

灵涯专注于让企业安全地构建、治理与交付 AI Agent。我们的产品「小灵通」通过 Studio 管理智能体的知识、工具、发布与边界，并通过 Portal 帮助员工完成有依据、可确认的真实工作。

我们在这里开放 Lingya Agents 的 API 契约、多语言服务端 SDK，以及从生产实践中沉淀的 Agent 与 MCP 基础设施。

### 开源项目

| 项目 | 用途 |
| --- | --- |
| [Lingya Agents OpenAPI](https://github.com/lingya-ai/lingya-agents-openapi) | 46 个公开 HMAC API 的规范来源，包含 OpenAPI 3.1 契约、示例和确定性测试向量。 |
| [Kotlin/JVM SDK](https://github.com/lingya-ai/lingya-agents-sdk-kotlin) | 面向 JVM 17 服务端的强类型 SDK，支持协程与 SSE `Flow`。 |
| [TypeScript SDK](https://github.com/lingya-ai/lingya-agents-sdk-typescript) | 面向 Node.js 服务端的强类型 SDK，内置请求签名与 SSE 事件流。 |
| [Python SDK](https://github.com/lingya-ai/lingya-agents-sdk-python) | 基于 Pydantic 模型的服务端 SDK，内置请求签名与 SSE 解码。 |
| [Rust SDK](https://github.com/lingya-ai/lingya-agents-sdk-rust) | 异步、强类型的服务端 SDK，覆盖公开契约并支持 SSE 流。 |
| [lingya-agent](https://github.com/lingya-ai/lingya-agent) | 与框架解耦的 Kotlin Agent 运行时，包含 ReAct、工具、Skill、MCP、工作区与多模型 Provider。 |
| [MCP Gateway](https://github.com/lingya-ai/mcp-gateway) | 原生 MCP 传输网关，在 stdio、SSE、Streamable HTTP 与 WebSocket 之间进行桥接。 |

> **安全提示：** Lingya Agents SDK 仅适用于可信服务端。请勿在浏览器、桌面端或移动端分发 Access Secret，也不要把凭证提交到 Issue、日志或代码仓库。

欢迎在对应仓库提交 Issue 或 Pull Request。各项目的成熟度、安装方式与许可证以其仓库文档为准。

---

## Governable agents for real work

Lingya helps enterprises build, govern, and deliver AI agents safely. Our product, Xiaolingtong, uses Studio to govern agent knowledge, tools, releases, and boundaries, while Portal helps employees complete evidence-backed, reviewable work.

On GitHub, we publish the Lingya Agents API contract, strongly typed server-side SDKs, and agent infrastructure shaped by production experience.

### Open source

| Project | What it provides |
| --- | --- |
| [Lingya Agents OpenAPI](https://github.com/lingya-ai/lingya-agents-openapi) | The source of truth for 46 public HMAC APIs, with an OpenAPI 3.1 contract, examples, and deterministic test vectors. |
| [Kotlin/JVM SDK](https://github.com/lingya-ai/lingya-agents-sdk-kotlin) | A strongly typed JVM 17 SDK with coroutines and SSE `Flow`. |
| [TypeScript SDK](https://github.com/lingya-ai/lingya-agents-sdk-typescript) | A strongly typed Node.js SDK with request signing and SSE event streams. |
| [Python SDK](https://github.com/lingya-ai/lingya-agents-sdk-python) | A server-side SDK with Pydantic models, request signing, and SSE decoding. |
| [Rust SDK](https://github.com/lingya-ai/lingya-agents-sdk-rust) | An async, strongly typed server-side SDK covering the public contract and SSE streams. |
| [lingya-agent](https://github.com/lingya-ai/lingya-agent) | A framework-agnostic Kotlin agent runtime with ReAct, tools, skills, MCP, workspaces, and multiple model providers. |
| [MCP Gateway](https://github.com/lingya-ai/mcp-gateway) | A native transport gateway bridging MCP over stdio, SSE, Streamable HTTP, and WebSocket. |

> **Security:** Lingya Agents SDKs are for trusted servers only. Never distribute an Access Secret in a browser, desktop, or mobile client, and never include credentials in issues, logs, or source control.

Issues and pull requests are welcome in the relevant repository. See each repository for its current maturity, installation instructions, and license.
