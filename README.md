<p align="center">
  <h1 align="center">🤖 Awesome Agent CLI</h1>
  <p align="center">
    <em>A curated collection of CLI tools designed for AI agents.</em>
  </p>
  <p align="center">
    <a href="#productivity-suites">Productivity</a> •
    <a href="#project-management">Project Mgmt</a> •
    <a href="#knowledge--docs">Knowledge</a> •
    <a href="#research--academic">Research</a> •
    <a href="#email">Email</a> •
    <a href="#social--messaging">Social</a> •
    <a href="#developer-tools">Dev Tools</a> •
    <a href="#agent-bridges">Bridges</a>
  </p>
</p>

---

## What is an "Agent CLI"?

A new wave of command-line tools built specifically for **AI agents** (Claude Code, OpenClaw, Codex, Gemini CLI, Cursor, etc.) to interact with external services. Instead of raw REST APIs or bloated MCP servers, agent CLIs provide:

- 📦 **Structured JSON output** — machine-parseable by default
- 🧠 **Agent skill files** (SKILL.md) — fit in LLM context windows
- 🔧 **Shell-composable commands** — pipe, batch, combine
- 🛡️ **Safety features** — `--dry-run`, input sanitization, scoped auth
- 📏 **Token-efficient** — compact output for minimal context usage

This repo classifies and tags every known agent-friendly CLI so you can find the right tool for your agent stack.

---

## Tags Legend

| Tag | Meaning |
|-----|---------|
| `official` | Maintained by the platform vendor |
| `community` | Community-maintained |
| `agent-first` | Designed primarily for AI agents |
| `agent-friendly` | Works well with agents but not exclusively designed for them |
| `has-skills` | Ships agent skill files (SKILL.md / AgentSkills) |
| `research` | Academic / research workflows |
| `productivity` | Workplace productivity (docs, calendar, email) |
| `project-mgmt` | Project & issue tracking |
| `knowledge` | Knowledge bases, wikis, notes |
| `messaging` | Chat & messaging platforms |
| `social` | Social media platforms |
| `dev-tools` | Developer-focused tools |
| `bridge` | Connects agents to messaging platforms |
| `markdown` | Strong Markdown support / conversion |
| `batch-ops` | Supports batch operations for fewer tool calls |
| `token-efficient` | Specifically optimized for minimal token usage |

---

## Productivity Suites

### Google Workspace CLI (`gws`)

> One CLI for all of Google Workspace — Drive, Gmail, Calendar, Sheets, Docs, Chat, Admin, and every Workspace API.

| | |
|---|---|
| **Repo** | [googleworkspace/cli](https://github.com/googleworkspace/cli) |
| **Stars** | ⭐ 22,800+ |
| **Language** | Rust |
| **Install** | `npm install -g @googleworkspace/cli` |
| **Tags** | `official` `agent-first` `has-skills` `productivity` `batch-ops` |

**Key Features:**
- Dynamic command surface — reads Google Discovery Service at runtime, auto-updates when APIs change
- 100+ agent skills (SKILL.md files)
- Three-layer architecture: Helper shortcuts (`+send`, `+agenda`) → Discovery methods → Raw API
- Schema introspection: `gws schema drive.files.list`
- Output formats: JSON, table, CSV, NDJSON
- OAuth with AES-256-GCM encrypted credentials in OS keyring
- Timezone-aware helpers (auto-detect from Calendar settings)
- Gemini CLI extension + OpenClaw skill support

**Example:**
```bash
gws gmail +triage                          # unread inbox summary
gws calendar +agenda                       # upcoming events
gws drive files list --params '{"pageSize": 5}'
gws sheets +read SPREADSHEET_ID 'Sheet1!A1:C10'
```

---

### Lark/Feishu Official CLI (`lark-cli`)

> Official command-line tool for Lark/Feishu Open Platform — 200+ commands, 19 agent skills.

| | |
|---|---|
| **Repo** | [larksuite/cli](https://github.com/larksuite/cli) |
| **Stars** | ⭐ 501 |
| **Language** | Go (npm wrapper) |
| **Install** | `npm install -g @larksuite/cli` |
| **Tags** | `official` `agent-first` `has-skills` `productivity` `batch-ops` |

**Key Features:**
- 11 business domains: Calendar, Messenger, Docs, Drive, Base, Sheets, Tasks, Wiki, Contact, Mail, Meetings
- 19 structured agent skills covering every domain
- Three-layer commands: Shortcuts → API Commands → Raw API
- Non-blocking auth flow (`--no-wait`) for agent use
- Schema introspection: `lark-cli schema calendar.events.instance_view`
- Output formats: JSON, pretty, table, NDJSON, CSV
- Input injection protection & terminal output sanitization
- `--dry-run` preview for side-effect commands

**Example:**
```bash
lark-cli calendar +agenda
lark-cli im +messages-send --chat-id "oc_xxx" --text "Hello"
lark-cli docs +create --title "Report" --markdown "# Progress\n- Done"
lark-cli api GET /open-apis/calendar/v4/calendars
```

---

### Feishu CLI (Community)

> Community Feishu CLI with Markdown ↔ Feishu Docs bidirectional lossless conversion.

| | |
|---|---|
| **Repo** | [riba2534/feishu-cli](https://github.com/riba2534/feishu-cli) |
| **Stars** | ⭐ 567 |
| **Language** | Go |
| **Install** | `curl -fsSL https://raw.githubusercontent.com/riba2534/feishu-cli/main/install.sh \| bash` |
| **Tags** | `community` `agent-first` `has-skills` `productivity` `markdown` |

**Key Features:**
- Markdown ↔ Feishu Docs **bidirectional lossless conversion** (40+ block types)
- Mermaid (8 diagram types) & PlantUML → editable Feishu Whiteboard vector graphics
- Three-stage concurrent pipeline for large documents (tested: 10,000+ lines, 127 diagrams)
- 11 agent skills
- Full platform coverage: docs, wiki, sheets, messages, groups, calendar, tasks, permissions, boards, comments, search
- Async file export/import (PDF, DOCX, XLSX)

**Example:**
```bash
feishu-cli doc import report.md --title "Tech Report" --upload-images --verbose
feishu-cli doc export <doc_id> -o output.md --download-images
feishu-cli msg send --receive-id-type email --receive-id user@example.com --text "Hello"
feishu-cli calendar events list
```

---

### Feishu MCP

> Feishu/Lark MCP server + CLI + Skill — integrates with Cursor, Claude Code, Cline.

| | |
|---|---|
| **Repo** | [cso1z/Feishu-MCP](https://github.com/cso1z/Feishu-MCP) |
| **Stars** | ⭐ 564 |
| **Language** | TypeScript |
| **Tags** | `community` `agent-friendly` `has-skills` `productivity` |

---

## Project Management

### Linearis (Linear CLI)

> CLI for Linear.app — JSON output, smart ID resolution, under 1,000 tokens for agent context.

| | |
|---|---|
| **Repo** | [czottmann/linearis](https://github.com/czottmann/linearis) |
| **Stars** | ⭐ 165 |
| **Language** | TypeScript |
| **Install** | `npm install -g linearis` |
| **Tags** | `community` `agent-first` `token-efficient` `project-mgmt` `has-skills` |

**Key Features:**
- JSON output, smart ID resolution (accepts `ABC-123` format)
- **Token-efficient:** `linearis usage` < 1,000 tokens (vs ~13k for Linear's official MCP)
- Issues (CRUD, search, labels, priority), Comments, Documents, Projects, Cycles/Sprints
- File embed upload/download
- Ships inline agent instruction prompt

**Example:**
```bash
linearis issues list -l 10
linearis issues search "auth bug" --team Platform --project "Auth Service"
linearis issues create "Fix timeout" --team Backend --priority 1
linearis comments create ABC-123 --body "Fixed in PR #456"
```

---

### linctl (Linear CLI — Go)

> Linear CLI built with agents in mind, implemented in Go with Cobra.

| | |
|---|---|
| **Repo** | [dorkitude/linctl](https://github.com/dorkitude/linctl) |
| **Stars** | ⭐ 119 |
| **Language** | Go |
| **Tags** | `community` `agent-friendly` `project-mgmt` |

---

### Linear CLI (mixpeek)

| | |
|---|---|
| **Repo** | [mixpeek/linear-cli](https://github.com/mixpeek/linear-cli) |
| **Stars** | ⭐ 16 |
| **Language** | TypeScript |
| **Tags** | `community` `agent-friendly` `project-mgmt` |

---

## Knowledge & Docs

### Notion CLI Agent

> The most powerful CLI for Notion — natural language queries, batch ops, `--llm` output mode.

| | |
|---|---|
| **Repo** | [Balneario-de-Cofrentes/notion-cli-agent](https://github.com/Balneario-de-Cofrentes/notion-cli-agent) |
| **Stars** | ⭐ 67 |
| **Language** | TypeScript |
| **Install** | `npm install -g notion-cli-agent` |
| **Tags** | `community` `agent-first` `has-skills` `knowledge` `batch-ops` `token-efficient` |

**Key Features:**
- `--llm` mode — compact, structured output for agents
- `notion find` — natural language → Notion filters ("overdue tasks", "urgent pending")
- `notion batch` — multiple operations in one command (minimize tool calls)
- `notion ai prompt` — generates database-specific prompt for agent
- `notion inspect context` — full schema + examples in one shot
- Workspace onboarding skill: auto-discovers databases
- Obsidian sync, CSV/Markdown import, backup, validation, health check

**Example:**
```bash
notion find "overdue tasks" -d <db_id>
notion batch --llm --data '[{"op":"get","type":"page","id":"abc"},{"op":"update",...}]'
notion page create --parent <db_id> --title "New Task" --prop "Status=Todo"
notion search "project plan" --type page
```

---

### Vibe-Notion

> Notion automation CLI for AI agents.

| | |
|---|---|
| **Repo** | [devxoul/vibe-notion](https://github.com/devxoul/vibe-notion) |
| **Stars** | ⭐ 16 |
| **Language** | TypeScript |
| **Tags** | `community` `agent-first` `knowledge` |

---

### Notion CLI (Enterprise)

> Enterprise-grade Notion CLI for AI agents — advanced retry, caching, Go.

| | |
|---|---|
| **Repo** | [Coastal-Programs/notion-cli](https://github.com/Coastal-Programs/notion-cli) |
| **Stars** | ⭐ 9 |
| **Language** | Go |
| **Tags** | `community` `agent-first` `knowledge` |

---

### Feishu Docx Exporter

> Feishu/Lark Docs & Sheets ↔ Markdown with OAuth, CLI, TUI & Claude Skills.

| | |
|---|---|
| **Repo** | [leemysw/feishu-docx](https://github.com/leemysw/feishu-docx) |
| **Stars** | ⭐ 136 |
| **Language** | Python |
| **Tags** | `community` `agent-friendly` `has-skills` `knowledge` `markdown` |

---

## Research & Academic

### PyOverleaf

> Python API and CLI for Overleaf — sync LaTeX projects between local and Overleaf.

| | |
|---|---|
| **Repo** | [jkulhanek/pyoverleaf](https://github.com/jkulhanek/pyoverleaf) |
| **Stars** | ⭐ 41 |
| **Language** | Python |
| **Install** | `pip install pyoverleaf` |
| **Tags** | `community` `agent-friendly` `research` `markdown` |

**Key Features:**
- List/create/archive/rename projects
- Upload/download individual files or full project zips
- Move, rename, delete files; create folders
- Comments access, live changes
- Auth via browser cookies (Chrome/Firefox)

**Example:**
```bash
pyoverleaf ls                                      # list projects
pyoverleaf ls project-name/path/                   # list files
echo "new content" | pyoverleaf write project-name/file.tex
pyoverleaf read project-name/main.tex
pyoverleaf download-project project-name output.zip
```

---

### olcli (Overleaf CLI — JS)

> Command-line interface to sync, manage, and compile LaTeX projects from terminal.

| | |
|---|---|
| **Repo** | [aloth/olcli](https://github.com/aloth/olcli) |
| **Stars** | ⭐ 21 |
| **Language** | JavaScript |
| **Tags** | `community` `agent-friendly` `research` |

---

### Overleaf Sync RS

> Bidirectional sync between Overleaf and local filesystem (Rust).

| | |
|---|---|
| **Repo** | [katzper-michno/overleaf-sync-rs](https://github.com/katzper-michno/overleaf-sync-rs) |
| **Stars** | ⭐ 10 |
| **Language** | Rust |
| **Tags** | `community` `agent-friendly` `research` |

---

### Overleap

> Real-time bidirectional sync between Overleaf and local filesystem.

| | |
|---|---|
| **Repo** | [Axect/overleap](https://github.com/Axect/overleap) |
| **Stars** | ⭐ 3 |
| **Language** | JavaScript |
| **Tags** | `community` `agent-friendly` `research` |

---

### LeafLink

> Lightweight CLI for syncing local LaTeX with Overleaf — pull/push workflows, pseudo real-time.

| | |
|---|---|
| **Repo** | [xiongqi123123/LeafLink](https://github.com/xiongqi123123/LeafLink) |
| **Stars** | ⭐ 3 |
| **Language** | Python |
| **Tags** | `community` `agent-friendly` `research` |

---

### Overleaf CLI (AI-focused)

> Enable AI tools (Claude Code, Cursor) to directly edit Overleaf projects via local file sync.

| | |
|---|---|
| **Repo** | [BruceChenSF/overleaf-cli](https://github.com/BruceChenSF/overleaf-cli) |
| **Stars** | ⭐ 1 |
| **Language** | TypeScript |
| **Tags** | `community` `agent-first` `research` |

---

### pubtab

> Bidirectional Excel ↔ LaTeX table converter with style-preserving roundtrip.

| | |
|---|---|
| **Repo** | [Galaxy-Dawn/pubtab](https://github.com/Galaxy-Dawn/pubtab) |
| **Stars** | ⭐ 265 |
| **Language** | Python |
| **Tags** | `community` `agent-friendly` `research` |

---

## Email

### Himalaya

> CLI to manage emails via IMAP/SMTP — list, read, write, reply, forward, search, organize.

| | |
|---|---|
| **Repo** | [pimalaya/himalaya](https://github.com/pimalaya/himalaya) |
| **Stars** | ⭐ 3,400+ |
| **Language** | Rust |
| **Install** | `brew install himalaya` or `cargo install himalaya` |
| **Tags** | `community` `agent-friendly` `has-skills` `productivity` |

**Key Features:**
- Multi-account IMAP/SMTP support
- MML (MIME Meta Language) for message composition
- OpenClaw agent skill available

---

### Gmail via `gws`

> Gmail operations through Google Workspace CLI.

| | |
|---|---|
| **Commands** | `gws gmail +send`, `+reply`, `+reply-all`, `+forward`, `+triage`, `+watch` |
| **Tags** | `official` `agent-first` `has-skills` `productivity` |

See [Google Workspace CLI](#google-workspace-cli-gws) above.

---

## Social & Messaging

### xurl (X/Twitter CLI)

> CLI for authenticated X (Twitter) API v2 requests.

| | |
|---|---|
| **Skills** | Available as OpenClaw agent skill |
| **Tags** | `community` `agent-friendly` `has-skills` `social` |

**Capabilities:** Post tweets, reply, quote, search, read posts, manage followers, send DMs, upload media.

---

### wacli (WhatsApp CLI)

> Send WhatsApp messages and search/sync history.

| | |
|---|---|
| **Skills** | Available as OpenClaw agent skill |
| **Tags** | `community` `agent-friendly` `has-skills` `messaging` |

---

### Slack CLI (Agent-Friendly)

> Slack CLI with OAuth auth and agentic design principles.

| | |
|---|---|
| **Repo** | [tumf/slack-rs](https://github.com/tumf/slack-rs) |
| **Stars** | ⭐ 2 |
| **Language** | Rust |
| **Tags** | `community` `agent-first` `messaging` |

---

## Developer Tools

### GitHub CLI (`gh`)

> The gold standard of agent-friendly CLIs.

| | |
|---|---|
| **Repo** | [cli/cli](https://github.com/cli/cli) |
| **Stars** | ⭐ 50,000+ |
| **Language** | Go |
| **Install** | `brew install gh` |
| **Tags** | `official` `agent-friendly` `has-skills` `dev-tools` |

**Capabilities:** Issues, PRs, CI/CD, code review, releases, API queries, gists, repos.

---

## Agent Bridges

*These aren't service CLIs per se, but they connect coding agents to messaging platforms.*

### CC-Connect

> Bridge local AI coding agents to messaging platforms.

| | |
|---|---|
| **Repo** | [chenhg5/cc-connect](https://github.com/chenhg5/cc-connect) |
| **Stars** | ⭐ 3,300 |
| **Language** | Go |
| **Tags** | `community` `bridge` `messaging` |

**Bridges:** Claude Code, Cursor, Gemini CLI, Codex → Feishu/Lark, DingTalk, Slack, Telegram, Discord

---

### GolemBot

> Any Agent × Any Provider × Anywhere.

| | |
|---|---|
| **Repo** | [0xranx/golembot](https://github.com/0xranx/golembot) |
| **Stars** | ⭐ 222 |
| **Language** | TypeScript |
| **Tags** | `community` `bridge` `messaging` |

**Bridges:** Cursor, Claude Code, OpenCode, Codex → Slack, Telegram, Discord, Feishu, DingTalk, WeCom

---

### Feishu Claude Code Bridge

> Bridge Claude Code CLI with Feishu/Lark via WebSocket.

| | |
|---|---|
| **Repo** | [joewongjc/feishu-claude-code](https://github.com/joewongjc/feishu-claude-code) |
| **Stars** | ⭐ 36 |
| **Language** | Python |
| **Tags** | `community` `bridge` `messaging` |

---

## Design Patterns

The best agent CLIs share these design principles:

### Output
- **JSON by default** + `--format table|csv|ndjson`
- **`--llm` mode** for token-efficient output (notion-cli-agent)
- **NDJSON streaming** for paginated results

### Command Architecture
- **Three-layer pattern** (lark-cli, gws):
  1. **Shortcuts** (`+agenda`, `+send`) — human & agent friendly
  2. **API commands** — 1:1 with endpoints
  3. **Raw API** — full coverage pass-through
- **Schema introspection** for agents to discover parameters

### Auth
- **Non-blocking auth** — return URL for human to approve
- **Environment variables** as primary auth
- **OS keyring** for credential storage

### Agent Integration
- **Agent Skills (SKILL.md)** — structured instructions for LLM context
- **Batch operations** to minimize tool calls
- **`--dry-run`** for safety
- **Progressive disclosure** — small SKILL.md + on-demand references

---

## Gaps & Opportunities

Services that **don't yet have a good agent-friendly CLI**:

| Service | Status | Opportunity |
|---------|--------|-------------|
| Jira | Community CLIs exist, none agent-optimized | High demand |
| Confluence | No agent CLI | Pairs with Jira |
| Asana | No known CLI | Large user base |
| Trello | No agent CLI | Simpler scope |
| Todoist | Has CLI, not agent-designed | Quick win |
| Airtable | No agent CLI | Popular with teams |
| Figma | No CLI (API exists) | Design workflows |
| Zoom | No agent CLI | Meeting management |
| HuggingFace | `huggingface-cli` exists, not agent-optimized | ML workflows |
| arXiv | No CLI | Research workflows |
| Semantic Scholar | No CLI | Paper discovery |

---

## Contributing

Know an agent-friendly CLI that's missing? Open a PR!

**Inclusion criteria:**
1. Must be a CLI tool (not a library, SDK, or MCP server only)
2. Must work well with AI agents (structured output, composable commands)
3. Bonus: ships agent skill files

**Format:** Follow the existing table + description format. Include repo link, stars, language, install command, and tags.

---

## License

This collection is [CC0 1.0 Universal](LICENSE) — public domain. Individual tools have their own licenses.

---

<p align="center">
  <em>Curated by <a href="https://github.com/shuyhere">@shuyhere</a> • Last updated: March 2026</em>
</p>
