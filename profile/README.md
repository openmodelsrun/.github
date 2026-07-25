# OpenModels

**Open Registry & Intelligence Platform for AI Infrastructure**

Discover, compare and monitor LLM models, inference providers, MCP servers and agent skills using open data and real-time telemetry.

Track latency, uptime, pricing, rate limits, capabilities, and provider mappings — in one place.

---

## Stats

| Models | Providers | Mappings | Skills | MCP Servers |
|:---:|:---:|:---:|:---:|:---:|
| 132 | 52 | 205 | 215 | 187 |

---

## What OpenModels covers

- **Models** — canonical registry of LLM models: capabilities, context windows, modalities, licensing, open-weight status

- **Providers** — 52 inference providers with API base URLs, auth types, regions, free tiers, trial credits

- **Mappings** — per-provider rate limits, pricing, and model availability

- **Telemetry** — real-time latency (TTFT p50/p95/p99) and uptime monitoring across providers

- **MCP Servers** — registry of 187 Model Context Protocol servers

- **Skills** — 215 ready-to-use AI agent prompts and workflows for Claude Code, Cursor, Kiro, Copilot, Windsurf and more

- **Insights** — data-driven analysis and benchmarks based on live telemetry

- **CLI** — command-line interface for querying the registry

---

## Architecture

```text
openmodels/     → public YAML registry (models, providers, mappings, schemas)
skills/         → community AI agent skills (github.com/openmodelsrun/skills)
mcp/            → Model Context Protocol server registry
cms/            → Payload CMS for Insights content (cms.openmodels.run)
docs/           → architecture, roadmap, contributing guides (docs.openmodels.run)
platform/       → intelligence platform — Next.js + NestJS + Python workers
```

---

## Platform

→ **[openmodels.run](https://www.openmodels.run)** — search, compare, telemetry, skills, MCP servers, insights

---

## Roadmap

- [x] Registry (models, providers, mappings)

- [x] Telemetry (Anthropic, Groq, AWS, DeepSeek, Alibaba, Google AI)

- [x] Skills

- [x] MCP Servers registry

- [x] Insights

- [x] CLI

- [x] Public API

- [x] SDK (`@openmodels/sdk`)

- [x] i18n (Chinese, Russian, Spanish)

- [ ] User accounts + Pro plan

---

## Contributing

The registry is community-maintained. Adding a model, provider, or MCP server is a single YAML file.

→ [Contributing Guide](https://docs.openmodels.run/contributing)
