# LifeOS Local

A minimal operating system for your life—AI agents + plain text. **Local-first, no cloud required.**

> **Note**: This is the offline/markdown-only version. For cloud-synced tasks with phone access, see [LifeOS](https://github.com/sanjeed5/life-os) (coming soon).

## Philosophy

- **One file**: Live in `today.md`
- **Plain text**: Everything is Markdown
- **Local-first**: Your data stays on your machine
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
| `user.md` | Your profile and preferences (created by `/onboard`) |
| `inbox.md` | Quick capture, projects, habits, someday ideas |
| `wins.md` | Accomplishments worth remembering |
| `journal/` | Archived days (Year/Month) |
| `AGENTS.md` | Instructions for the AI agent |

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
