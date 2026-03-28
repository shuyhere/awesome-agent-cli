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

`official` platform vendor maintained / `community` community maintained / `agent-first` designed primarily for agents / `agent-friendly` works well with agents / `research` academic workflows / `productivity` workplace tools / `project-mgmt` issue tracking / `knowledge` notes and wikis / `messaging` chat platforms / `social` social media / `dev-tools` developer tools / `browser` web automation / `agent-app` full application for agents / `bridge` connects agents to platforms / `markdown` markdown support / `batch-ops` batch operations / `token-efficient` minimal token usage

---

## Productivity Suites

- [**gws**](https://github.com/googleworkspace/cli) ![](https://img.shields.io/github/stars/googleworkspace/cli?style=flat-square&label=) `Rust` `official` `agent-first` `batch-ops` -- One CLI for all Google Workspace (Drive, Gmail, Calendar, Sheets, Docs, Chat, Admin). Dynamic command surface from Discovery Service. Three-layer architecture, schema introspection, NDJSON streaming.

- [**lark-cli**](https://github.com/larksuite/cli) ![](https://img.shields.io/github/stars/larksuite/cli?style=flat-square&label=) `Go` `official` `agent-first` `batch-ops` -- Official Lark/Feishu CLI. 200+ commands across 11 domains. Three-layer commands, non-blocking agent auth, schema introspection, `--dry-run`.

- [**feishu-cli**](https://github.com/riba2534/feishu-cli) ![](https://img.shields.io/github/stars/riba2534/feishu-cli?style=flat-square&label=) `Go` `community` `agent-first` `markdown` -- Bidirectional lossless Markdown-to-Feishu conversion (40+ block types). Mermaid/PlantUML to Feishu Whiteboard. Concurrent pipeline tested at 10k+ lines.

- [**Feishu-MCP**](https://github.com/cso1z/Feishu-MCP) ![](https://img.shields.io/github/stars/cso1z/Feishu-MCP?style=flat-square&label=) `TypeScript` `community` `agent-friendly` -- Feishu/Lark MCP server + CLI. Integrates with Cursor, Claude Code, Cline.

---

## Project Management

- [**linearis**](https://github.com/czottmann/linearis) ![](https://img.shields.io/github/stars/czottmann/linearis?style=flat-square&label=) `TypeScript` `community` `agent-first` `token-efficient` -- Linear.app CLI. JSON output, smart ID resolution. Under 1k tokens for agent context (vs ~13k for Linear MCP). Issues, comments, documents, cycles, embeds.

- [**linctl**](https://github.com/dorkitude/linctl) ![](https://img.shields.io/github/stars/dorkitude/linctl?style=flat-square&label=) `Go` `community` `agent-friendly` -- Linear CLI built with agents in mind. Cobra framework.

- [**linear-cli**](https://github.com/mixpeek/linear-cli) ![](https://img.shields.io/github/stars/mixpeek/linear-cli?style=flat-square&label=) `TypeScript` `community` `agent-friendly` -- CLI tool for interacting with Linear.app.

---

## Knowledge & Docs

- [**notion-cli-agent**](https://github.com/Balneario-de-Cofrentes/notion-cli-agent) ![](https://img.shields.io/github/stars/Balneario-de-Cofrentes/notion-cli-agent?style=flat-square&label=) `TypeScript` `community` `agent-first` `batch-ops` `token-efficient` -- Notion CLI with `--llm` mode. Natural language queries, batch operations, workspace auto-discovery, Obsidian sync.

- [**vibe-notion**](https://github.com/devxoul/vibe-notion) ![](https://img.shields.io/github/stars/devxoul/vibe-notion?style=flat-square&label=) `TypeScript` `community` `agent-first` -- Notion automation CLI for AI agents.

- [**notion-cli**](https://github.com/Coastal-Programs/notion-cli) ![](https://img.shields.io/github/stars/Coastal-Programs/notion-cli?style=flat-square&label=) `Go` `community` `agent-first` -- Enterprise-grade Notion CLI. Advanced retry and caching.

- [**feishu-docx**](https://github.com/leemysw/feishu-docx) ![](https://img.shields.io/github/stars/leemysw/feishu-docx?style=flat-square&label=) `Python` `community` `agent-friendly` `markdown` -- Feishu/Lark Docs and Sheets to Markdown with OAuth, CLI, TUI.

- [**obsidian-export**](https://github.com/zoni/obsidian-export) ![](https://img.shields.io/github/stars/zoni/obsidian-export?style=flat-square&label=) `Rust` `community` `agent-friendly` `markdown` -- Export Obsidian vault to regular Markdown. Resolves wiki-links, embeds, and Obsidian-specific syntax.

- [**ov**](https://github.com/sokojh/obsidian-vault) ![](https://img.shields.io/github/stars/sokojh/obsidian-vault?style=flat-square&label=) `Rust` `community` `agent-first` -- Agent-first CLI for Obsidian vaults. JSON-only output, schema introspection, `--dry-run`.

- [**obs**](https://github.com/markfive-proto/obsidian-vault-cli) ![](https://img.shields.io/github/stars/markfive-proto/obsidian-vault-cli?style=flat-square&label=) `TypeScript` `community` `agent-friendly` -- Community CLI for Obsidian vaults. 100+ commands for notes, search, tags, links, tasks.

- [**obsidianRAGsody**](https://github.com/nicolaischneider/obsidianRAGsody) ![](https://img.shields.io/github/stars/nicolaischneider/obsidianRAGsody?style=flat-square&label=) `Python` `community` `agent-friendly` -- Intelligent Obsidian vault interaction using RAG. Natural language queries, URL-to-markdown.

---

## Research & Academic

- [**pyoverleaf**](https://github.com/jkulhanek/pyoverleaf) ![](https://img.shields.io/github/stars/jkulhanek/pyoverleaf?style=flat-square&label=) `Python` `community` `agent-friendly` `markdown` -- Python API and CLI for Overleaf. List/create/archive projects, upload/download files, comments, live changes.

- [**olcli**](https://github.com/aloth/olcli) ![](https://img.shields.io/github/stars/aloth/olcli?style=flat-square&label=) `JavaScript` `community` `agent-friendly` -- Overleaf CLI. Sync, manage, and compile LaTeX projects from terminal.

- [**overleaf-sync-rs**](https://github.com/katzper-michno/overleaf-sync-rs) ![](https://img.shields.io/github/stars/katzper-michno/overleaf-sync-rs?style=flat-square&label=) `Rust` `community` `agent-friendly` -- Bidirectional sync between Overleaf and local filesystem.

- [**overleap**](https://github.com/Axect/overleap) ![](https://img.shields.io/github/stars/Axect/overleap?style=flat-square&label=) `JavaScript` `community` `agent-friendly` -- Real-time bidirectional Overleaf sync.

- [**LeafLink**](https://github.com/xiongqi123123/LeafLink) ![](https://img.shields.io/github/stars/xiongqi123123/LeafLink?style=flat-square&label=) `Python` `community` `agent-friendly` -- Lightweight Overleaf sync. Pull/push workflows, pseudo real-time.

- [**overleaf-cli**](https://github.com/BruceChenSF/overleaf-cli) ![](https://img.shields.io/github/stars/BruceChenSF/overleaf-cli?style=flat-square&label=) `TypeScript` `community` `agent-first` -- Enable AI tools (Claude Code, Cursor) to edit Overleaf projects via local file sync.

- [**pubtab**](https://github.com/Galaxy-Dawn/pubtab) ![](https://img.shields.io/github/stars/Galaxy-Dawn/pubtab?style=flat-square&label=) `Python` `community` `agent-friendly` -- Bidirectional Excel-to-LaTeX table converter with style-preserving roundtrip.

- [**s2cli**](https://github.com/mrshu/s2cli) ![](https://img.shields.io/github/stars/mrshu/s2cli?style=flat-square&label=) `Python` `community` `agent-first` -- CLI for the Semantic Scholar API. Designed for researchers and AI agents.

- [**searchkit**](https://github.com/RanaPriyansh/searchkit) ![](https://img.shields.io/github/stars/RanaPriyansh/searchkit?style=flat-square&label=) `Python` `community` `agent-friendly` -- Academic paper discovery. Search arXiv, PubMed, SSRN; download PDFs; generate summaries.

- [**xiv**](https://github.com/james-akl/xiv) ![](https://img.shields.io/github/stars/james-akl/xiv?style=flat-square&label=) `Python` `community` `agent-friendly` -- Minimal arXiv search and download CLI.

- [**rSearch**](https://github.com/jscraik/rSearch) ![](https://img.shields.io/github/stars/jscraik/rSearch?style=flat-square&label=) `TypeScript` `community` `agent-friendly` -- Search, fetch, and download arXiv papers from the terminal.

- [**Research-Paper-Extractor**](https://github.com/Sreeram5678/Research-Paper-Extractor) ![](https://img.shields.io/github/stars/Sreeram5678/Research-Paper-Extractor?style=flat-square&label=) `Python` `community` `agent-friendly` -- Automated arXiv paper search and download by keywords, authors, categories.

- [**arxiv-cli**](https://github.com/lucabeetz/arxiv-cli) ![](https://img.shields.io/github/stars/lucabeetz/arxiv-cli?style=flat-square&label=) `Rust` `community` `agent-friendly` -- Small CLI to search and download arXiv papers.

- [**PaperHunterAgent**](https://github.com/madara88645/PaperHunterAgent) ![](https://img.shields.io/github/stars/madara88645/PaperHunterAgent?style=flat-square&label=) `Python` `community` `agent-first` -- Multi-agent CLI that discovers, summarizes, and visualizes papers from arXiv and Semantic Scholar.

---

## Email

- [**himalaya**](https://github.com/pimalaya/himalaya) ![](https://img.shields.io/github/stars/pimalaya/himalaya?style=flat-square&label=) `Rust` `community` `agent-friendly` -- CLI for IMAP/SMTP email. List, read, write, reply, forward, search. Multi-account, MML composition.

- [**Gmail via gws**](https://github.com/googleworkspace/cli) ![](https://img.shields.io/github/stars/googleworkspace/cli?style=flat-square&label=) `Rust` `official` `agent-first` -- Gmail through Google Workspace CLI: `+send`, `+reply`, `+triage`, `+watch`. See Productivity.

---

## Social & Messaging

- **xurl** `community` `agent-friendly` `social` -- X/Twitter API v2 CLI. Tweets, replies, search, DMs, media upload. (OpenClaw built-in)

- **wacli** `community` `agent-friendly` `messaging` -- WhatsApp CLI. Send messages, search/sync history. (OpenClaw built-in)

- [**slack-rs**](https://github.com/tumf/slack-rs) ![](https://img.shields.io/github/stars/tumf/slack-rs?style=flat-square&label=) `Rust` `community` `agent-first` -- Slack CLI with OAuth auth and agentic design principles.

---

## Developer Tools

- [**gh**](https://github.com/cli/cli) ![](https://img.shields.io/github/stars/cli/cli?style=flat-square&label=) `Go` `official` `agent-friendly` `dev-tools` -- GitHub CLI. Issues, PRs, CI/CD, code review, releases, API queries.

---

## Browser & Web Automation

- [**browser-use**](https://github.com/browser-use/browser-use) ![](https://img.shields.io/github/stars/browser-use/browser-use?style=flat-square&label=) `Python` `community` `agent-first` -- Make websites accessible for AI agents. The most popular agent browser library.

- [**UI-TARS-desktop**](https://github.com/bytedance/UI-TARS-desktop) ![](https://img.shields.io/github/stars/bytedance/UI-TARS-desktop?style=flat-square&label=) `TypeScript` `official` `agent-first` -- Multimodal AI agent stack from ByteDance. Connecting AI models and agent infrastructure.

- [**nanobrowser**](https://github.com/nanobrowser/nanobrowser) ![](https://img.shields.io/github/stars/nanobrowser/nanobrowser?style=flat-square&label=) `TypeScript` `community` `agent-first` -- Chrome extension for AI-powered web automation. Multi-agent workflows with your own LLM key.

- [**magentic-ui**](https://github.com/microsoft/magentic-ui) ![](https://img.shields.io/github/stars/microsoft/magentic-ui?style=flat-square&label=) `Python` `official` `agent-first` -- Human-centered web agent research prototype from Microsoft.

- [**wiseflow**](https://github.com/TeamWiseFlow/wiseflow) ![](https://img.shields.io/github/stars/TeamWiseFlow/wiseflow?style=flat-square&label=) `JavaScript` `community` `agent-friendly` -- Enhance any agent's browser use skill.

- [**openbrowser**](https://github.com/ntegrals/openbrowser) ![](https://img.shields.io/github/stars/ntegrals/openbrowser?style=flat-square&label=) `TypeScript` `community` `agent-first` -- Autonomous toolkit for browser-based AI agents.

- [**notte**](https://github.com/nottelabs/notte) ![](https://img.shields.io/github/stars/nottelabs/notte?style=flat-square&label=) `Python` `community` `agent-first` -- Build web agents and deploy serverless web automation on reliable browser infra.

- [**agentql**](https://github.com/tinyfish-io/agentql) ![](https://img.shields.io/github/stars/tinyfish-io/agentql?style=flat-square&label=) `Python` `community` `agent-first` -- Tools for connecting AI to the web. Query language and Playwright integrations.

- [**HyperAgent**](https://github.com/hyperbrowserai/HyperAgent) ![](https://img.shields.io/github/stars/hyperbrowserai/HyperAgent?style=flat-square&label=) `TypeScript` `community` `agent-first` -- AI browser automation.

- [**browserable**](https://github.com/browserable/browserable) ![](https://img.shields.io/github/stars/browserable/browserable?style=flat-square&label=) `JavaScript` `community` `agent-first` -- Self-hostable browser automation library for AI agents.

- [**AIPex**](https://github.com/AIPexStudio/AIPex) ![](https://img.shields.io/github/stars/AIPexStudio/AIPex?style=flat-square&label=) `TypeScript` `community` `agent-first` -- AI browser automation assistant. Privacy first.

- [**fara**](https://github.com/microsoft/fara) ![](https://img.shields.io/github/stars/microsoft/fara?style=flat-square&label=) `Python` `official` `agent-first` -- Fara-7B: efficient agentic model for computer use from Microsoft.

- [**mobile-use**](https://github.com/minitap-ai/mobile-use) ![](https://img.shields.io/github/stars/minitap-ai/mobile-use?style=flat-square&label=) `Python` `community` `agent-first` -- AI agents use real Android and iOS apps, just like a human.

- [**agent-browser-go**](https://github.com/cpunion/agent-browser-go) ![](https://img.shields.io/github/stars/cpunion/agent-browser-go?style=flat-square&label=) `Go` `community` `agent-first` -- Headless browser automation CLI for AI agents. chromedp/playwright backends.

---

## Agent Applications

- [**obsidian-skills**](https://github.com/kepano/obsidian-skills) ![](https://img.shields.io/github/stars/kepano/obsidian-skills?style=flat-square&label=) `official` `agent-first` `agent-app` -- Official agent skills for Obsidian. Teaches agents to use Markdown, Bases, JSON Canvas, and CLI.

- [**obsidian-agent-client**](https://github.com/RAIT-09/obsidian-agent-client) ![](https://img.shields.io/github/stars/RAIT-09/obsidian-agent-client?style=flat-square&label=) `TypeScript` `community` `agent-first` `agent-app` -- Bring AI agents into Obsidian via ACP. Supports Claude Code, Codex, Gemini CLI.

- [**geminese**](https://github.com/Momoyu404/geminese) ![](https://img.shields.io/github/stars/Momoyu404/geminese?style=flat-square&label=) `TypeScript` `community` `agent-first` `agent-app` -- Obsidian plugin that embeds Gemini CLI as AI collaborator in your vault.

- [**neurostack**](https://github.com/raphasouthall/neurostack) ![](https://img.shields.io/github/stars/raphasouthall/neurostack?style=flat-square&label=) `Python` `community` `agent-first` `agent-app` -- CLI + MCP server for building and searching a knowledge vault.

- [**plandex**](https://github.com/plandex-ai/plandex) ![](https://img.shields.io/github/stars/plandex-ai/plandex?style=flat-square&label=) `Go` `community` `agent-first` `agent-app` -- Open source AI coding agent for large projects and real world tasks.

- [**superset**](https://github.com/superset-sh/superset) ![](https://img.shields.io/github/stars/superset-sh/superset?style=flat-square&label=) `TypeScript` `community` `agent-first` `agent-app` -- Code editor for the AI agents era. Run multiple Claude Code, Codex instances.

- [**axe**](https://github.com/jrswab/axe) ![](https://img.shields.io/github/stars/jrswab/axe?style=flat-square&label=) `Go` `community` `agent-first` `agent-app` -- Lightweight CLI for single-purpose AI agents. TOML config, trigger from pipes, hooks, cron.

- [**dataclaw-sync**](https://github.com/UFOyyds/dataclaw-sync) ![](https://img.shields.io/github/stars/UFOyyds/dataclaw-sync?style=flat-square&label=) `Python` `community` `agent-friendly` `agent-app` -- Export AI agent conversations to Obsidian notes. Supports Claude Code, Codex, Gemini CLI, OpenClaw.

---

## Agent Bridges

- [**cc-connect**](https://github.com/chenhg5/cc-connect) ![](https://img.shields.io/github/stars/chenhg5/cc-connect?style=flat-square&label=) `Go` `community` `bridge` -- Bridge coding agents to Feishu/Lark, DingTalk, Slack, Telegram, Discord.

- [**golembot**](https://github.com/0xranx/golembot) ![](https://img.shields.io/github/stars/0xranx/golembot?style=flat-square&label=) `TypeScript` `community` `bridge` -- Any Agent, Any Provider, Anywhere. Connects to Slack, Telegram, Discord, Feishu, DingTalk, WeCom.

- [**feishu-claude-code**](https://github.com/joewongjc/feishu-claude-code) ![](https://img.shields.io/github/stars/joewongjc/feishu-claude-code?style=flat-square&label=) `Python` `community` `bridge` -- Bridge Claude Code CLI with Feishu/Lark via WebSocket.

---

## Design Patterns

**Output** -- JSON by default + `--format table|csv|ndjson`. `--llm` mode for token-efficient output. NDJSON streaming for pagination.

**Commands** -- Three-layer pattern (lark-cli, gws): Shortcuts (`+agenda`) -> API commands -> Raw API. Schema introspection.

**Auth** -- Non-blocking auth returning URL for approval. Environment variables. OS keyring storage.

**Safety** -- Batch operations to minimize tool calls. `--dry-run` previews. Progressive disclosure.

---

## Gaps

Services without a good agent CLI yet: Jira, Confluence, Asana, Trello, Todoist, Airtable, Figma, Zoom, HuggingFace (agent-optimized).

---

## Contributing

Open a PR. Must be a CLI/app for agent use with its own repo link. Use format:
```
- [**name**](repo-url) ![](https://img.shields.io/github/stars/OWNER/REPO?style=flat-square&label=) `Lang` `tags` -- Description.
```

## License

[CC0 1.0 Universal](LICENSE) -- public domain. Individual tools have their own licenses.

---

<p align="center">
  Curated by <a href="https://github.com/shuyhere">@shuyhere</a>
</p>
