---
name: cti-expert
description: Use for cyber threat intelligence, OSINT investigations, exposure reviews, infrastructure pivots, IOC analysis, threat modeling, and sourced intelligence reports.
---

# CTI Expert for GitHub Copilot

The complete skill is stored at the repository root so Claude Code, Codex, and
GitHub Copilot share one authoritative workflow instead of maintaining divergent
copies.

1. Resolve `$SKILL_DIR` as the repository root three levels above this file.
2. Read `$SKILL_DIR/AGENTS.md` and `$SKILL_DIR/SKILL.md` in full before acting.
3. Follow the requested command and load referenced resources relative to
   `$SKILL_DIR`.
4. Run scripts from `$SKILL_DIR/scripts`; prefer `uv run` as specified by the
   cross-agent contract.

The root `SKILL.md` command catalog, safety boundary, evidence model, tool cascade,
and output requirements are authoritative if this dispatcher conflicts with them.
