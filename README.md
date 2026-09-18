# Agentic Portfolio Starter

A deliberately small starter package for an agent-assisted portfolio website workshop.

The starter teaches three ideas without prescribing a full development process:

1. Put stable repository-wide behavior in project instructions.
2. Put reusable task-specific guidance in skills.
3. Keep personal taste—especially UI/UX direction—owned by the user rather than hidden inside a universal starter.

No custom agent profiles are included by design.

## Included

- `AGENTS.md` — lean project-wide development, verification, Git, and completion rules.
- `skills/clean-coding/` — implementation standards for readable, modular, self-documenting code.
- `skills/portfolio-website-content/` — content and information-architecture guidance for a professional portfolio.

## Skill installation

The skill contents use the portable `SKILL.md` Agent Skills pattern. Harnesses differ in where project skills are discovered, so copy the two skill directories into the project skill location used by your tool.

### Google Antigravity / Codex

Place them under:

```text
.agents/skills/
├── clean-coding/
│   └── SKILL.md
└── portfolio-website-content/
    └── SKILL.md
```

### Claude Code

Place them under:

```text
.claude/skills/
├── clean-coding/
│   └── SKILL.md
└── portfolio-website-content/
    └── SKILL.md
```

Claude Code uses `CLAUDE.md` for its native always-loaded project instructions. If using Claude Code, carry the directives from `AGENTS.md` into the project's `CLAUDE.md` rather than maintaining two independently edited sources of truth.

### Codex / other Agent Skills-compatible harnesses

Use the project skill location supported by the current harness and retain each skill directory with its `SKILL.md` entrypoint. Keep `AGENTS.md` at the repository root when the harness supports it as repository instructions.

## Create your own UI/UX skill

The starter intentionally does not include one universal UI/UX skill. Visual taste is subjective, and students should make those preferences explicit themselves.

Use the skill creator available in your coding harness and ask it to create a project UI/UX skill. A useful request is:

> Create a project skill for UI/UX work on my portfolio website. First interview me briefly about visual references, density, typography, color, motion, layout, interaction style, accessibility expectations, and aesthetics I dislike. Then create a focused skill that captures my preferences without duplicating general clean-coding or portfolio-content guidance. Include a verification loop that checks the rendered site at representative desktop and mobile sizes.

Review the generated skill before using it. Its trigger should clearly cover visual design and UI implementation tasks, while its body should remain focused on your preferences rather than becoming a general frontend encyclopedia.

## Begin development

Once the project instructions and skills are installed, start coding normally. The purpose of the starter is not to prescribe every step; it is to give the coding agent a small amount of durable context that remains useful as the project evolves.
