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

## Tags

`official` platform vendor / `community` community maintained / `agent-first` designed for agents / `agent-friendly` works well with agents / `research` academic workflows / `productivity` workplace tools / `project-mgmt` issue tracking / `knowledge` notes and wikis / `messaging` chat platforms / `social` social media / `dev-tools` developer tools / `browser` web automation / `agent-app` application for agents / `bridge` connects agents to platforms / `markdown` markdown support / `batch-ops` batch operations / `token-efficient` minimal token usage

---

## Productivity Suites

| Name | Stars | Lang | Tags |
|------|-------|------|------|
| [gws](https://github.com/googleworkspace/cli) | ![](https://img.shields.io/github/stars/googleworkspace/cli?style=flat-square&label=) | Rust | `official` `agent-first` `batch-ops` |
| [lark-cli](https://github.com/larksuite/cli) | ![](https://img.shields.io/github/stars/larksuite/cli?style=flat-square&label=) | Go | `official` `agent-first` `batch-ops` |
| [feishu-cli](https://github.com/riba2534/feishu-cli) | ![](https://img.shields.io/github/stars/riba2534/feishu-cli?style=flat-square&label=) | Go | `community` `agent-first` `markdown` |
| [Feishu-MCP](https://github.com/cso1z/Feishu-MCP) | ![](https://img.shields.io/github/stars/cso1z/Feishu-MCP?style=flat-square&label=) | TypeScript | `community` `agent-friendly` |

<details>
<summary>Descriptions</summary>

- **gws** -- One CLI for all Google Workspace (Drive, Gmail, Calendar, Sheets, Docs, Chat, Admin). Dynamic command surface from Discovery Service. Three-layer architecture: shortcuts (`+send`, `+agenda`) -> API methods -> raw API. Schema introspection, NDJSON streaming, encrypted OAuth.
- **lark-cli** -- Official Lark/Feishu CLI. 200+ commands across 11 domains (Calendar, Messenger, Docs, Drive, Base, Sheets, Tasks, Wiki, Contact, Mail, Meetings). Three-layer commands, non-blocking agent auth (`--no-wait`), schema introspection, `--dry-run`.
- **feishu-cli** -- Community Feishu CLI. Bidirectional lossless Markdown-to-Feishu conversion (40+ block types). Mermaid/PlantUML to editable Feishu Whiteboard. Concurrent pipeline tested at 10k+ lines. Full platform coverage.
- **Feishu-MCP** -- Feishu/Lark MCP server + CLI. Integrates with Cursor, Claude Code, Cline.

</details>

---

## Project Management

| Name | Stars | Lang | Tags |
|------|-------|------|------|
| [linearis](https://github.com/czottmann/linearis) | ![](https://img.shields.io/github/stars/czottmann/linearis?style=flat-square&label=) | TypeScript | `community` `agent-first` `token-efficient` |
| [linctl](https://github.com/dorkitude/linctl) | ![](https://img.shields.io/github/stars/dorkitude/linctl?style=flat-square&label=) | Go | `community` `agent-friendly` |
| [linear-cli](https://github.com/mixpeek/linear-cli) | ![](https://img.shields.io/github/stars/mixpeek/linear-cli?style=flat-square&label=) | TypeScript | `community` `agent-friendly` |

<details>
<summary>Descriptions</summary>

- **linearis** -- Linear.app CLI. JSON output, smart ID resolution (`ABC-123` format). Under 1k tokens for agent context (vs ~13k for Linear MCP). Issues, comments, documents, projects, cycles, embeds.
- **linctl** -- Linear CLI built with agents in mind. Cobra framework.
- **linear-cli** -- CLI tool for interacting with Linear.app.

</details>

---

## Knowledge & Docs

| Name | Stars | Lang | Tags |
|------|-------|------|------|
| [notion-cli-agent](https://github.com/Balneario-de-Cofrentes/notion-cli-agent) | ![](https://img.shields.io/github/stars/Balneario-de-Cofrentes/notion-cli-agent?style=flat-square&label=) | TypeScript | `community` `agent-first` `batch-ops` `token-efficient` |
| [vibe-notion](https://github.com/devxoul/vibe-notion) | ![](https://img.shields.io/github/stars/devxoul/vibe-notion?style=flat-square&label=) | TypeScript | `community` `agent-first` |
| [notion-cli](https://github.com/Coastal-Programs/notion-cli) | ![](https://img.shields.io/github/stars/Coastal-Programs/notion-cli?style=flat-square&label=) | Go | `community` `agent-first` |
| [feishu-docx](https://github.com/leemysw/feishu-docx) | ![](https://img.shields.io/github/stars/leemysw/feishu-docx?style=flat-square&label=) | Python | `community` `agent-friendly` `markdown` |
| [obsidian-export](https://github.com/zoni/obsidian-export) | ![](https://img.shields.io/github/stars/zoni/obsidian-export?style=flat-square&label=) | Rust | `community` `agent-friendly` `markdown` |
| [ov](https://github.com/sokojh/obsidian-vault) | ![](https://img.shields.io/github/stars/sokojh/obsidian-vault?style=flat-square&label=) | Rust | `community` `agent-first` |
| [obs](https://github.com/markfive-proto/obsidian-vault-cli) | ![](https://img.shields.io/github/stars/markfive-proto/obsidian-vault-cli?style=flat-square&label=) | TypeScript | `community` `agent-friendly` |
| [obsidianRAGsody](https://github.com/nicolaischneider/obsidianRAGsody) | ![](https://img.shields.io/github/stars/nicolaischneider/obsidianRAGsody?style=flat-square&label=) | Python | `community` `agent-friendly` |

<details>
<summary>Descriptions</summary>

- **notion-cli-agent** -- Notion CLI with `--llm` mode for compact output. Natural language queries (`notion find`), batch operations, workspace auto-discovery, Obsidian sync.
- **vibe-notion** -- Notion automation CLI for AI agents.
- **notion-cli** -- Enterprise-grade Notion CLI. Advanced retry and caching.
- **feishu-docx** -- Feishu/Lark Docs and Sheets to Markdown with OAuth, CLI, TUI.
- **obsidian-export** -- Export Obsidian vault to regular Markdown. Resolves wiki-links, embeds, and Obsidian-specific syntax.
- **ov** -- Agent-first CLI for Obsidian vaults. JSON-only output, schema introspection, `--dry-run`.
- **obs** -- Community CLI for Obsidian vaults. 100+ commands for notes, search, tags, links, tasks.
- **obsidianRAGsody** -- Intelligent Obsidian vault interaction using RAG. Natural language queries, URL-to-markdown.

</details>

---

## Research & Academic

| Name | Stars | Lang | Tags |
|------|-------|------|------|
| [pyoverleaf](https://github.com/jkulhanek/pyoverleaf) | ![](https://img.shields.io/github/stars/jkulhanek/pyoverleaf?style=flat-square&label=) | Python | `community` `agent-friendly` `markdown` |
| [olcli](https://github.com/aloth/olcli) | ![](https://img.shields.io/github/stars/aloth/olcli?style=flat-square&label=) | JavaScript | `community` `agent-friendly` |
| [overleaf-sync-rs](https://github.com/katzper-michno/overleaf-sync-rs) | ![](https://img.shields.io/github/stars/katzper-michno/overleaf-sync-rs?style=flat-square&label=) | Rust | `community` `agent-friendly` |
| [overleap](https://github.com/Axect/overleap) | ![](https://img.shields.io/github/stars/Axect/overleap?style=flat-square&label=) | JavaScript | `community` `agent-friendly` |
| [LeafLink](https://github.com/xiongqi123123/LeafLink) | ![](https://img.shields.io/github/stars/xiongqi123123/LeafLink?style=flat-square&label=) | Python | `community` `agent-friendly` |
| [overleaf-cli](https://github.com/BruceChenSF/overleaf-cli) | ![](https://img.shields.io/github/stars/BruceChenSF/overleaf-cli?style=flat-square&label=) | TypeScript | `community` `agent-first` |
| [pubtab](https://github.com/Galaxy-Dawn/pubtab) | ![](https://img.shields.io/github/stars/Galaxy-Dawn/pubtab?style=flat-square&label=) | Python | `community` `agent-friendly` |
| [s2cli](https://github.com/mrshu/s2cli) | ![](https://img.shields.io/github/stars/mrshu/s2cli?style=flat-square&label=) | Python | `community` `agent-first` |
| [searchkit](https://github.com/RanaPriyansh/searchkit) | ![](https://img.shields.io/github/stars/RanaPriyansh/searchkit?style=flat-square&label=) | Python | `community` `agent-friendly` |
| [xiv](https://github.com/james-akl/xiv) | ![](https://img.shields.io/github/stars/james-akl/xiv?style=flat-square&label=) | Python | `community` `agent-friendly` |
| [rSearch](https://github.com/jscraik/rSearch) | ![](https://img.shields.io/github/stars/jscraik/rSearch?style=flat-square&label=) | TypeScript | `community` `agent-friendly` |
| [Research-Paper-Extractor](https://github.com/Sreeram5678/Research-Paper-Extractor) | ![](https://img.shields.io/github/stars/Sreeram5678/Research-Paper-Extractor?style=flat-square&label=) | Python | `community` `agent-friendly` |
| [arxiv-cli](https://github.com/lucabeetz/arxiv-cli) | ![](https://img.shields.io/github/stars/lucabeetz/arxiv-cli?style=flat-square&label=) | Rust | `community` `agent-friendly` |
| [PaperHunterAgent](https://github.com/madara88645/PaperHunterAgent) | ![](https://img.shields.io/github/stars/madara88645/PaperHunterAgent?style=flat-square&label=) | Python | `community` `agent-first` |

<details>
<summary>Descriptions</summary>

- **pyoverleaf** -- Python API and CLI for Overleaf. List/create/archive projects, upload/download files, comments, live changes. Auth via browser cookies.
- **olcli** -- Overleaf CLI. Sync, manage, and compile LaTeX projects from terminal.
- **overleaf-sync-rs** -- Bidirectional sync between Overleaf and local filesystem.
- **overleap** -- Real-time bidirectional Overleaf sync.
- **LeafLink** -- Lightweight Overleaf sync. Pull/push workflows, pseudo real-time.
- **overleaf-cli** -- Enable AI tools (Claude Code, Cursor) to edit Overleaf projects via local file sync.
- **pubtab** -- Bidirectional Excel-to-LaTeX table converter with style-preserving roundtrip.
- **s2cli** -- CLI for the Semantic Scholar API. Designed for researchers and AI agents.
- **searchkit** -- Academic paper discovery. Search arXiv, PubMed, SSRN; download PDFs; generate summaries.
- **xiv** -- Minimal arXiv search and download CLI.
- **rSearch** -- Search, fetch, and download arXiv papers from the terminal.
- **Research-Paper-Extractor** -- Automated arXiv paper search and download by keywords, authors, categories.
- **arxiv-cli** -- Small CLI to search and download arXiv papers.
- **PaperHunterAgent** -- Multi-agent CLI that discovers, summarizes, and visualizes papers from arXiv and Semantic Scholar.

</details>

---

## Email

| Name | Stars | Lang | Tags |
|------|-------|------|------|
| [himalaya](https://github.com/pimalaya/himalaya) | ![](https://img.shields.io/github/stars/pimalaya/himalaya?style=flat-square&label=) | Rust | `community` `agent-friendly` |
| [Gmail via gws](https://github.com/googleworkspace/cli) | ![](https://img.shields.io/github/stars/googleworkspace/cli?style=flat-square&label=) | Rust | `official` `agent-first` |

<details>
<summary>Descriptions</summary>

- **himalaya** -- CLI for IMAP/SMTP email. List, read, write, reply, forward, search. Multi-account, MML composition.
- **Gmail via gws** -- Gmail through Google Workspace CLI: `+send`, `+reply`, `+triage`, `+watch`. See Productivity.

</details>

---

## Social & Messaging

| Name | Stars | Lang | Tags |
|------|-------|------|------|
| xurl | -- | -- | `community` `agent-friendly` `social` |
| wacli | -- | -- | `community` `agent-friendly` `messaging` |
| [slack-rs](https://github.com/tumf/slack-rs) | ![](https://img.shields.io/github/stars/tumf/slack-rs?style=flat-square&label=) | Rust | `community` `agent-first` |

<details>
<summary>Descriptions</summary>

- **xurl** -- X/Twitter API v2 CLI. Tweets, replies, search, DMs, media upload. (OpenClaw built-in)
- **wacli** -- WhatsApp CLI. Send messages, search/sync history. (OpenClaw built-in)
- **slack-rs** -- Slack CLI with OAuth auth and agentic design principles.

</details>

---

## Developer Tools

| Name | Stars | Lang | Tags |
|------|-------|------|------|
| [gh](https://github.com/cli/cli) | ![](https://img.shields.io/github/stars/cli/cli?style=flat-square&label=) | Go | `official` `agent-friendly` `dev-tools` |

<details>
<summary>Descriptions</summary>

- **gh** -- GitHub CLI. Issues, PRs, CI/CD, code review, releases, API queries.

</details>

---

## Browser & Web Automation

| Name | Stars | Lang | Tags |
|------|-------|------|------|
| [browser-use](https://github.com/browser-use/browser-use) | ![](https://img.shields.io/github/stars/browser-use/browser-use?style=flat-square&label=) | Python | `community` `agent-first` |
| [UI-TARS-desktop](https://github.com/bytedance/UI-TARS-desktop) | ![](https://img.shields.io/github/stars/bytedance/UI-TARS-desktop?style=flat-square&label=) | TypeScript | `official` `agent-first` |
| [nanobrowser](https://github.com/nanobrowser/nanobrowser) | ![](https://img.shields.io/github/stars/nanobrowser/nanobrowser?style=flat-square&label=) | TypeScript | `community` `agent-first` |
| [magentic-ui](https://github.com/microsoft/magentic-ui) | ![](https://img.shields.io/github/stars/microsoft/magentic-ui?style=flat-square&label=) | Python | `official` `agent-first` |
| [wiseflow](https://github.com/TeamWiseFlow/wiseflow) | ![](https://img.shields.io/github/stars/TeamWiseFlow/wiseflow?style=flat-square&label=) | JavaScript | `community` `agent-friendly` |
| [openbrowser](https://github.com/ntegrals/openbrowser) | ![](https://img.shields.io/github/stars/ntegrals/openbrowser?style=flat-square&label=) | TypeScript | `community` `agent-first` |
| [notte](https://github.com/nottelabs/notte) | ![](https://img.shields.io/github/stars/nottelabs/notte?style=flat-square&label=) | Python | `community` `agent-first` |
| [agentql](https://github.com/tinyfish-io/agentql) | ![](https://img.shields.io/github/stars/tinyfish-io/agentql?style=flat-square&label=) | Python | `community` `agent-first` |
| [HyperAgent](https://github.com/hyperbrowserai/HyperAgent) | ![](https://img.shields.io/github/stars/hyperbrowserai/HyperAgent?style=flat-square&label=) | TypeScript | `community` `agent-first` |
| [browserable](https://github.com/browserable/browserable) | ![](https://img.shields.io/github/stars/browserable/browserable?style=flat-square&label=) | JavaScript | `community` `agent-first` |
| [AIPex](https://github.com/AIPexStudio/AIPex) | ![](https://img.shields.io/github/stars/AIPexStudio/AIPex?style=flat-square&label=) | TypeScript | `community` `agent-first` |
| [fara](https://github.com/microsoft/fara) | ![](https://img.shields.io/github/stars/microsoft/fara?style=flat-square&label=) | Python | `official` `agent-first` |
| [mobile-use](https://github.com/minitap-ai/mobile-use) | ![](https://img.shields.io/github/stars/minitap-ai/mobile-use?style=flat-square&label=) | Python | `community` `agent-first` |
| [agent-browser-go](https://github.com/cpunion/agent-browser-go) | ![](https://img.shields.io/github/stars/cpunion/agent-browser-go?style=flat-square&label=) | Go | `community` `agent-first` |

<details>
<summary>Descriptions</summary>

- **browser-use** -- Make websites accessible for AI agents. The most popular agent browser library.
- **UI-TARS-desktop** -- Multimodal AI agent stack from ByteDance. Connecting AI models and agent infrastructure.
- **nanobrowser** -- Chrome extension for AI-powered web automation. Multi-agent workflows with your own LLM key.
- **magentic-ui** -- Human-centered web agent research prototype from Microsoft.
- **wiseflow** -- Enhance any agent's browser use skill.
- **openbrowser** -- Autonomous toolkit for browser-based AI agents.
- **notte** -- Build web agents and deploy serverless web automation on reliable browser infra.
- **agentql** -- Tools for connecting AI to the web. Query language and Playwright integrations.
- **HyperAgent** -- AI browser automation.
- **browserable** -- Self-hostable browser automation library for AI agents.
- **AIPex** -- AI browser automation assistant. Privacy first.
- **fara** -- Fara-7B: efficient agentic model for computer use from Microsoft.
- **mobile-use** -- AI agents use real Android and iOS apps, just like a human.
- **agent-browser-go** -- Headless browser automation CLI for AI agents. chromedp/playwright backends.

</details>

---

## Agent Applications

| Name | Stars | Lang | Tags |
|------|-------|------|------|
| [obsidian-skills](https://github.com/kepano/obsidian-skills) | ![](https://img.shields.io/github/stars/kepano/obsidian-skills?style=flat-square&label=) | -- | `official` `agent-first` `agent-app` |
| [obsidian-agent-client](https://github.com/RAIT-09/obsidian-agent-client) | ![](https://img.shields.io/github/stars/RAIT-09/obsidian-agent-client?style=flat-square&label=) | TypeScript | `community` `agent-first` `agent-app` |
| [geminese](https://github.com/Momoyu404/geminese) | ![](https://img.shields.io/github/stars/Momoyu404/geminese?style=flat-square&label=) | TypeScript | `community` `agent-first` `agent-app` |
| [neurostack](https://github.com/raphasouthall/neurostack) | ![](https://img.shields.io/github/stars/raphasouthall/neurostack?style=flat-square&label=) | Python | `community` `agent-first` `agent-app` |
| [plandex](https://github.com/plandex-ai/plandex) | ![](https://img.shields.io/github/stars/plandex-ai/plandex?style=flat-square&label=) | Go | `community` `agent-first` `agent-app` |
| [superset](https://github.com/superset-sh/superset) | ![](https://img.shields.io/github/stars/superset-sh/superset?style=flat-square&label=) | TypeScript | `community` `agent-first` `agent-app` |
| [axe](https://github.com/jrswab/axe) | ![](https://img.shields.io/github/stars/jrswab/axe?style=flat-square&label=) | Go | `community` `agent-first` `agent-app` |
| [dataclaw-sync](https://github.com/UFOyyds/dataclaw-sync) | ![](https://img.shields.io/github/stars/UFOyyds/dataclaw-sync?style=flat-square&label=) | Python | `community` `agent-friendly` `agent-app` |

<details>
<summary>Descriptions</summary>

- **obsidian-skills** -- Official agent skills for Obsidian. Teaches agents to use Markdown, Bases, JSON Canvas, and CLI.
- **obsidian-agent-client** -- Bring AI agents into Obsidian via ACP. Supports Claude Code, Codex, Gemini CLI.
- **geminese** -- Obsidian plugin that embeds Gemini CLI as AI collaborator in your vault.
- **neurostack** -- CLI + MCP server for building and searching a knowledge vault.
- **plandex** -- Open source AI coding agent for large projects and real world tasks.
- **superset** -- Code editor for the AI agents era. Run multiple Claude Code, Codex instances.
- **axe** -- Lightweight CLI for single-purpose AI agents. TOML config, trigger from pipes, hooks, cron.
- **dataclaw-sync** -- Export AI agent conversations to Obsidian notes. Supports Claude Code, Codex, Gemini CLI, OpenClaw.

</details>

---

## Agent Bridges

| Name | Stars | Lang | Tags |
|------|-------|------|------|
| [cc-connect](https://github.com/chenhg5/cc-connect) | ![](https://img.shields.io/github/stars/chenhg5/cc-connect?style=flat-square&label=) | Go | `community` `bridge` |
| [golembot](https://github.com/0xranx/golembot) | ![](https://img.shields.io/github/stars/0xranx/golembot?style=flat-square&label=) | TypeScript | `community` `bridge` |
| [feishu-claude-code](https://github.com/joewongjc/feishu-claude-code) | ![](https://img.shields.io/github/stars/joewongjc/feishu-claude-code?style=flat-square&label=) | Python | `community` `bridge` |

<details>
<summary>Descriptions</summary>

- **cc-connect** -- Bridge coding agents to Feishu/Lark, DingTalk, Slack, Telegram, Discord.
- **golembot** -- Any Agent, Any Provider, Anywhere. Connects to Slack, Telegram, Discord, Feishu, DingTalk, WeCom.
- **feishu-claude-code** -- Bridge Claude Code CLI with Feishu/Lark via WebSocket.

</details>

---

## Design Patterns

<details>
<summary>Expand</summary>

**Output** -- JSON by default + `--format table|csv|ndjson`. `--llm` mode for token-efficient output. NDJSON streaming for pagination.

**Commands** -- Three-layer pattern (lark-cli, gws): Shortcuts (`+agenda`) -> API commands -> Raw API. Schema introspection.

**Auth** -- Non-blocking auth returning URL for approval. Environment variables. OS keyring storage.

**Safety** -- Batch operations to minimize tool calls. `--dry-run` previews. Progressive disclosure.

</details>

---

## Gaps

Services without a good agent CLI yet: Jira, Confluence, Asana, Trello, Todoist, Airtable, Figma, Zoom, HuggingFace (agent-optimized).

---

## Contributing

Open a PR. Must be a CLI/app for agent use with its own repo link. Add a row to the table + a line in the descriptions block.

## License

[CC0 1.0 Universal](LICENSE) -- public domain. Individual tools have their own licenses.

---

<p align="center">
  Curated by <a href="https://github.com/shuyhere">@shuyhere</a>
</p>
