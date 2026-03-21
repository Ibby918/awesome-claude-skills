---
name: awesome-claude-skills
description: A curated collection of 100+ Claude skills for automation, development, data, and SaaS integrations via Composio. Use when the user needs to automate apps like Supabase, Stripe, GitHub, Slack, Notion, Google Sheets, or any of 500+ services.
---

# Awesome Claude Skills — 100+ Skills for Claude Code

A curated collection of skills covering document processing, development tools, SaaS automation, and business workflows. Powered by Composio for real app integrations.

## When to Use This Skill

- User wants to automate a SaaS tool (Stripe, Supabase, GitHub, Slack, Notion, etc.)
- User wants to connect Claude to external services
- User says "automate X in Y app" or "integrate with Z service"

## Key Skill Categories

### Development
- `supabase-automation` — SQL queries, tables, edge functions, storage
- `github-automation` — Issues, PRs, repos, branches, actions
- `stripe-automation` — Charges, customers, products, subscriptions
- `playwright-automation` — Browser testing and automation
- `mcp-builder` — Build MCP servers for external APIs

### Productivity
- `notion-automation` — Pages, databases, blocks, comments
- `google-drive-automation` — Upload, download, search, share
- `slack-automation` — Messages, channels, search, threads
- `google-calendar-automation` — Events, attendees, scheduling
- `gmail-automation` — Send, reply, search, labels, drafts

### Data & Analytics
- `googlesheets-automation` — Read/write cells, formulas, charts
- `airtable-automation` — Records, tables, bases, views
- `amplitude-automation` — Events, cohorts, analytics queries

### Document Processing  
- `docx` — Create, edit, analyze Word documents
- `pdf` — Extract text, merge, annotate PDFs
- `xlsx` — Spreadsheet manipulation and formulas
- `pptx` — Read and generate slide decks

## How to Use

These skills activate automatically when relevant, or you can reference them directly:

```
"Automate Supabase: create a table for users"
"Create a GitHub issue for this bug"
"Send a Slack message to the #trading channel"
"Add a row to my Google Sheet"
```

## Installing Individual Skills

```bash
/plugin install supabase-automation@awesome-claude-skills
/plugin install stripe-automation@awesome-claude-skills
/plugin install github-automation@awesome-claude-skills
```
