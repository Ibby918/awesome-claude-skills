---
name: awesome-claude-skills
description: >
  Use this skill whenever the user wants to automate a SaaS application or connect Claude
  to an external service. Trigger for requests involving specific apps like "automate Supabase",
  "create a GitHub issue", "send a Slack message", "update a Notion page", "add a row to Google
  Sheets", "create a Stripe customer", "automate Jira", or any request to integrate Claude
  with one of 500+ supported services. Also trigger when the user asks "can Claude connect to X"
  or "automate my workflow in Y app". Skip for pure coding tasks that don't involve external
  service integration. Skip for general API questions not requiring Composio. When the user
  mentions a specific app (Supabase, Stripe, GitHub, Slack, Notion, Google, Jira, etc.) in
  the context of automation or integration — this skill covers it.
---

# Awesome Claude Skills — 100+ Skills for Claude Code

A curated collection of skills for automation, development, data workflows and SaaS integrations.
App automation (500+ services) powered by Composio.

## Categories

### Development & Code
- `github-automation` — Issues, PRs, repos, branches, code search, actions
- `gitlab-automation` — MRs, issues, projects, pipelines, branches
- `supabase-automation` — SQL queries, tables, edge functions, storage buckets
- `stripe-automation` — Charges, customers, products, subscriptions, refunds
- `playwright-automation` — Browser testing and UI automation
- `mcp-builder` — Guide for building MCP servers to connect any API
- `changelog-generator` — User-facing changelogs from git commit history
- `skill-creator` — Create new Claude skills

### Productivity & Files
- `notion-automation` — Pages, databases, blocks, comments, search
- `google-drive-automation` — Upload, download, search, share, organise
- `one-drive-automation` — Files, folders, sharing, versioning
- `file-organizer` — Intelligently organise files and folders
- `invoice-organizer` — Organise invoices for tax prep

### Communication
- `slack-automation` — Messages, channels, search, reactions, threads
- `gmail-automation` — Send, reply, search, labels, drafts, attachments
- `outlook-automation` — Emails, folders, contacts, calendar
- `discord-automation` — Messages, channels, roles, reactions
- `microsoft-teams-automation` — Messages, channels, meetings

### Data & Spreadsheets
- `googlesheets-automation` — Read/write cells, formatting, formulas, batch ops
- `airtable-automation` — Records, tables, bases, views, field management
- `coda-automation` — Docs, tables, rows, formulas, automations

### Calendar & Scheduling
- `google-calendar-automation` — Events, attendees, free/busy, recurring
- `calendly-automation` — Events, scheduling links, availability

### Analytics
- `amplitude-automation` — Events, cohorts, user properties, analytics
- `google-analytics-automation` — Reports, dimensions, metrics
- `mixpanel-automation` — Events, funnels, cohorts, JQL

### Project Management
- `jira-automation` — Issues, boards, sprints, JQL queries
- `asana-automation` — Tasks, projects, sections, workspaces
- `linear-automation` — Issues, projects, cycles, teams
- `notion-automation` — Pages, databases, blocks

### E-commerce & Payments
- `stripe-automation` — Charges, customers, subscriptions, refunds
- `shopify-automation` — Products, orders, customers, inventory

### Document Processing
- `docx` — Create, edit, analyse Word documents
- `pdf` — Extract, merge, annotate PDFs
- `xlsx` — Spreadsheet manipulation, formulas, charts
- `pptx` — Read and generate slide decks

## How to Use

Skills auto-activate when you mention a supported app. Or ask directly:

```
"Create a GitHub issue for this bug I found"
"Add a row to my trading journal Google Sheet"
"Send a Slack message to #trading-alerts with this signal"
"Create a Stripe customer for this new user"
"Query my Supabase database for all open trades"
```

## Installing Individual Skills

To install a specific skill from this collection:

```bash
/plugin install supabase-automation@awesome-claude-skills
/plugin install stripe-automation@awesome-claude-skills
/plugin install github-automation@awesome-claude-skills
/plugin install googlesheets-automation@awesome-claude-skills
```

## App Automation Setup (Composio)

For real app actions (send emails, create issues, post Slack messages), the
`connect-apps` plugin from this collection handles authentication:

```bash
claude --plugin-dir ./connect-apps-plugin
/connect-apps:setup    # Enter your free Composio API key
```

Get a free key at [platform.composio.dev](https://platform.composio.dev)
