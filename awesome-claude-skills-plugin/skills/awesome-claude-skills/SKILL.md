---
name: awesome-claude-skills
description: Use when the user wants to automate or integrate a SaaS application — Supabase, Stripe, GitHub, Slack, Notion, Google Sheets, Jira, Gmail, or any of 500+ services. Triggers on "automate X in Y app", "connect Claude to Z service", "create a GitHub issue", "send a Slack message", "add a row to Google Sheets", or any SaaS integration request.
---

# Awesome Claude Skills — 100+ Skills for SaaS Automation

Curated collection covering development tools, SaaS automation, data workflows, and business
integrations. App automation for 500+ services powered by Composio.

## When to Use

- Automating a specific SaaS app (Stripe, Supabase, GitHub, Slack, Notion, etc.)
- Connecting Claude Code to external services with real actions
- Document processing (Word, PDF, Excel, PowerPoint)

**Skip when:** The task is pure coding with no external service integration.

## Key Skills by Category

### Development
| Skill | What it does |
|---|---|
| `supabase-automation` | SQL queries, tables, edge functions, storage |
| `github-automation` | Issues, PRs, repos, branches, code search |
| `stripe-automation` | Charges, customers, products, subscriptions |
| `mcp-builder` | Build MCP servers for any API |
| `changelog-generator` | User-facing changelogs from git history |

### Productivity
| Skill | What it does |
|---|---|
| `notion-automation` | Pages, databases, blocks, comments |
| `google-drive-automation` | Upload, download, search, share |
| `slack-automation` | Messages, channels, reactions, threads |
| `gmail-automation` | Send, reply, search, labels, drafts |
| `googlesheets-automation` | Read/write cells, formulas, batch ops |

### Documents
| Skill | What it does |
|---|---|
| `docx` | Create, edit, analyse Word documents |
| `pdf` | Extract, merge, annotate PDFs |
| `xlsx` | Spreadsheets, formulas, charts |
| `pptx` | Generate and read slide decks |

### Calendar & Scheduling
`google-calendar-automation`, `calendly-automation`, `outlook-calendar-automation`

### Project Management
`jira-automation`, `asana-automation`, `linear-automation`, `notion-automation`

### E-commerce & Payments
`stripe-automation`, `shopify-automation`, `square-automation`

## Usage

Skills auto-activate when you mention a supported app. Or ask directly:

```
"Create a GitHub issue for this bug"
"Add a row to my Google Sheet"
"Send a Slack message to #trading-alerts"
"Create a Stripe customer"
"Query my Supabase DB for open trades"
```

## Installing Individual Skills

```bash
/plugin install supabase-automation@awesome-claude-skills
/plugin install stripe-automation@awesome-claude-skills
/plugin install github-automation@awesome-claude-skills
```

## App Authentication (Composio)

Real actions (send emails, create issues, post messages) need Composio auth:

```bash
claude --plugin-dir ./connect-apps-plugin
/connect-apps:setup    # Enter free Composio API key
```

Free key: [platform.composio.dev](https://platform.composio.dev)

## Common Mistakes

- Expecting real app actions without Composio setup — skills provide guidance, Composio provides execution
- Looking for a skill that doesn't exist — check [ComposioHQ/awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills) for the full list
- Installing the whole collection when you only need one skill — use `/plugin install <skill-name>@awesome-claude-skills`
