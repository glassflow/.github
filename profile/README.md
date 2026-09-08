<a href="https://glassflow.ai">
  <img alt="GlassFlow Logo" src="https://raw.githubusercontent.com/glassflow/.github/main/profile/assets/banner.png">
<a href="https://www.linkedin.com/company/glassflow-dev" target="_blank">
<img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white">
</a>
<a href="https://twitter.com/glassflowdev" target="_blank">
<img alt="Twitter" src="https://img.shields.io/badge/Twitter-1DA1F2?logo=twitter&logoColor=white">
</a>
</p>


# GlassFlow Overview: Data Infrastructure for production-grade AI agents, running for hours, not seconds.

GlassFlow is an AI-native data infrastructure company building the observability and data plane for production AI agents. We make two products for teams running agents that work for hours, not seconds: Rius for agent observability, and Tares for the agent data plane.

Two products. One umbrella.

## Rius: Agent observability
Rius is a managed observability platform for AI agents running. There's nothing to host and no infrastructure to run. You simply point your agents at Rius and you can see what they decided, why they failed, and how quality is trending, even while they're still running. It's built for long-running, always-on agents rather than short chat sessions.

### Key Features
- **Long-running agent support**: traces and metrics that keep updating mid-run, so you're not waiting for an agent to finish to see what it's doing.
- **Liveness heartbeats**: tell a clean shutdown apart from a silent crash, instead of a frozen agent looking identical to a healthy one.
- **MCP in both directions**: agents send traces in, and coding agents like Claude Code query Rius back out to investigate failures and open a fix.
- **Privacy controls**: decide what gets captured and what stays redacted before it ever leaves your agent.
- **Shared views**: send a read-only link to a trace so a teammate can see exactly what you saw.

→ [Get started]([https://glassflow.ai](https://eu.console.rius-glassflow.com/signin?utm_source=github&utm_medium=website&utm_campaign=github_get_started)) · [Docs](https://docs.glassflow.ai/rius)

## Tares: Agent data plane
Tares is an open-source data plane for AI agents that runs locally. Instead of an agent calling each tool one by one at runtime, Tares prepares and serves the exact data package the agent needs, when it needs it. The result is less token burn, lower latency, and fewer runtime tool calls.

### Key Features
- **Local-first**: open source, runs in your own environment, no managed dependency.
- **Prepared data packages**: assembles the right context ahead of time instead of at runtime.
- **MCP-native**: serves data to your agents over MCP, the same protocol they already speak.
- **Lower cost and latency**: fewer live tool calls mean fewer tokens and less waiting.
- **Framework-agnostic**: works with Claude Code, Cursor, and your own agents.

→ [Repo](https://github.com/glassflow/tares) · [Docs](https://docs.glassflow.ai/tares)

Rius and Tares are two halves of the same idea: agents running in production need both a clear view of what they're doing and the right data to do it well. GlassFlow builds both: OpenTelemetry-native, MCP-first, and grounded in years of streaming and ClickHouse infrastructure work. Whether you're debugging a 72-hour run or feeding an always-on agent the context it needs, the goal is the same: agents you can actually see, understand, and trust in production.

[Docs](https://docs.glassflow.ai) | [Blog](https://glassflow.ai/blog) | [X](https://x.com/glassflowdev)

