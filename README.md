<p align="center">
  <h1 align="center">Awesome Agent CLI</h1>
  <p align="center">
    <em>A curated collection of CLI tools and applications designed for AI agents.</em>
  </p>
  <p align="center">
    <a href="#productivity-suites">Productivity</a> &middot;
    <a href="#project-management">Project Mgmt</a> &middot;
    <a href="#knowledge--docs">Knowledge</a> &middot;
    <a href="#research--academic">Research</a> &middot;
    <a href="#email">Email</a> &middot;
    <a href="#social--messaging">Social</a> &middot;
    <a href="#developer-tools">Dev Tools</a> &middot;
    <a href="#browser--web-automation">Browser</a> &middot;
    <a href="#agent-applications">Agent Apps</a> &middot;
    <a href="#agent-bridges">Bridges</a>
  </p>
</p>

---

## What is an "Agent CLI"?

CLI tools built for **AI agents** (Claude Code, OpenClaw, Codex, Gemini CLI, Cursor, etc.) to interact with external services. Instead of raw REST APIs or bloated MCP servers, agent CLIs provide structured JSON output, shell-composable commands, `--dry-run` safety, and token-efficient responses.

---

## Productivity Suites

<div align="center">

| Name | Stars | Lang | Tags | Description |
|:-----|:------|:-----|:-----|:------------|
| [gws](https://github.com/googleworkspace/cli) | ![](https://img.shields.io/github/stars/googleworkspace/cli?style=flat-square&label=) | Rust | ![official][official] ![agent-first][agent-first] ![batch-ops][batch-ops] | Google Workspace CLI. Drive, Gmail, Calendar, Sheets, Docs, Chat, Admin. Dynamic Discovery API. Three-layer commands. |
| [lark-cli](https://github.com/larksuite/cli) | ![](https://img.shields.io/github/stars/larksuite/cli?style=flat-square&label=) | Go | ![official][official] ![agent-first][agent-first] ![batch-ops][batch-ops] | Official Lark/Feishu. 200+ commands, 11 domains. Agent auth, schema introspection, `--dry-run`. |
| [feishu-cli](https://github.com/riba2534/feishu-cli) | ![](https://img.shields.io/github/stars/riba2534/feishu-cli?style=flat-square&label=) | Go | ![community][community] ![agent-first][agent-first] ![markdown][markdown] | Bidirectional Markdown-to-Feishu (40+ blocks). Mermaid/PlantUML to Whiteboard. 10k+ line pipeline. |
| [Feishu-MCP](https://github.com/cso1z/Feishu-MCP) | ![](https://img.shields.io/github/stars/cso1z/Feishu-MCP?style=flat-square&label=) | TypeScript | ![community][community] ![agent-friendly][agent-friendly] | Feishu/Lark MCP server + CLI. Cursor, Claude Code, Cline. |

</div>

---

## Project Management

<div align="center">

| Name | Stars | Lang | Tags | Description |
|:-----|:------|:-----|:-----|:------------|
| [linearis](https://github.com/czottmann/linearis) | ![](https://img.shields.io/github/stars/czottmann/linearis?style=flat-square&label=) | TypeScript | ![community][community] ![agent-first][agent-first] ![token-efficient][token-efficient] | Linear.app CLI. Smart ID resolution. Under 1k tokens (vs 13k MCP). Issues, comments, cycles. |
| [linctl](https://github.com/dorkitude/linctl) | ![](https://img.shields.io/github/stars/dorkitude/linctl?style=flat-square&label=) | Go | ![community][community] ![agent-friendly][agent-friendly] | Linear CLI built with agents in mind. Cobra framework. |
| [linear-cli](https://github.com/mixpeek/linear-cli) | ![](https://img.shields.io/github/stars/mixpeek/linear-cli?style=flat-square&label=) | TypeScript | ![community][community] ![agent-friendly][agent-friendly] | CLI tool for interacting with Linear.app. |

</div>

---

## Knowledge & Docs

<div align="center">

| Name | Stars | Lang | Tags | Description |
|:-----|:------|:-----|:-----|:------------|
| [notion-cli-agent](https://github.com/Balneario-de-Cofrentes/notion-cli-agent) | ![](https://img.shields.io/github/stars/Balneario-de-Cofrentes/notion-cli-agent?style=flat-square&label=) | TypeScript | ![community][community] ![agent-first][agent-first] ![batch-ops][batch-ops] ![token-efficient][token-efficient] | Notion CLI. `--llm` mode, natural language queries, batch ops, auto-discovery. |
| [vibe-notion](https://github.com/devxoul/vibe-notion) | ![](https://img.shields.io/github/stars/devxoul/vibe-notion?style=flat-square&label=) | TypeScript | ![community][community] ![agent-first][agent-first] | Notion automation CLI for AI agents. |
| [notion-cli](https://github.com/Coastal-Programs/notion-cli) | ![](https://img.shields.io/github/stars/Coastal-Programs/notion-cli?style=flat-square&label=) | Go | ![community][community] ![agent-first][agent-first] | Enterprise-grade Notion CLI. Advanced retry and caching. |
| [feishu-docx](https://github.com/leemysw/feishu-docx) | ![](https://img.shields.io/github/stars/leemysw/feishu-docx?style=flat-square&label=) | Python | ![community][community] ![agent-friendly][agent-friendly] ![markdown][markdown] | Feishu/Lark Docs and Sheets to Markdown. OAuth, CLI, TUI. |
| [obsidian-export](https://github.com/zoni/obsidian-export) | ![](https://img.shields.io/github/stars/zoni/obsidian-export?style=flat-square&label=) | Rust | ![community][community] ![agent-friendly][agent-friendly] ![markdown][markdown] | Export Obsidian vault to Markdown. Resolves wiki-links, embeds. |
| [ov](https://github.com/sokojh/obsidian-vault) | ![](https://img.shields.io/github/stars/sokojh/obsidian-vault?style=flat-square&label=) | Rust | ![community][community] ![agent-first][agent-first] | Agent-first Obsidian vault CLI. JSON output, schema introspection, `--dry-run`. |
| [obs](https://github.com/markfive-proto/obsidian-vault-cli) | ![](https://img.shields.io/github/stars/markfive-proto/obsidian-vault-cli?style=flat-square&label=) | TypeScript | ![community][community] ![agent-friendly][agent-friendly] | Obsidian vault CLI. 100+ commands for notes, search, tags, links, tasks. |
| [obsidianRAGsody](https://github.com/nicolaischneider/obsidianRAGsody) | ![](https://img.shields.io/github/stars/nicolaischneider/obsidianRAGsody?style=flat-square&label=) | Python | ![community][community] ![agent-friendly][agent-friendly] | Obsidian vault RAG. Natural language queries, URL-to-markdown. |

</div>

---

## Research & Academic

<div align="center">

| Name | Stars | Lang | Tags | Description |
|:-----|:------|:-----|:-----|:------------|
| [pyoverleaf](https://github.com/jkulhanek/pyoverleaf) | ![](https://img.shields.io/github/stars/jkulhanek/pyoverleaf?style=flat-square&label=) | Python | ![community][community] ![agent-friendly][agent-friendly] ![markdown][markdown] | Overleaf API + CLI. Projects, files, comments, live changes. |
| [olcli](https://github.com/aloth/olcli) | ![](https://img.shields.io/github/stars/aloth/olcli?style=flat-square&label=) | JavaScript | ![community][community] ![agent-friendly][agent-friendly] | Overleaf CLI. Sync, manage, compile LaTeX projects. |
| [overleaf-sync-rs](https://github.com/katzper-michno/overleaf-sync-rs) | ![](https://img.shields.io/github/stars/katzper-michno/overleaf-sync-rs?style=flat-square&label=) | Rust | ![community][community] ![agent-friendly][agent-friendly] | Bidirectional Overleaf-to-local sync. |
| [overleap](https://github.com/Axect/overleap) | ![](https://img.shields.io/github/stars/Axect/overleap?style=flat-square&label=) | JavaScript | ![community][community] ![agent-friendly][agent-friendly] | Real-time bidirectional Overleaf sync. |
| [LeafLink](https://github.com/xiongqi123123/LeafLink) | ![](https://img.shields.io/github/stars/xiongqi123123/LeafLink?style=flat-square&label=) | Python | ![community][community] ![agent-friendly][agent-friendly] | Lightweight Overleaf sync. Pull/push, pseudo real-time. |
| [overleaf-cli](https://github.com/BruceChenSF/overleaf-cli) | ![](https://img.shields.io/github/stars/BruceChenSF/overleaf-cli?style=flat-square&label=) | TypeScript | ![community][community] ![agent-first][agent-first] | AI tools (Claude Code, Cursor) edit Overleaf via local sync. |
| [pubtab](https://github.com/Galaxy-Dawn/pubtab) | ![](https://img.shields.io/github/stars/Galaxy-Dawn/pubtab?style=flat-square&label=) | Python | ![community][community] ![agent-friendly][agent-friendly] | Bidirectional Excel-to-LaTeX table converter. Style-preserving. |
| [s2cli](https://github.com/mrshu/s2cli) | ![](https://img.shields.io/github/stars/mrshu/s2cli?style=flat-square&label=) | Python | ![community][community] ![agent-first][agent-first] | Semantic Scholar API CLI. For researchers and AI agents. |
| [searchkit](https://github.com/RanaPriyansh/searchkit) | ![](https://img.shields.io/github/stars/RanaPriyansh/searchkit?style=flat-square&label=) | Python | ![community][community] ![agent-friendly][agent-friendly] | Paper discovery. arXiv, PubMed, SSRN search + PDF + summaries. |
| [xiv](https://github.com/james-akl/xiv) | ![](https://img.shields.io/github/stars/james-akl/xiv?style=flat-square&label=) | Python | ![community][community] ![agent-friendly][agent-friendly] | Minimal arXiv search and download CLI. |
| [rSearch](https://github.com/jscraik/rSearch) | ![](https://img.shields.io/github/stars/jscraik/rSearch?style=flat-square&label=) | TypeScript | ![community][community] ![agent-friendly][agent-friendly] | Search, fetch, download arXiv papers from terminal. |
| [Research-Paper-Extractor](https://github.com/Sreeram5678/Research-Paper-Extractor) | ![](https://img.shields.io/github/stars/Sreeram5678/Research-Paper-Extractor?style=flat-square&label=) | Python | ![community][community] ![agent-friendly][agent-friendly] | arXiv paper search/download by keywords, authors, categories. |
| [arxiv-cli](https://github.com/lucabeetz/arxiv-cli) | ![](https://img.shields.io/github/stars/lucabeetz/arxiv-cli?style=flat-square&label=) | Rust | ![community][community] ![agent-friendly][agent-friendly] | Small CLI to search and download arXiv papers. |
| [PaperHunterAgent](https://github.com/madara88645/PaperHunterAgent) | ![](https://img.shields.io/github/stars/madara88645/PaperHunterAgent?style=flat-square&label=) | Python | ![community][community] ![agent-first][agent-first] | Multi-agent paper discovery from arXiv + Semantic Scholar. |

</div>

---

## Email

<div align="center">

| Name | Stars | Lang | Tags | Description |
|:-----|:------|:-----|:-----|:------------|
| [himalaya](https://github.com/pimalaya/himalaya) | ![](https://img.shields.io/github/stars/pimalaya/himalaya?style=flat-square&label=) | Rust | ![community][community] ![agent-friendly][agent-friendly] | IMAP/SMTP CLI. Read, write, reply, forward, search. Multi-account. |
| [Gmail via gws](https://github.com/googleworkspace/cli) | ![](https://img.shields.io/github/stars/googleworkspace/cli?style=flat-square&label=) | Rust | ![official][official] ![agent-first][agent-first] | Gmail through gws: `+send`, `+reply`, `+triage`, `+watch`. See Productivity. |

</div>

---

## Social & Messaging

<div align="center">

| Name | Stars | Lang | Tags | Description |
|:-----|:------|:-----|:-----|:------------|
| xurl | -- | -- | ![community][community] ![agent-friendly][agent-friendly] | X/Twitter API v2. Tweets, replies, search, DMs, media. (OpenClaw built-in) |
| wacli | -- | -- | ![community][community] ![agent-friendly][agent-friendly] | WhatsApp CLI. Send, search, sync history. (OpenClaw built-in) |
| [slack-rs](https://github.com/tumf/slack-rs) | ![](https://img.shields.io/github/stars/tumf/slack-rs?style=flat-square&label=) | Rust | ![community][community] ![agent-first][agent-first] | Slack CLI. OAuth auth, agentic design principles. |

</div>

---

## Developer Tools

<div align="center">

| Name | Stars | Lang | Tags | Description |
|:-----|:------|:-----|:-----|:------------|
| [gh](https://github.com/cli/cli) | ![](https://img.shields.io/github/stars/cli/cli?style=flat-square&label=) | Go | ![official][official] ![agent-friendly][agent-friendly] | GitHub CLI. Issues, PRs, CI/CD, code review, releases, API queries. |

</div>

---

## Browser & Web Automation

<div align="center">

| Name | Stars | Lang | Tags | Description |
|:-----|:------|:-----|:-----|:------------|
| [browser-use](https://github.com/browser-use/browser-use) | ![](https://img.shields.io/github/stars/browser-use/browser-use?style=flat-square&label=) | Python | ![community][community] ![agent-first][agent-first] | Make websites accessible for AI agents. Most popular agent browser lib. |
| [UI-TARS-desktop](https://github.com/bytedance/UI-TARS-desktop) | ![](https://img.shields.io/github/stars/bytedance/UI-TARS-desktop?style=flat-square&label=) | TypeScript | ![official][official] ![agent-first][agent-first] | Multimodal AI agent stack from ByteDance. |
| [nanobrowser](https://github.com/nanobrowser/nanobrowser) | ![](https://img.shields.io/github/stars/nanobrowser/nanobrowser?style=flat-square&label=) | TypeScript | ![community][community] ![agent-first][agent-first] | Chrome extension. AI web automation, multi-agent, own LLM key. |
| [magentic-ui](https://github.com/microsoft/magentic-ui) | ![](https://img.shields.io/github/stars/microsoft/magentic-ui?style=flat-square&label=) | Python | ![official][official] ![agent-first][agent-first] | Human-centered web agent from Microsoft. |
| [wiseflow](https://github.com/TeamWiseFlow/wiseflow) | ![](https://img.shields.io/github/stars/TeamWiseFlow/wiseflow?style=flat-square&label=) | JavaScript | ![community][community] ![agent-friendly][agent-friendly] | Enhance any agent's browser use skill. |
| [openbrowser](https://github.com/ntegrals/openbrowser) | ![](https://img.shields.io/github/stars/ntegrals/openbrowser?style=flat-square&label=) | TypeScript | ![community][community] ![agent-first][agent-first] | Autonomous toolkit for browser-based AI agents. |
| [notte](https://github.com/nottelabs/notte) | ![](https://img.shields.io/github/stars/nottelabs/notte?style=flat-square&label=) | Python | ![community][community] ![agent-first][agent-first] | Web agents framework. Serverless browser automation. |
| [agentql](https://github.com/tinyfish-io/agentql) | ![](https://img.shields.io/github/stars/tinyfish-io/agentql?style=flat-square&label=) | Python | ![community][community] ![agent-first][agent-first] | AI-to-web tools. Query language + Playwright integrations. |
| [HyperAgent](https://github.com/hyperbrowserai/HyperAgent) | ![](https://img.shields.io/github/stars/hyperbrowserai/HyperAgent?style=flat-square&label=) | TypeScript | ![community][community] ![agent-first][agent-first] | AI browser automation. |
| [browserable](https://github.com/browserable/browserable) | ![](https://img.shields.io/github/stars/browserable/browserable?style=flat-square&label=) | JavaScript | ![community][community] ![agent-first][agent-first] | Self-hostable browser automation for AI agents. |
| [AIPex](https://github.com/AIPexStudio/AIPex) | ![](https://img.shields.io/github/stars/AIPexStudio/AIPex?style=flat-square&label=) | TypeScript | ![community][community] ![agent-first][agent-first] | AI browser automation. Privacy first. |
| [fara](https://github.com/microsoft/fara) | ![](https://img.shields.io/github/stars/microsoft/fara?style=flat-square&label=) | Python | ![official][official] ![agent-first][agent-first] | Fara-7B: agentic model for computer use, Microsoft. |
| [mobile-use](https://github.com/minitap-ai/mobile-use) | ![](https://img.shields.io/github/stars/minitap-ai/mobile-use?style=flat-square&label=) | Python | ![community][community] ![agent-first][agent-first] | AI agents on real Android/iOS apps. |
| [agent-browser-go](https://github.com/cpunion/agent-browser-go) | ![](https://img.shields.io/github/stars/cpunion/agent-browser-go?style=flat-square&label=) | Go | ![community][community] ![agent-first][agent-first] | Headless browser CLI. chromedp/playwright backends. |

</div>

---

## Agent Applications

<div align="center">

| Name | Stars | Lang | Tags | Description |
|:-----|:------|:-----|:-----|:------------|
| [obsidian-skills](https://github.com/kepano/obsidian-skills) | ![](https://img.shields.io/github/stars/kepano/obsidian-skills?style=flat-square&label=) | -- | ![official][official] ![agent-first][agent-first] ![agent-app][agent-app] | Official Obsidian agent skills. Markdown, Bases, JSON Canvas, CLI. |
| [obsidian-agent-client](https://github.com/RAIT-09/obsidian-agent-client) | ![](https://img.shields.io/github/stars/RAIT-09/obsidian-agent-client?style=flat-square&label=) | TypeScript | ![community][community] ![agent-first][agent-first] ![agent-app][agent-app] | Obsidian ACP plugin. Claude Code, Codex, Gemini CLI support. |
| [geminese](https://github.com/Momoyu404/geminese) | ![](https://img.shields.io/github/stars/Momoyu404/geminese?style=flat-square&label=) | TypeScript | ![community][community] ![agent-first][agent-first] ![agent-app][agent-app] | Obsidian plugin. Embeds Gemini CLI in your vault. |
| [neurostack](https://github.com/raphasouthall/neurostack) | ![](https://img.shields.io/github/stars/raphasouthall/neurostack?style=flat-square&label=) | Python | ![community][community] ![agent-first][agent-first] ![agent-app][agent-app] | CLI + MCP for building/searching a knowledge vault. |
| [plandex](https://github.com/plandex-ai/plandex) | ![](https://img.shields.io/github/stars/plandex-ai/plandex?style=flat-square&label=) | Go | ![community][community] ![agent-first][agent-first] ![agent-app][agent-app] | AI coding agent for large projects. |
| [superset](https://github.com/superset-sh/superset) | ![](https://img.shields.io/github/stars/superset-sh/superset?style=flat-square&label=) | TypeScript | ![community][community] ![agent-first][agent-first] ![agent-app][agent-app] | Code editor for agents. Run multiple Claude Code / Codex. |
| [axe](https://github.com/jrswab/axe) | ![](https://img.shields.io/github/stars/jrswab/axe?style=flat-square&label=) | Go | ![community][community] ![agent-first][agent-first] ![agent-app][agent-app] | Single-purpose AI agents. TOML config, pipes, hooks, cron. |
| [dataclaw-sync](https://github.com/UFOyyds/dataclaw-sync) | ![](https://img.shields.io/github/stars/UFOyyds/dataclaw-sync?style=flat-square&label=) | Python | ![community][community] ![agent-friendly][agent-friendly] ![agent-app][agent-app] | Export agent conversations to Obsidian. Claude Code, Codex, OpenClaw. |

</div>

---

## Agent Bridges

<div align="center">

| Name | Stars | Lang | Tags | Description |
|:-----|:------|:-----|:-----|:------------|
| [cc-connect](https://github.com/chenhg5/cc-connect) | ![](https://img.shields.io/github/stars/chenhg5/cc-connect?style=flat-square&label=) | Go | ![community][community] ![bridge][bridge] | Bridge agents to Feishu, DingTalk, Slack, Telegram, Discord. |
| [golembot](https://github.com/0xranx/golembot) | ![](https://img.shields.io/github/stars/0xranx/golembot?style=flat-square&label=) | TypeScript | ![community][community] ![bridge][bridge] | Any Agent, Any Provider, Anywhere. Slack, Telegram, Discord, Feishu, WeCom. |
| [feishu-claude-code](https://github.com/joewongjc/feishu-claude-code) | ![](https://img.shields.io/github/stars/joewongjc/feishu-claude-code?style=flat-square&label=) | Python | ![community][community] ![bridge][bridge] | Bridge Claude Code to Feishu/Lark via WebSocket. |

</div>

---

<details>
<summary><strong>Design Patterns</strong></summary>

**Output** -- JSON by default + `--format table|csv|ndjson`. `--llm` mode for token-efficient output. NDJSON streaming for pagination.

**Commands** -- Three-layer pattern (lark-cli, gws): Shortcuts (`+agenda`) -> API commands -> Raw API. Schema introspection.

**Auth** -- Non-blocking auth returning URL for approval. Environment variables. OS keyring storage.

**Safety** -- Batch operations to minimize tool calls. `--dry-run` previews. Progressive disclosure.

</details>

---

## Gaps

Services without a good agent CLI yet: Jira, Confluence, Asana, Trello, Todoist, Airtable, Figma, Zoom, HuggingFace (agent-optimized).

<!-- badge reference links (must be at end of file) -->
[official]: https://img.shields.io/badge/official-0969DA?style=flat-square
[community]: https://img.shields.io/badge/community-2DA44E?style=flat-square
[agent-first]: https://img.shields.io/badge/agent--first-8250DF?style=flat-square
[agent-friendly]: https://img.shields.io/badge/agent--friendly-BF8BFF?style=flat-square
[research]: https://img.shields.io/badge/research-1F6FEB?style=flat-square
[productivity]: https://img.shields.io/badge/productivity-E16F24?style=flat-square
[project-mgmt]: https://img.shields.io/badge/project--mgmt-CF222E?style=flat-square
[knowledge]: https://img.shields.io/badge/knowledge-0E8A16?style=flat-square
[messaging]: https://img.shields.io/badge/messaging-1A7F37?style=flat-square
[social]: https://img.shields.io/badge/social-D4A72C?style=flat-square
[dev-tools]: https://img.shields.io/badge/dev--tools-343B42?style=flat-square
[browser]: https://img.shields.io/badge/browser-0550AE?style=flat-square
[agent-app]: https://img.shields.io/badge/agent--app-A475F9?style=flat-square
[bridge]: https://img.shields.io/badge/bridge-DA3633?style=flat-square
[markdown]: https://img.shields.io/badge/markdown-57606A?style=flat-square
[batch-ops]: https://img.shields.io/badge/batch--ops-E3B341?style=flat-square
[token-efficient]: https://img.shields.io/badge/token--efficient-2DA44E?style=flat-square


