<p align="center">
  <a href="https://www.lingya.tech/">
    <img src="https://avatars.githubusercontent.com/u/244903660?s=180&v=4" width="120" alt="Lingya logo">
  </a>
</p>

<h1 align="center">Lingya · 灵涯</h1>

<p align="center">
  <strong>让每个想法，都能低成本变成 AI 产品</strong><br>
  Turn every idea into an AI product—at low cost.
</p>

<p align="center">
  <a href="https://www.lingya.tech/">官网</a> ·
  <a href="https://lingya.cloud/">SaaS 平台</a> ·
  <a href="https://lingya-ai.github.io/xlt-agent-ui/">UI 文档与演示</a> ·
  <a href="https://lingya-ai.github.io/lingya-agents-openapi/">API 文档</a>
</p>

灵涯致力于降低 AI 产品的开发与接入成本。我们将产品「小灵通」实践中的接口契约、多语言 SDK、React 交互组件、Agent 运行时与 MCP 网关逐步开放，让开发者复用已有能力，更快地把想法做成可用的产品。

从接入智能体、搭建交互界面，到扩展工具与运行时，你可以根据项目需要选择合适的起点。

## 小灵通 SaaS 平台

[lingya.cloud](https://lingya.cloud/) 是小灵通的在线 AI Agent SaaS 平台，支持创建独立租户空间，由平台统一维护与升级。

- **构建与发布：** 在 Studio 中配置模型、提示词、知识库、Skill 与 MCP 工具，预览验证后发布 Agent 版本
- **接入业务系统：** 通过 OpenAPI 与官方 SDK 调用已发布的 Agent，将流式结果接入自己的应用
- **团队使用：** 员工通过 Portal 使用已发布的企业专家、知识与工具，延续会话，并按需配置定时任务
- **持续治理：** 管理发布版本、接入方与凭证，回看会话及工具活动

希望直接使用托管平台，可以从 [进入 SaaS 平台](https://lingya.cloud/) 开始；希望在自己的应用中集成 Agent，可以从下方开源项目开始。平台也提供私有化部署交付方式。

## 从你的目标开始

| 你想做什么 | 推荐入口 |
| --- | --- |
| 构建 Agent 对话界面 | [XLT Agent UI](https://github.com/lingya-ai/xlt-agent-ui)：通过 shadcn Registry 安装可自行维护的 React 组件源码，组合会话、消息、审批、工作区和文件预览等交互 |
| 在业务系统中调用 Agent | 多语言 SDK：[TypeScript](https://github.com/lingya-ai/lingya-agents-sdk-typescript) · [Python](https://github.com/lingya-ai/lingya-agents-sdk-python) · [Kotlin/JVM](https://github.com/lingya-ai/lingya-agents-sdk-kotlin) · [Rust](https://github.com/lingya-ai/lingya-agents-sdk-rust) |
| 查阅接口或自行实现客户端 | [Lingya Agents OpenAPI](https://github.com/lingya-ai/lingya-agents-openapi)：统一接口契约、认证规则、请求示例与流式事件说明 |
| 构建或扩展 Kotlin Agent 运行时 | [lingya-agent](https://github.com/lingya-ai/lingya-agent)：**🚧 尚未完成 · 暂不可用**：正在从产品实现中逐步剥离出开源核心，涵盖 ReAct、工具调用、Skill、MCP、工作区与模型 Provider |
| 连接不同传输方式的 MCP 服务 | [MCP Gateway](https://github.com/lingya-ai/mcp-gateway)：连接 stdio、SSE 与 Streamable HTTP，并支持 WebSocket 输出 |

## 开始接入

- **使用托管平台：** 访问 [小灵通 SaaS 平台](https://lingya.cloud/)
- **构建界面：** 查看 [UI 文档与交互演示](https://lingya-ai.github.io/xlt-agent-ui/)
- **接入接口：** 查看 [API 文档](https://lingya-ai.github.io/lingya-agents-openapi/)，选择适合你的 SDK
- **了解产品：** 访问 [灵涯官网](https://www.lingya.tech/)

浏览器接入使用由可信服务端签发的一次性令牌；Access Secret 仅保存在可信服务端。平台接入条件、项目成熟度、安装方式与许可证请参阅各仓库文档。

欢迎通过对应仓库的 Issue 和 Pull Request 反馈问题、讨论改进并参与贡献。

## About Lingya

[Xiaolingtong SaaS](https://lingya.cloud/) provides a hosted platform with independent tenant spaces, maintained and upgraded by the platform. Build and publish agents in Studio, integrate them into business applications through OpenAPI and official SDKs, and let teams use published capabilities in Portal. The platform also provides version, credential, and conversation management, with private deployment available as an alternative delivery option.

Lingya lowers the cost of building and integrating AI products. We open-source API contracts, multilingual SDKs, React UI components, an Agent runtime, and an MCP gateway shaped by our product, Xiaolingtong, so developers can reuse existing capabilities and turn ideas into working products faster.

Start with [XLT Agent UI](https://github.com/lingya-ai/xlt-agent-ui) to build an interface, explore the [API reference](https://lingya-ai.github.io/lingya-agents-openapi/) and SDKs to integrate agents, or extend the [Kotlin runtime](https://github.com/lingya-ai/lingya-agent) and [MCP Gateway](https://github.com/lingya-ai/mcp-gateway) for your infrastructure. **🚧 Incomplete · Not yet available for use:** The Kotlin Agent runtime is being progressively extracted from the product implementation into an open-source core.

Browser integrations use single-use tokens issued by a trusted server. Keep Access Secrets on trusted servers only. See each repository for access requirements, maturity, installation instructions, and license. Issues and pull requests are welcome.
