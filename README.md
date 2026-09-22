# Awesome Claude Skills

A curated list of **Claude Skills**, **Claude Code plugins**, marketplaces and the tooling around them. Every entry is a real repository whose stars and last-push date were read from the GitHub API on 2026-09-22 — nothing here is listed from memory.

> **What is a skill?** A folder with a `SKILL.md` (front matter + instructions) and optional scripts. Claude Code loads it only when a task matches its description — progressive disclosure for instructions. Skills live in `~/.claude/skills/`, `.claude/skills/`, or inside plugins installed from a marketplace. Longer explanation, marketplace commands and how to write one: [Claude Code skills & plugins guide](https://aiprimetech.io/claude-code/skills/).

## Contents

- [Official (Anthropic)](#official-anthropic)
- [Marketplaces and large collections](#marketplaces-and-large-collections)
- [Design and frontend](#design-and-frontend)
- [Domain skill packs](#domain-skill-packs)
- [Behaviour and configuration](#behaviour-and-configuration)
- [Tooling around Claude Code](#tooling-around-claude-code)
- [Install a skill](#install-a-skill)
- [Contributing](#contributing)

## Official (Anthropic)

- [anthropics/skills](https://github.com/anthropics/skills) — The reference skill set: document skills (PDF, DOCX, XLSX, PPTX), a skill-creator, examples of the SKILL.md format. *(★ 178k · updated 2026-09-10)*
- [anthropics/claude-plugins-official](https://github.com/anthropics/claude-plugins-official) — Anthropic-managed plugin directory — `/plugin marketplace add anthropics/claude-plugins-official`. *(★ 37k · updated 2026-09-21 · Apache-2.0)*
- [anthropics/claude-plugins-community](https://github.com/anthropics/claude-plugins-community) — Community plugin marketplace for Claude Code and Claude Cowork. *(★ 4k · updated 2026-08-25 · Apache-2.0)*
- [anthropics/claude-code](https://github.com/anthropics/claude-code) — Claude Code itself — issues, docs, release notes. *(★ 148k · updated 2026-09-21)*
- [anthropics/claude-code-action](https://github.com/anthropics/claude-code-action) — The GitHub Action that runs Claude Code on issues and pull requests. *(★ 9k · updated 2026-09-19 · MIT)*
- [anthropics/claude-agent-sdk-python](https://github.com/anthropics/claude-agent-sdk-python) — Claude Agent SDK for Python (formerly the Claude Code SDK). *(★ 8k · updated 2026-09-20 · MIT)*
- [anthropics/claude-agent-sdk-typescript](https://github.com/anthropics/claude-agent-sdk-typescript) — Claude Agent SDK for TypeScript. *(★ 2k · updated 2026-09-19)*

## Marketplaces and large collections

- [wshobson/agents](https://github.com/wshobson/agents) — Multi-harness plugin marketplace: agents, skills and commands for Claude Code, Codex and Cursor. *(★ 40k · updated 2026-09-21 · MIT)*
- [alirezarezvani/claude-skills](https://github.com/alirezarezvani/claude-skills) — Hundreds of skills, agents and plugins organised by discipline. *(★ 26k · updated 2026-08-30 · MIT)*
- [hesreallyhim/awesome-claude-code](https://github.com/hesreallyhim/awesome-claude-code) — The broad awesome-list for Claude Code — commands, hooks, workflows, not only skills. *(★ 54k · updated 2026-09-22)*
- [davepoon/buildwithclaude](https://github.com/davepoon/buildwithclaude) — A single hub to browse skills, agents, commands, hooks and plugins. *(★ 4k · updated 2026-09-22 · MIT)*
- [obra/superpowers-marketplace](https://github.com/obra/superpowers-marketplace) — Curated plugin marketplace. *(★ 1k · updated 2026-09-08 · MIT)*
- [numman-ali/n-skills](https://github.com/numman-ali/n-skills) — Curated marketplace that also targets Codex and other agents. *(★ 1k · updated 2026-09-12 · Apache-2.0)*
- [fivetaku/gptaku_plugins](https://github.com/fivetaku/gptaku_plugins) — Plugin marketplace aimed at non-developers becoming AI-native. *(★ 1k · updated 2026-09-08 · MIT)*
- [mhattingpete/claude-skills-marketplace](https://github.com/mhattingpete/claude-skills-marketplace) — Software-engineering workflow skills: git automation, reviews, releases. *(★ 676 · updated 2026-07-25 · Apache-2.0)*
- [ananddtyagi/cc-marketplace](https://github.com/ananddtyagi/cc-marketplace) — A minimal marketplace repo — useful as a template for hosting your own. *(★ 689 · updated 2026-01-18)*
- [mxyhi/ok-skills](https://github.com/mxyhi/ok-skills) — Curated coding-agent skills plus AGENTS.md playbooks. *(★ 490 · updated 2026-09-20 · Apache-2.0)*

## Design and frontend

- [nextlevelbuilder/ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) — Design-intelligence skill for building professional UI; one of the most installed skills there is. *(★ 130k · updated 2026-09-21 · MIT)*
- [bergside/awesome-design-skills](https://github.com/bergside/awesome-design-skills) — List of DESIGN.md and SKILL.md design skill files. *(★ 3k · updated 2026-06-28 · MIT)*

## Domain skill packs

- [coreyhaines31/marketingskills](https://github.com/coreyhaines31/marketingskills) — Marketing: CRO, copywriting, SEO, analytics — for Claude Code and other agents. *(★ 51k · updated 2026-09-05 · MIT)*
- [gamedev-skills/awesome-gamedev-agent-skills](https://github.com/gamedev-skills/awesome-gamedev-agent-skills) — Game development skills: Godot, Unity, Unreal, Phaser. *(★ 1k · updated 2026-09-10 · Apache-2.0)*
- [microsoft/power-platform-skills](https://github.com/microsoft/power-platform-skills) — Microsoft's plugin marketplace for Power Platform development. *(★ 908 · updated 2026-09-22 · MIT)*
- [data-goblin/power-bi-agentic-development](https://github.com/data-goblin/power-bi-agentic-development) — Power BI skills and agents. *(★ 923 · updated 2026-09-19 · GPL-3.0)*
- [quant-sentiment-ai/claude-equity-research](https://github.com/quant-sentiment-ai/claude-equity-research) — Equity-research plugin. *(★ 715 · updated 2026-09-22 · MIT)*
- [arpitg1304/robotics-agent-skills](https://github.com/arpitg1304/robotics-agent-skills) — Robotics skills for production-grade code. *(★ 366 · updated 2026-08-12 · Apache-2.0)*
- [elementalsouls/Claude-OSINT](https://github.com/elementalsouls/Claude-OSINT) — OSINT and recon skills, including secret-pattern detection. *(★ 3k · updated 2026-08-30 · MIT)*
- [feichanggege/ecommerce-visual-copywriting-skill](https://github.com/feichanggege/ecommerce-visual-copywriting-skill) — E-commerce visual copywriting SOP (Chinese). *(★ 800 · updated 2026-09-17 · MIT)*
- [jzOcb/writing-style-skill](https://github.com/jzOcb/writing-style-skill) — Writing-style skill template with auto-learning. *(★ 270 · updated 2026-03-24)*

## Behaviour and configuration

- [multica-ai/andrej-karpathy-skills](https://github.com/multica-ai/andrej-karpathy-skills) — A single CLAUDE.md that changes how Claude Code behaves, derived from Karpathy's guidance. *(★ 215k · updated 2026-04-20)*
- [ykdojo/claude-code-tips](https://github.com/ykdojo/claude-code-tips) — 45+ practical tips from basics to advanced. *(★ 10k · updated 2026-09-02)*
- [agent-sh/agnix](https://github.com/agent-sh/agnix) — Linter and language server for CLAUDE.md, skills and agent configs. *(★ 421 · updated 2026-09-20 · Apache-2.0)*

## Tooling around Claude Code

- [jarrodwatts/claude-hud](https://github.com/jarrodwatts/claude-hud) — Plugin that shows context usage and activity live. *(★ 28k · updated 2026-09-19 · MIT)*
- [farion1231/cc-switch](https://github.com/farion1231/cc-switch) — Desktop switcher for Claude Code / Codex providers, keys and base URLs. *(★ 134k · updated 2026-09-22 · MIT)*
- [openai/codex-plugin-cc](https://github.com/openai/codex-plugin-cc) — Use Codex from inside Claude Code for reviews and delegation. *(★ 33k · updated 2026-07-08 · Apache-2.0)*

## Install a skill

```bash
# personal skill, every project
mkdir -p ~/.claude/skills/my-skill && $EDITOR ~/.claude/skills/my-skill/SKILL.md

# from a marketplace
/plugin marketplace add anthropics/claude-plugins-official
/plugin install <name>@<marketplace>
```

A minimal `SKILL.md`:

```markdown
---
name: release-notes
description: Write release notes from the git log in this repo's house style. Use when asked for a changelog.
---
1. Run `git log --oneline <last-tag>..HEAD`.
2. Group by area, drop chores, one user-facing line per change.
```

## Contributing

Open a pull request with the repository, a one-line description of what the skill does, and which agents it targets. Entries must be public repositories with a `SKILL.md` or a plugin manifest; star counts are refreshed from the API, not edited by hand.

## Licence

[CC0 1.0](LICENSE) — do what you like with the list itself.
