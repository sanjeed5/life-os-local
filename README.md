# LifeOS

A minimal operating system for your life—AI agents + plain text.

## Philosophy

- **One file**: Live in `today.md`
- **Plain text**: Everything is Markdown
- **AI handles the busywork**: Archiving, migrating, reminding

## Quick Start

1. Clone this repo
2. Open in [Cursor](https://cursor.sh), [Cursor CLI](https://cursor.com/cli) or any [AGENTS.md](https://agents.md)-compatible CLI/Editor
3. Run `/setup-private` to create your own private repo (keeps your data safe) or just DIY it
4. Run `/onboard` to set up your profile

## Files

| File | Purpose |
|------|---------|
| `today.md` | Your dashboard—plan and log for today |
| `backlog.md` | Future tasks, projects, ideas |
| `user.md` | Your identity and preferences for the AI |
| `journal/` | Archived days (Year/Month) |
| `AGENTS.md` | Instructions for your AI assistant |

## Commands

| Command | What it does |
|---------|--------------|
| `/setup-private` | Create your private repo (run once after cloning) |
| `/onboard` | Set up your profile |
| `/start` | Archive yesterday, pull tasks, plan today |
| `/finish` | Archive today, migrate incomplete tasks, celebrate wins |
| `/review` | Weekly reflection |
| `/unstuck` | Gentle help when you're overwhelmed or can't start |

## Integrations (Optional)

LifeOS works standalone, but gets smarter with [MCP](https://modelcontextprotocol.io) integrations:

- **Google Workspace** - Calendar, Gmail, Drive ([Setup Guide](https://github.com/taylorwilsdon/google_workspace_mcp#quick-start))
- **Browse more** - [MCP servers](https://github.com/modelcontextprotocol/servers)

---

⭐ Star if you find this useful · PRs welcome · MIT License
