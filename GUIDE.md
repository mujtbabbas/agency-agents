# Reader's Guide — agency-agents ("The Agency")

## What this project is

**The Agency** is a complete AI agency in a repository: a large roster of
ready-to-use **AI specialist agents** — frontend developers, security
auditors, marketers, product managers, game developers and dozens more — each
defined as a Markdown persona file with a personality, a process and concrete
deliverables. The agents are designed to be activated inside AI coding tools
(Claude Code first-class, with integrations for GitHub Copilot, Gemini CLI,
Cursor, Aider, Windsurf and others) or simply read as reference playbooks.

## How the content is organised

Agents live in **one folder per division**, mirroring the roster in the
README:

- **Build & design:** `engineering`, `design`, `testing`, `security`,
  `spatial-computing`, `game-development` (with cross-engine plus Unity,
  Unreal, Godot, Blender and Roblox groupings).
- **Business:** `product`, `project-management`, `marketing`, `paid-media`,
  `sales`, `finance`, `strategy`, `support`.
- **Knowledge & specialist:** `academic`, `gis`, `healthcare`, `research`,
  `specialized`.

Supporting structure:

- [`README.md`](README.md) — the catalogue: Quick Start, the full Agency
  Roster by division, real-world use-case scenarios, agent design philosophy
  and stats. (This guide was written from the README's section outline and the
  repository tree.)
- `divisions.json` and `tools.json` — machine-readable indexes of the
  divisions and the supported tool integrations.
- `integrations/` — per-tool integration material; `scripts/` — the
  conversion/install scripts the README's Quick Install section uses.
- `examples/` — worked examples. `CONTRIBUTING.md` explains how to add a new
  agent or improve an existing one.

## How to use it

1. Start at the README's **Quick Start**: install the companion app, use the
   agents with Claude Code, copy them into another supported tool via the
   integrations flow, or just read them as reference.
2. Browse the division folders (or the README roster) to find the specialist
   you need, then activate that agent in your tool session.
3. The README's **Real-World Use Cases** show how several agents are combined
   on one job — startup MVPs, campaign launches, enterprise features and
   more.

## About this standalone edition

This repository is a standalone edition of
[msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents),
converted from a fork into its own repository and enhanced in place. See
[`ENHANCEMENTS.md`](ENHANCEMENTS.md) for what this edition adds and
[`CHANGELOG.md`](CHANGELOG.md) for its version history (v1.0.0 upstream
baseline, v1.1.0 enhancements). All original work belongs to the upstream
contributors; licence MIT (see `LICENSE`).
