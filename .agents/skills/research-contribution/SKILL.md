---
name: research-contribution
description: Safely draft, critique, or revise OneMind research contributions.
---

# Research Contribution Skill

## When To Use

Use this skill when drafting, reviewing, or revising OneMind research material,
including critiques, counterexamples, worked examples, related-work notes,
formal-model changes, safety/governance analysis, or small simulation proposals.

## Context To Load

Read these files before acting:

1. `AGENTS.md`
2. `README.md`
3. `CONTRIBUTING.md`
4. `SECURITY.md`

Also read:

- `docs/research-paper-plan.md` when the task touches roadmap, venue planning,
  paper structure, milestones, or dissemination.
- `docs/decisions-and-actions.md` when the task touches maintainer decisions,
  readiness gates, authorship, claim strength, or project priorities.
- The specific files the user asks to edit or review.

## Workflow

1. Identify the contribution type: critique, counterexample, worked example,
   related work, formal model, safety/governance, or toy simulation.
2. Check that the proposed contribution preserves the research posture: idealized
   trusted mediation, critique first, prototype second, no deployment pitch.
3. Screen for sensitive or identifying real-world content. Replace it with
   synthetic or abstracted material before it enters public text.
4. Make claims precise. Separate assumptions, definitions, propositions,
   conjectures, intuitions, and open questions.
5. Locate the change in the smallest appropriate file or section.
6. Preserve the solvability boundary between failures that trusted mediation may
   reduce and conflicts that remain structurally hard.
7. Keep edits focused and avoid combining unrelated research arguments.
8. Add verification notes or citations when claims depend on external,
   time-sensitive, or source-specific facts.

## Output Contract

Return or commit changes that include:

- a concise summary of the research contribution,
- any files changed,
- safety/privacy assumptions made,
- unresolved uncertainties or claims that remain speculative,
- verification performed.

When drafting examples, include the agents, preferences or constraints,
information available to participants, mediator knowledge, allowed mediator
actions, welfare or success criterion, and why the mediator should act, ask,
delay, or do nothing.

## Verification Requirements

- Confirm no private, sensitive, identifying, confidential, or non-consensual
  material was introduced.
- Check that research claims do not imply a real system should know everything
  about everyone.
- For Markdown edits, review headings, links, terminology, and line wrapping.
- For code or simulations, run the smallest meaningful test or command.
- Run `git diff --check` before finishing when files were edited.
