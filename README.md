# Robby Czesany

**Agentic engineer** building the infrastructure layer for AI agents — search & retrieval, memory systems, MCP tooling, and messaging integrations. I turn APIs and workflows into reliable agent tools: the engineering is in the loop *around* the agent — reliability, verification, tight feedback. Patterns are portable across [OpenClaw](https://github.com/openclaw/openclaw), [Hermes](https://github.com/NousResearch/hermes-agent), [Nanoclaw](https://github.com/qwibitai/nanoclaw), and standalone MCP/PyPI packages.

**19 merged PRs** to OpenClaw core · **74k+** ClawHub registry downloads across 12 skills · flagship [web-search-plus](https://websearchplus.xyz) at **331★**

Latest: **[OpenAgentFleet](https://github.com/robbyczgw-cla/openagentfleet)** — a local-first macOS runtime for AI agents with isolated computers and explicit approvals.

📫 Open to interesting agent-infrastructure work : **robby@robbyczesany.com**

---

## Featured work

### 🖥️ Agent runtime

**[OpenAgentFleet](https://github.com/robbyczgw-cla/openagentfleet)** — local-first macOS app for running AI agents with explicit control. Grok Build, Codex App Server, and OpenCode in one workspace; browser and desktop tasks run on an isolated Linux computer you can watch, stop, or take over. Controller-brokered approvals, local-only data, mobile control over Tailscale.

Go controller · Tauri + React shell · Apache-2.0 · signed & notarized alpha for Apple Silicon → [openagentfleet.xyz](https://openagentfleet.xyz)

### 🔍 Agent tools & retrieval

**[web-search-plus](https://websearchplus.xyz)** — multi-provider search engine for AI agents. 13+ search providers, 6+ extraction providers, intelligent auto-routing, opt-in research mode, multi-LLM fallback chains.

One engine, three deployments: [hermes-web-search-plus](https://github.com/robbyczgw-cla/hermes-web-search-plus) (331★), [web-search-plus-plugin](https://github.com/robbyczgw-cla/web-search-plus-plugin) for OpenClaw, and a standalone MCP server ([`web-search-plus-mcp`](https://pypi.org/project/web-search-plus-mcp/) on PyPI).

### 🧠 Agent memory & autonomy

- **[lucid-dreamer](https://clawhub.ai/robbyczgw-cla/lucid-dreamer)** — nightly memory reasoning; auto-cleans agent memory while you sleep
- **[skillminer](https://clawhub.ai/robbyczgw-cla/skillminer)** — scans agent memory, detects patterns, drafts new skills for human review
- **[topic-monitor](https://clawhub.ai/robbyczgw-cla/topic-monitor)** — scheduled topic monitoring with AI importance scoring — included in [DigitalOcean's OpenClaw Skills guide](https://www.digitalocean.com/resources/articles/what-are-openclaw-skills) (as *proactive-research*)

*Also built: [agent-chronicle](https://clawhub.ai/robbyczgw-cla/agent-chronicle) (AI-perspective diary), [roundtable](https://clawhub.ai/robbyczgw-cla/roundtable) (multi-agent debate council), and [OpenCami](https://github.com/robbyczgw-cla/opencami) (a web client for OpenClaw).*

---

## How I build

I design the system, let agents accelerate implementation and research, review every commit, test the behavior, and ship the parts that hold up. The engineering is in the loop around the agent — reliability, verification, feedback. Human decisions, agent-assisted execution, tight feedback loop. The same patterns port across OpenClaw, Hermes, Nanoclaw, and standalone MCP/PyPI packages — each suited to a different workflow.

## Track record

- **[OpenClaw](https://github.com/openclaw/openclaw) contributor** — 19 merged PRs: Telegram, Discord, session management, formatting, bug fixes
- **74k+ ClawHub registry downloads** across 12 published skills — indexed at [openclawskills.xyz](https://openclawskills.xyz)
- Skills featured in [awesome-openclaw-skills](https://github.com/VoltAgent/awesome-openclaw-skills) and [awesome-hermes-agent](https://github.com/0xNyk/awesome-hermes-agent)

## Stack

Go (local agent runtime) · Python (engines, MCP servers) · TypeScript (plugins, web) · React + React Native · Tauri · Node.js · Vite · Expo · SQLite · Docker/Colima sandboxing · async-everywhere · multi-LLM orchestration with fallback chains

---

<sub>📫 robbyczgw@gmail.com · [openagentfleet.xyz](https://openagentfleet.xyz) · [websearchplus.xyz](https://websearchplus.xyz) · [openclawskills.xyz](https://openclawskills.xyz) · Graz, Austria (CET)</sub>
