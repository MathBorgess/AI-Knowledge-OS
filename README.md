# AI Knowledge OS

**Context Engine** (Protocol Kernel) for technology professionals — not a PKM app, not a news aggregator, not a prompt pack.

It helps you turn dispersed signals into actionable context and close the loop through learning and production. The public repo is the **framework**. Your knowledge lives in your **private instance**.

## Constitution

| This project **is** | This project **is not** |
|---------------------|-------------------------|
| A Protocol Kernel for personal/professional context | A personal Obsidian vault |
| Contracts + cycle + agent/provider packs | A dump of one person's notes |
| A system you instantiate privately | A requirement that your knowledge live upstream |
| Tool-agnostic by design | Locked to Cursor, Claude, Obsidian, or one LLM |

## Start

1. Read [VISION.md](VISION.md) and [MISSION.md](MISSION.md)
2. Read [ARCHITECTURE.md](ARCHITECTURE.md)
3. Follow [docs/getting-started.md](docs/getting-started.md)
4. Copy [templates/instance/](templates/instance/) into a **private** repo for your living Knowledge Base

## Agent packs — try one right now

An **agent pack** is a skill your AI coding assistant (Cursor, Claude Code) can run
directly from this repo — no separate app, no dashboard. Two are ready to use:

| Pack | What it does | Good for |
|------|---------------|----------|
| [`agents/trend-radar/`](agents/trend-radar/) | Pulls signals from multiple sources, clusters them, and surfaces what deserves attention today | Staying on top of a fast-moving space without doom-scrolling |
| [`agents/sales-motion/`](agents/sales-motion/) | Listens for public pain signals, gives you an auditable Go/No-Go verdict on whether a market exists, and only then drafts brand-voiced content — **never sends anything on its own** | Solo operators and small agencies juggling several clients: validate demand before spending content effort on any one of them, without losing the human judgment part |

If you run marketing/growth for more than one account and don't have time to manually
watch every channel, `sales-motion` is built for exactly that: it does the listening and
scoring, you make the call, it drafts, you send. No auto-DMs, no spam, no black box.

**Try it in your own agent (3 steps):**

1. Bootstrap a private instance ([step 2 of getting-started.md](docs/getting-started.md#2-create-a-private-instance-from-the-template)), or just clone this repo to try it first.
2. Install the skill: it's already at `agents/sales-motion/SKILL.md`, synced to `.cursor/skills/sales-motion/SKILL.md` and `.claude/skills/sales-motion/SKILL.md` — open the repo in Cursor or Claude Code and it's picked up automatically.
3. Ask your agent: **"Run sales motion"** (or **"Run trend radar"**). It'll walk you through setup in chat — one question at a time, nothing sent without your explicit approval.

Full walkthrough: [docs/getting-started.md §4](docs/getting-started.md#4-optional--enable-agent-packs-trend-radar-sales-motion), [docs/sales/using-agents.md](docs/sales/using-agents.md).

## Layout (public)

| Path | Role |
|------|------|
| `contracts/` | Artifact schemas |
| `engine/` | Cycle protocol |
| `wiki/` | Knowledge Base **scaffold** only |
| `agents/` | Skill packs |
| `providers/` | Reference providers |
| `docs/` | Institutional + feature docs |

Full governance: [GOVERNANCE.md](GOVERNANCE.md)
