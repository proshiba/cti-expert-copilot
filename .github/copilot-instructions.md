# CTI Expert repository instructions

When a request is about cyber threat intelligence or OSINT, use CTI Expert:

1. Treat the repository root (the directory containing `SKILL.md`) as
   `$SKILL_DIR`.
2. Read `AGENTS.md`, then `SKILL.md`, before starting the investigation.
3. Detect the operating system once and use the matching shell and package
   manager. Prefer `uv run` for the Python utilities.
4. Follow the public-source-only ethics boundary, evidence provenance, confidence
   scoring, and reporting rules in `SKILL.md`.
5. Never claim that a command, collection step, or report build ran unless it did.

For a focused CTI session, select the repository's `cti-expert` custom agent in
GitHub Copilot CLI with `/agent`. After selection, enter CTI commands without a
leading slash (for example, `case example.com`); slash commands belong to the CLI.
