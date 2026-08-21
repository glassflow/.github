<a href="https://glassflow.dev">
  <img alt="GlassFlow Logo" src="https://raw.githubusercontent.com/glassflow/.github/main/profile/assets/banner.png">
</a>
<p align="center">
<a href="https://hub.docker.com/u/glassflow" target="_blank">
<img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white">
</a>
<a href="https://www.linkedin.com/company/glassflow-dev" target="_blank">
<img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white">
</a>
<a href="https://twitter.com/glassflowdev" target="_blank">
<img alt="Twitter" src="https://img.shields.io/badge/Twitter-1DA1F2?logo=twitter&logoColor=white">
</a>
</p>


# GlassFlow Overview

GlassFlow builds the data infrastructure for AI agents in production. As teams move agents out of prototypes and into real workloads, they hit a wall: agents need reliable, correlated data to act on, and teams need visibility into what those agents actually do once they're live. GlassFlow closes both gaps with a pair of products purpose-built for production agent systems.

GlassFlow offers two products: Tares feeds agents correlated data from every system they depend on, so they act on a complete, consistent picture rather than scattered, stale inputs. Rius traces and debugs what production agents do, giving teams visibility into agent behavior, decisions, and failures so issues can be caught and fixed in real time.


## Product Details

- **GlassFlow Tares**:
  - **Connect a source once, every agent uses it**: point Tares at a database, folder, or API and it becomes a queryable surface any MCP agent can read. It's ingest config, not another MCP server to build and maintain per source.
  - **Records arrive already correlated**: the Postgres row, the API enrichment, and the document about the same customer land on one keyed timeline, so agents spend context on the task instead of joining data.
  - **Your sources stay calm**: agents read from the Tares store, so your production DB and rate-limited APIs see one well-behaved reader no matter how many agents you run.
  - **Memory comes standard**: everything an agent reads or writes about an entity stays on its timeline, so the next task starts from what's already known.
  - **One endpoint, any harness**: serves standard MCP, so Claude Code, Codex, Cursor, or a custom loop all just work; two commands to wire up.
  

- **GlassFlow Rius**:
  - **See incidents before customers do**: every step persisted live, full sessions queryable in milliseconds even after days of runtime.
  - **Made for agents in prod, not just chatbots**: one continuous session across restarts and sub-agents, built for long-running, always-on, multi-framework agents.
  - **Debug over MCP**: your coding agent queries traces and ships the fix, no dashboard required.
  - **Nothing deleted**: extended retention with hot traces in milliseconds and older ones auto-tiered to S3.
  - **Whitelabel it**: embed observability under your own domain and brand.


## Getting Started

- To get started with **GlassFlow Tares**, check the [Tares Quickstart](https://docs.glassflow.ai/tares/quickstart)
- To get started with **GlassFlow Rius**, check the [Rius Quickstart](https://docs.glassflow.ai/rius/quickstart)

