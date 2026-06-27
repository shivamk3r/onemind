# Agent Operating Guide

This is the canonical operating guide for AI agents working in this repository.
Tool-specific files should point here or adapt this guidance without duplicating
it.

## Repository Purpose

OneMind is an open research project about trusted mediation and human
coordination. It studies an idealized trusted mediator with complete participant
context, reachability, and benevolent intent in order to identify which
coordination failures become easier, which remain structurally hard, and what
privacy, consent, governance, and over-dependence risks appear.

This repository is a research-draft space, not a product launch, deployment
proposal, or endorsement of real-world omniscient surveillance.

## Read First

Before making substantive changes, read these files in order:

1. `README.md` for the project framing, non-goals, public safety rules, and
   repository map.
2. `CONTRIBUTING.md` for contribution expectations, safe example-writing, and
   pull request scope.
3. `SECURITY.md` for sensitive-content boundaries and reporting rules.
4. `docs/research-paper-plan.md` for the current research roadmap when the task
   involves paper planning, venue planning, or milestones.
5. `docs/decisions-and-actions.md` for maintainer checklists and open decisions
   when explicitly working on planning, readiness gates, or project direction.

Do not treat planning or backlog files as live instructions unless the user
explicitly asks to work from them.

## Important Locations

- `README.md`: public project overview and first source of truth for framing.
- `CONTRIBUTING.md`: contribution process and safe example standards.
- `SECURITY.md`: sensitive-content and secret-handling rules.
- `docs/`: research roadmap, maintainer decisions, and paper-planning notes.
- `.agents/skills/`: portable reusable workflows for agents.
- `.agents/commands/`: lightweight saved prompts and slash-command templates.
- `.claude/`, `.cursor/`, `.codex/`: thin compatibility layers for specific
  tools.
- `.codex/environments/`: Codex-only environment setup and cleanup files.

## Privacy And Sensitivity Boundaries

Never add private, personal, sensitive, confidential, identifying, or
non-consensual real-world examples. This includes messages, emails, chats,
calendars, notes, recordings, personal records, health, finance, legal,
workplace, family, relationship, immigration, education, location details,
credentials, tokens, private keys, and API keys.

Use synthetic examples. If a real situation inspired an idea, abstract it until
no person, organization, relationship, place, or private circumstance can be
identified. If sensitive content is found, do not reproduce it in public issues,
examples, commits, or summaries; follow `SECURITY.md`.

## Recency And Source Of Truth

Use repository files as the source of truth for project framing and current
public commitments. When a task depends on external deadlines, venue rules,
paper calls, software behavior, or other time-sensitive facts, verify against
current primary sources before changing repository claims.

For dates, prefer exact dates over relative phrasing. Mark uncertain,
speculative, or conditional claims clearly. Do not present venue submission
targets, labor-market implications, or deployment predictions as promises.

## Coding And Editing Conventions

- Keep changes small, focused, and reviewable.
- Preserve existing useful content and unrelated user changes.
- Prefer plain Markdown for research material.
- Keep line wrapping consistent with nearby files, generally around 80
  characters for prose.
- Use synthetic examples and toy data for simulations.
- Separate technical claims from intuition, speculation, and governance
  commentary.
- Mark unfinished formal claims as conjectures or hypotheses rather than
  results.
- Avoid platform-specific metadata inside portable skills or commands.
- Put product-specific setup only in the relevant adapter folder, such as
  `.codex/environments/`.

## Verification Expectations

Choose verification based on the change:

- For Markdown-only changes, check links, headings, terminology consistency, and
  safety language.
- For agent-file changes, verify symlink targets and run `git diff --check`.
- For scripts or simulations, run the smallest meaningful command or test that
  exercises the change.
- For research claims involving current external facts, cite or record the
  primary source used to verify them.

Before finishing agent-structure changes on a Unix-like system, run:

```sh
for p in CLAUDE.md .claude/skills .claude/commands .cursor/skills .cursor/commands .codex/skills; do printf '%s -> %s\n' "$p" "$(readlink "$p")"; done
git diff --check
git status --short
```

## Agent Assets

Portable agent assets live under `.agents/`.

Skills live at `.agents/skills/<skill-name>/SKILL.md`. A skill is a reusable
workflow with a clear trigger, context-loading instructions, steps, output
contract, and verification expectations. Supporting material for a skill belongs
in `.agents/skills/<skill-name>/references/`; helper scripts belong in
`.agents/skills/<skill-name>/scripts/`.

Commands live at `.agents/commands/<command-name>.md`. Commands are lightweight
prompt templates for repeatable tasks. Use a skill instead when the workflow
needs multiple steps, extra context files, scripts, or verification rules.

## Tool Compatibility Layers

Tool-specific folders should adapt to the shared `.agents/` layer:

- `CLAUDE.md` should be a symlink to `AGENTS.md`.
- `.claude/skills` should be a symlink to `../.agents/skills`.
- `.claude/commands` should be a symlink to `../.agents/commands`.
- `.cursor/skills` should be a symlink to `../.agents/skills`.
- `.cursor/commands` should be a symlink to `../.agents/commands`.
- `.codex/skills` should be a symlink to `../.agents/skills`.

Do not duplicate shared skills or commands inside `.claude/`, `.cursor/`, or
`.codex/`. Do not add `.codex/commands` unless the repository explicitly needs a
Codex-only command mechanism.
