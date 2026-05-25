# OpenModels

Open infrastructure for discovering, comparing, and monitoring LLM models and inference providers.

OpenModels is a community-driven registry and intelligence platform for the modern AI inference ecosystem — models, providers, pricing, rate limits, latency, uptime, and capabilities.

## What OpenModels covers

- **Models** — canonical registry of LLM models with capabilities, context windows, modalities, licensing
- **Providers** — 42+ inference providers with API base URLs, auth types, regions, free tiers, trial credits
- **Mappings** — per-provider rate limits, pricing, and model availability
- **Telemetry** — real-time latency (TTFT p50/p95/p99) and uptime monitoring across providers
- **Skills** — ready-to-use AI agent prompts and workflows for Claude Code, Cursor, Kiro, Copilot and more
- **Insights** — data-driven analysis and benchmarks based on live telemetry
- **CLI** — command-line interface for querying the registry

## Architecture

```text
openmodels/     → public YAML registry (models, providers, mappings, schemas)
skills/         → community AI agent skills
docs/           → architecture, roadmap, contributing guides (docs.openmodels.run)
```

## Platform

→ **openmodels.run** — search, compare, telemetry, skills, insights
