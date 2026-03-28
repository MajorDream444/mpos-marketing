# SYSTEM MAP — MAJOR PRIME OS

This document is the single source of truth for where everything lives across local, GitHub, and Obsidian.

---

## Architecture

```
YOU
↓
MAJOR PRIME OS (brain + control)
↓
CLAUDE CODE (builder + execution)
↓
CLAWBOT AGENTS (specialized workers)
↓
OUTPUT (leads, content, sales, systems)
```

---

## GitHub Repos (MajorDream444)

| Repo | Status | Purpose | Local Path |
|------|--------|---------|------------|
| `mpos-marketing` | Active | Marketing division — agents, campaigns, playbooks, skills | `/Users/majordreamwilliams/mpos-marketing/` |
| `build-while-you-heal` | Active | Retreat product — website, application, sales system | `/Users/majordreamwilliams/major-prime-bot/major-prime-retreat-os/build-while-you-heal/` |
| `ui-ux-pro-max-skill` | Fork/Integrated | UX + conversion intelligence skill | Integrated → `mpos-marketing/skills/ux_intelligence/` |
| `ATRA` | Active | West African Trade Gateway | `/Users/majordreamwilliams/ATRA/` |
| `everything-claude-code` | Fork | Agent harness performance system | Reference only |
| `OpenClaw (via ClawX/picoclaw)` | Fork | Orchestration runtime | Local: `/Users/majordreamwilliams/OpenClaw 7-Day Lab/` |

---

## Local Directories

| Path | Contains |
|------|----------|
| `/Users/majordreamwilliams/mpos-marketing/` | Marketing OS — canonical version, synced to GitHub |
| `/Users/majordreamwilliams/major-prime-bot/` | Main bot runtime — flows, mini apps, dashboard |
| `/Users/majordreamwilliams/major-prime-bot/major-prime-retreat-os/` | Retreat product system |
| `/Users/majordreamwilliams/OpenClaw 7-Day Lab/` | OpenClaw toolpack, skills, catalog |
| `/Users/majordreamwilliams/operative/` | Operative framework |
| `/Users/majordreamwilliams/mcp/` | Hanzo MCP server |
| `/Users/majordreamwilliams/vault/` | Secondary Obsidian vault (Tasks only) |

---

## Obsidian Vault (Primary — iCloud Synced)

**Location:** `/Users/majordreamwilliams/Library/Mobile Documents/iCloud~md~obsidian/Documents/Major OS/`

| Folder | Purpose |
|--------|---------|
| `00_Dashboard` | Master control dashboard |
| `01_Projects` | Active projects (Build While You Heal, Lucky Pirate, etc.) |
| `02_Companies` | Company profiles |
| `03_Research` | Research notes |
| `04_AI_Agents` | Agent definitions and configs |
| `05_Content` | Content library |
| `06_Deals` | Deal tracking (Gold Tanzania, Mauritania Mining, etc.) |
| `07_People` | People profiles |
| `08_Knowledge` | Knowledge base |
| `10_144_AGInts` | 144 Agent Intelligence system |
| `crew/` | Active crew agents (Captain, Scout, Storyteller, Broadcaster, Closer) |
| `SKILL/` | Skill definitions |
| `Major Tees/` | Lucky Pirate Campaign |
| `ClawPack/` | OpenClaw resources |
| `hanzo-agent-os/` | Hanzo agent OS |

---

## Active Marketing Agents

| Agent | File | Role |
|-------|------|------|
| Captain | `agents/captain.md` | Orchestration |
| Scout | `agents/scout.md` | Lead intelligence |
| Storyteller | `agents/storyteller.md` | Content engine |
| Distributor | `agents/distributor.md` | Traffic engine |
| Closer | `agents/closer.md` | Revenue engine |
| Conversion Architect | `agents/conversion_architect.md` | UX + funnel optimization |

---

## Active Campaigns

| Campaign | File | Status |
|---------|------|--------|
| Build While You Heal (May 2026) | `campaigns/retreat_may_2026.md` | Active |
| Authority Engine | `campaigns/authority_engine.md` | Active (parallel) |
| Viva La Contour | `campaigns/viva_la_contour.md` | Queued |

---

## Skills Stack

| Skill | Location | Powers |
|-------|----------|--------|
| Lead Scout | `skills/lead_scout.md` | Scout agent |
| Content Engine | `skills/content_engine.md` | Storyteller agent |
| Outreach | `skills/outreach.md` | Closer agent |
| Qualification | `skills/qualification.md` | Closer agent |
| Conversion | `skills/conversion.md` | Closer agent |
| Client Update | `skills/client_update.md` | All agents |
| Reporting | `skills/reporting.md` | Captain agent |
| UI/UX Pro Max | `skills/ux_intelligence/ui_ux_pro_max_skill/` | Conversion Architect |

---

## Tech Stack

| Layer | Tool |
|-------|------|
| Builder Brain | Claude Code |
| Orchestration | OpenClaw / Clawbot |
| Web Intelligence | Firecrawl (planned) |
| Memory | Obsidian (iCloud) + repo files |
| Database | Supabase (planned) |
| Alerts | Telegram (planned) |
| Tracking | Google Sheets (planned) |
| Hosting | GitHub |

---

## Daily Command Template

```
Run MPOS_MARKETING for today.

Campaign: [name]
Focus: [goal]

Assign:
- Scout: [task]
- Storyteller: [task]
- Distributor: [task]
- Closer: [task]
- Conversion Architect: [task if needed]
```

---

## Sync Rules

1. **Source of truth for marketing system** = `mpos-marketing` GitHub repo
2. **Source of truth for client/deal data** = Obsidian vault (`06_Deals`, `07_People`)
3. **Source of truth for product** = `build-while-you-heal` repo
4. **Any new agent, skill, or campaign** = must be added to BOTH the repo AND this SYSTEM_MAP
5. **Weekly** = pull latest from GitHub, update Obsidian notes, log results

---

*Last updated: 2026-03-28*
