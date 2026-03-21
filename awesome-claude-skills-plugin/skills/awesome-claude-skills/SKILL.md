---
name: awesome-claude-skills
description: Connects Claude to 500+ external apps and services via Composio. Use when the user wants to automate Supabase, Stripe, GitHub, Slack, Notion, Google Sheets, Jira, or any other SaaS tool — creating records, sending messages, running queries, or triggering workflows.
---

# Awesome Claude Skills

100+ skills for SaaS automation, development tools, document processing, and business workflows.
App integrations powered by Composio (500+ services).

## Workflow

### Automating an external app

Skills auto-activate when you mention a supported app. Just describe what you want:

```
"Create a GitHub issue for this bug"
"Add a row to my trading journal Google Sheet"
"Send a Slack message to #alerts with this signal"
"Query my Supabase database for all open trades"
"Create a Stripe customer for this new user"
"Create a Notion page summarising today's research"
```

### Installing a specific skill

```bash
/plugin install <skill-name>@awesome-claude-skills
```

Example:
```bash
/plugin install supabase-automation@awesome-claude-skills
/plugin install stripe-automation@awesome-claude-skills
/plugin install github-automation@awesome-claude-skills
```

### Connecting apps (Composio setup)

For real write actions (send emails, create issues, post Slack messages):

```bash
claude --plugin-dir ./connect-apps-plugin
/connect-apps:setup
```

Get a free API key at [platform.composio.dev](https://platform.composio.dev).

## Available skills by category

See [reference/skill-list.md](reference/skill-list.md) for the complete list of 100+ skills.

### Most relevant for development

| Skill | What it does |
|---|---|
| `supabase-automation` | SQL queries, tables, edge functions, storage |
| `stripe-automation` | Charges, customers, subscriptions, refunds |
| `github-automation` | Issues, PRs, repos, branches, actions |
| `gitlab-automation` | MRs, issues, projects, pipelines |
| `mcp-builder` | Guide for building MCP servers |

### Most relevant for productivity

| Skill | What it does |
|---|---|
| `notion-automation` | Pages, databases, blocks, search |
| `slack-automation` | Messages, channels, threads |
| `gmail-automation` | Send, reply, search, labels |
| `google-calendar-automation` | Events, attendees, scheduling |
| `googlesheets-automation` | Read/write cells, formulas, batch ops |
| `jira-automation` | Issues, boards, sprints, JQL |
