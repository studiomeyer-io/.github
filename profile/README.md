<div align="center">

# StudioMeyer

**AI tools that work. Built in TypeScript. Open source.**

We build MCP servers, agent frameworks, and security tooling for AI applications.

[Website](https://studiomeyer.io) · [Twitter](https://x.com/matthias_meyer_)

---

</div>


<!-- org-stats-badges -->
<div align="center">

[![npm downloads / month](https://img.shields.io/npm/dm/darwin-agents?style=flat-square&color=cb3837&logo=npm&label=darwin-agents%20%2Fmo)](https://www.npmjs.com/package/darwin-agents)
[![npm downloads / month](https://img.shields.io/npm/dm/mcp-academy?style=flat-square&color=cb3837&logo=npm&label=mcp-academy%20%2Fmo)](https://www.npmjs.com/package/mcp-academy)
[![npm downloads / month](https://img.shields.io/npm/dm/mcp-personal-suite?style=flat-square&color=cb3837&logo=npm&label=personal-suite%20%2Fmo)](https://www.npmjs.com/package/mcp-personal-suite)
[![PyPI downloads / month](https://img.shields.io/pypi/dm/studiomeyer-aishield?style=flat-square&color=3776AB&logo=pypi&logoColor=white&label=ai-shield-py%20%2Fmo)](https://pypi.org/project/studiomeyer-aishield/)
[![crates.io](https://img.shields.io/crates/d/mcp-armor?style=flat-square&color=000000&logo=rust&label=mcp-armor%20installs)](https://crates.io/crates/mcp-armor)

**5,500+ npm installs / month across 33 packages · 3,000+ git clones / 14 days · 43 public repos · 19 forks**

Measured, not maintained: refreshed weekly by [`org-stats-refresh`](https://github.com/studiomeyer-io/.github). Last run 2026-08-23. Live mirror: [matthiasmeyer.tech](https://matthiasmeyer.tech).

</div>
<!-- /org-stats-badges -->

## A note from us

We have been building tools and systems for ourselves for the past two years. The fact that this org is small and our repos have few stars is not because we are new. It is because we only just decided to share what we have built. It is not a fresh experiment, it is a long story with a recent commit.

We love building things and sharing them. We do not love social media tactics, growth hacks, or chasing stars and followers. So this org is small. The code is real, it gets used, issues get answered. Judge for yourself.

If something here helps you, sharing, testing, and feedback help us. If it could be better, an issue is more useful. If you build something with it, tell us at hello@studiomeyer.io. That genuinely makes our day.

From a small studio in Palma de Mallorca.

## Ecosystem

This org is the open-source half of StudioMeyer, a small AI and design studio in Palma de Mallorca. Six connected sites, same founder, same stack:

- **[studiomeyer.io](https://studiomeyer.io)** — the studio. Websites, AI systems and automation for smaller companies. Personal guidance, long-term support.
- **[studiomeyer.academy](https://studiomeyer.academy)** — a free "Memory-First AI Operator" school. Six levels from beginner to building your own MCP server, DE/EN/ES, Discord. Ships as the `mcp-academy` npm package.
- **[aifinca.es](https://aifinca.es)** — hands-on AI-operator workshops on a finca on Mallorca. Four formats, solo to full team. You leave with a running system, not a PDF of notes.
- **[matthiasmeyer.tech](https://matthiasmeyer.tech)** — the hub for everything in this org: each repo with architecture notes, trade-offs, and when to use it.
- **[meetmyagent.io](https://meetmyagent.io)** — a free, AI-native visibility platform and marketplace. List a service, product or property for free; an agent fills in the details, and it becomes visible to people and to AI.
- **[aklow-labs.com](https://aklow-labs.com)** — our research lab. Polis: nine AI citizens (Claude Opus, Sonnet, Haiku) live sixty years in a simulated Mallorca town, open and live.

## MCP Server Products

### 🧠 [StudioMeyer Memory](https://github.com/studiomeyer-io/studiomeyer-memory) — Persistent AI Memory

56 MCP tools (incl. interactive 3D knowledge graph visualization). Knowledge Graph, semantic search, session tracking, multi-agent support, contradiction detection. Import from ChatGPT, Claude, Gemini, Copilot, Perplexity.

```
https://memory.studiomeyer.io/mcp
```

`56 tools` · `Bi-temporal KG` · `EU Frankfurt` · `OAuth 2.1 + Magic Link` · `Free tier`

---

### 📇 [StudioMeyer CRM](https://github.com/studiomeyer-io/studiomeyer-crm) — Headless AI CRM

33 MCP tools. Companies, contacts, deals, pipeline, leads, follow-ups, health scores, Stripe sync, CSV import/export. No dashboard needed.

```
https://crm.studiomeyer.io/mcp
```

`33 tools` · `3-phase search` · `Free tier` · `Zero-Knowledge Credentials`

---

### 🔍 [StudioMeyer GEO](https://github.com/studiomeyer-io/studiomeyer-geo) — AI Visibility Monitoring

25 MCP tools. Check how 8 LLM platforms (ChatGPT, Gemini, Perplexity, Claude, Grok, DeepSeek, Meta AI, Copilot) see your brand. 20 tools work without API keys.

```
https://geo.studiomeyer.io/mcp
```

`25 tools` · `8 LLM platforms` · `Free tier` · `KDD 2024 paper-based`

---

### 👥 [MCP Crew](https://github.com/studiomeyer-io/mcp-crew) — Agent Personas

10 MCP tools. 8 expert personas (CEO, CFO, CMO, CTO, PM, Analyst, Support, Creative Director) with domain frameworks, decision models, and memory integration. Zero extra API cost.

```
https://crew.studiomeyer.io/mcp
```

`10 tools` · `8 personas` · `3 workflows` · `Free`

---

### 🏪 [StudioMeyer Marketplace](https://github.com/studiomeyer-io/studiomeyer-marketplace) — Claude Code Plugin Suite

All 4 MCP products as Claude Code plugins. One command, 119 tools, slash commands, skills, subagents.

```bash
/plugin marketplace add studiomeyer-io/studiomeyer-marketplace
```

---

## Open Source Tools

### 🛡️ [AI Shield](https://github.com/studiomeyer-io/ai-shield) — LLM Security Middleware

Prompt injection detection, PII masking, cost tracking, and tool policies. Zero dependencies. Works with OpenAI, Anthropic, Gemini.

```bash
npm install ai-shield-core
```

`325 tests` · `5 packages` · `<25ms scans` · `zero dependencies`

---

### 🧬 [Darwin Agents](https://github.com/studiomeyer-io/darwin-agents) — Self-Evolving AI Prompts

AI agents that improve themselves through automated A/B testing with safety gates. Multi-model critics, micro-mutations, failure rollback.

```bash
npm install darwin-agents
```

`130 tests` · `4 providers` · `7 critic sets` · `built-in A/B testing`

---

### 🤖 [Agent Fleet](https://github.com/studiomeyer-io/agent-fleet) — Multi-Agent Orchestration

Run specialized AI agents in parallel — research, critique, analyze, fix, and discuss. Built on Claude Code CLI with MCP tool access.

```bash
npx tsx agents/research-agent.ts "your topic"
```

`158 tests` · `7 agents` · `conductor orchestration` · `MCP native`

---

### 🎬 [MCP Video](https://github.com/studiomeyer-io/mcp-video) — Video Production via MCP

Cinema-grade video production from any AI assistant. Recording, editing, effects, captions, TTS, and smart screenshots. Built on FFmpeg + Playwright.

`8 tools` · `60fps recording` · `22 LUT presets` · `social format export`

---

### 🌀 [Temporal Memory Workflows](https://github.com/studiomeyer-io/temporal-memory-workflows) — Durable AI Workflow Templates

Five Temporal workflow templates with StudioMeyer Memory integration. Memory-aware agent, operator approval, saga rollback, recurring synthesis, multi-agent coordination. Built so AI agents and long-running pipelines have one shared brain across crashes, restarts, and weeks of execution.

```bash
git clone https://github.com/studiomeyer-io/temporal-memory-workflows
```

`5 templates` · `45 tests` · `TypeScript SDK` · `Postgres-only cluster`

---

### 🦀 [MCP Armor](https://github.com/studiomeyer-io/mcp-armor) — Rust Security Sidecar

Drop-in Rust sidecar for MCP servers. Scans tool calls for prompt injection, validates Ed25519 manifest signatures, blocks marketplace-poisoning vectors. Defense against the OX Security MCP advisory (10+ CVEs).

```bash
cargo install mcp-armor
```

`343 tests` · `<5ms p99 overhead` · `Sigstore Rekor bridge` · `OTLP gRPC export`

---

### 💾 [Local Memory MCP](https://github.com/studiomeyer-io/local-memory-mcp) — Persistent Memory, No Cloud

Persistent local memory for Claude, Cursor, and Codex. 13 MCP tools, SQLite + FTS5 + Knowledge Graph. No cloud, no API keys, no signup.

```bash
npx @studiomeyer/local-memory-mcp
```

`13 tools` · `SQLite + FTS5` · `Knowledge Graph` · `MIT`

---

<div align="center">

**All projects are MIT licensed.**

Built by [Matthias Meyer](https://github.com/madetocreate) in Mallorca, Spain.

*Running an AI agency with 35+ agents, 60 MCP servers, and 700+ tools.*

</div>
