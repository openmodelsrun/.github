# OpenModels

[![OpenModels - Open Registry for AI Infrastructure](https://raw.githubusercontent.com/openmodelsrun/.github/main/profile/og-image.jpg)](https://www.openmodels.run)

**Open Registry & Telemetry for AI Infrastructure**

Discover, compare and monitor LLM models, inference providers, MCP servers and agent skills with source-transparent pricing, context limits, capabilities, access terms and live provider health.

Everything in one place — built on open data, community-maintained.

---

## Stats

| Models | Providers | Mappings | Skills | MCP Servers |
|:---:|:---:|:---:|:---:|:---:|
| 212 | 52 | 282 | 260 | 230 |

---

## What OpenModels covers

- **Models** — canonical registry of LLM models: capabilities, context windows, modalities, licensing, open-weight status, published benchmark results

- **Providers** — 52 inference providers with API base URLs, auth types, regions, free tiers, trial credits

- **Mappings** — per-provider pricing, rate limits and model availability; prices are always tied to a provider, never presented as a global model property

- **Compare & Calculator** — side-by-side model comparison and workload cost estimates based on your own token volumes, cache assumptions and request counts

- **Telemetry** — provider status and 30-day uptime history from hourly health checks across all 52 providers, plus latency (TTFT p50/p95/p99) monitoring

- **MCP Servers** — registry of 230 Model Context Protocol servers across 11 categories

- **Skills** — 260 ready-to-use AI agent prompts and workflows for Claude Code, Cursor, Kiro, Copilot, Windsurf, Gemini CLI, Aider and more

- **Insights** — data-driven analysis and benchmarks based on live registry and telemetry data

- **API, SDK & CLI** — public REST API, `@openmodels/sdk` and a command-line interface for querying the registry

- **Multilingual** — interface available in English, Chinese, Russian and Spanish

---

## Architecture

```text
openmodels/     → public YAML registry (models, providers, mappings, schemas)
skills/         → community AI agent skills (github.com/openmodelsrun/skills)
mcp/            → Model Context Protocol server registry
cms/            → Payload CMS for Insights content (cms.openmodels.run)
docs/           → architecture, contributing guides, API reference (docs.openmodels.run)
platform/       → intelligence platform — Next.js + NestJS + Python workers
```

---

## Platform

→ **[openmodels.run](https://www.openmodels.run)** — search, compare, calculator, provider status, skills, MCP servers, insights

---

## Contributing

The registry is community-maintained. Adding a model, provider, or MCP server is a single YAML file.

→ [Contributing Guide](https://docs.openmodels.run/contributing)
