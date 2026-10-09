# FocusCave v1.0.0

A lightweight open-source agent skill combining concise output inspired by Caveman with *selective* divergent exploration inspired by ADHD. Independent implementation, not affiliated with either project.

## Install
Copy `skills/focuscave/` into `.codex/skills/` for Codex or `.claude/skills/` for Claude Code. Ready-made directory layouts are included in this archive. For project installation, copy the `.codex` or `.claude` folder into the project root. Restart the agent if necessary.

Ask the agent to **use focuscave** or **use focuscave explore** for complex tasks. Some agents discover skills automatically; others require explicit invocation.

## How it works
- Short, factual answers; no filler.
- Single-solution default; explore alternatives only when uncertainty warrants it.
- Limit file reads and redundant tool calls.
- Preserve safety, correctness, tests and warnings.
- No extra runtime, dependencies or model calls.

## Limitations
This is an instruction-based skill, not a token proxy. Savings depend on model, workload and skill loading. Exploration can increase token use. No measured savings are claimed.

## Inspiration
- Caveman: https://github.com/JuliusBrussee/caveman
- ADHD Skill: https://github.com/AIXploits/adhd-skill

The rules are newly written; neither project's code is included.

## License
MIT. See LICENSE.
