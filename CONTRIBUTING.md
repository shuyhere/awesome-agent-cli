# Contributing to Awesome Agent CLI

Thanks for your interest in contributing! 🎉

## Adding a New CLI Tool

1. Fork this repository
2. Add the tool to the appropriate category in `README.md`
3. Follow the existing format:
   - Table with: Repo link, Stars, Language, Install command, Tags
   - Brief description of key features
   - Code example showing typical usage
4. Apply appropriate tags from the [Tags Legend](README.md#tags-legend)
5. Open a Pull Request

## Criteria for Inclusion

- **Must be a CLI tool** — not a library, SDK, or MCP server only
- **Must work well with AI agents** — structured output (JSON), composable commands
- **Bonus points for:**
  - Agent skill files (SKILL.md / AgentSkills)
  - `--llm` or token-efficient output modes
  - Batch operations
  - `--dry-run` safety
  - Non-blocking auth flows

## Categories

If your tool doesn't fit existing categories, propose a new one. Current categories:

- **Productivity Suites** — Workspace tools (Google, Feishu, etc.)
- **Project Management** — Issue tracking (Linear, Jira, etc.)
- **Knowledge & Docs** — Note-taking, wikis (Notion, etc.)
- **Research & Academic** — LaTeX, paper tools (Overleaf, etc.)
- **Email** — Email clients and management
- **Social & Messaging** — Social media, chat platforms
- **Developer Tools** — GitHub, CI/CD, code tools
- **Agent Bridges** — Connect agents to messaging platforms

## Tag Guidelines

Apply all relevant tags. See the full [Tags Legend](README.md#tags-legend).

Key distinctions:
- `agent-first` — The tool was *designed primarily* for AI agents
- `agent-friendly` — The tool works *well* with agents but serves humans too
- `has-skills` — Ships SKILL.md or compatible agent instruction files

## Style

- Keep descriptions concise and factual
- Include star counts (approximate is fine)
- Link to the actual repository, not mirrors
- Use consistent formatting with existing entries
