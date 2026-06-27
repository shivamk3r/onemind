# OneMind: All Humans In One Team

OneMind is an open research project about trusted mediation and human
coordination.

The core question is:

> If a trusted mediator had complete context and could communicate with all
> participants, which human coordination failures would become easier, which
> would remain structurally hard, and what new risks would appear?

This repository is not a product launch or a proposal for real-world
omniscient surveillance. It is an early research space for making the idea
precise enough to critique, formalize, simulate, and improve.

## Project Status

OneMind is at the research-draft stage. The current work is to turn the idea
into a rigorous paper and a small set of testable examples. Contributions are
most useful when they challenge the model, sharpen definitions, add failure
cases, connect the work to existing literature, or build tiny simulations of
mediated coordination scenarios.

The first public posture is research critique first, prototype second.

## Research Framing

Human coordination often fails even when mutually beneficial outcomes exist.
People make decisions with partial information, hidden preferences, incomplete
trust, asymmetric visibility, and limited reachability. In game-theoretic
terms, participants may settle into inefficient equilibria, fail to discover
compatible partners, defect from cooperation because they cannot verify intent,
or avoid negotiation because they do not know what to ask or whom to ask.

OneMind studies an idealized mediator with complete participant context,
trusted intent, and the ability to communicate with each participant. The goal
is to identify the solvability boundary of such mediation:

- Which failures are caused mainly by fragmented information, search costs,
  mistrust, missing common knowledge, or poor timing?
- Which failures remain hard because of scarcity, incompatible preferences,
  distributional conflict, weak commitment, zero-sum structure, or contested
  welfare?
- How should an ideal mediator decide between recommending, asking,
  introducing, warning, negotiating, delaying, or taking no action?
- What privacy, consent, governance, and over-dependence risks arise when the
  model is approximated in real systems?

## What This Is

- An open research project on trusted mediation and human coordination.
- A draft theory space near game theory, mechanism design, information design,
  social choice, matching, bargaining, multi-agent systems, collective
  intelligence, and AI governance.
- A place to collect precise examples, counterexamples, toy models, related
  work, and safety constraints.
- A paper-in-progress about an idealized mechanism, not an immediate deployment
  plan.

## What This Is Not

- Not a proposal that any real system should know everything about everyone.
- Not a call to collect private, personal, non-consensual, or sensitive
  coordination data.
- Not a claim that information alone solves all human conflict.
- Not a claim that every job, relationship, institution, or social process can
  be reduced to automated mediation.
- Not a product roadmap for a surveillance system, central authority, or
  coercive decision-maker.

## Core Model Sketch

The initial model contains:

- **Agents:** human participants with preferences, goals, constraints, and
  lived context.
- **Complete participant state:** the mediator's assumed knowledge of
  preferences, constraints, histories, relationships, beliefs, capacities,
  obligations, and incentives.
- **Evidence and commitments:** messages, promises, observations, agreements,
  and shared facts that shape what participants believe and can reasonably act
  on.
- **Reachability:** the mediator's ability to proactively contact participants,
  ask questions, give information, introduce people, and coordinate timing.
- **Trust assumption:** participants treat the mediator as a trusted friend
  whose intent is benevolent and whose recommendations deserve serious
  consideration.
- **Mediator action space:** recommendations, clarifying questions,
  introductions, warnings, mediation steps, negotiation options, reminders,
  delays, and deliberate no-action decisions.

A valid OneMind output should improve expected collective outcome under the
paper's welfare assumptions, preserve participant agency, and communicate in a
way each participant can understand and act on.

## Solvability Boundary

Problems OneMind may reduce under idealized assumptions:

- incomplete-information failures,
- search and matching failures,
- equilibrium-selection failures,
- mistrust and missing verification,
- communication timing failures,
- misaligned local incentives caused by poor context.

Problems OneMind cannot fully solve by information alone:

- true preference conflict,
- scarcity,
- distributional conflict,
- commitment without enforcement,
- zero-sum or negative-sum games,
- contested welfare functions.

This boundary is the center of the research. If the project is useful, it will
make both sides sharper: what trusted mediation can transform, and what it must
not pretend to solve.

## Contribution Tracks

Useful early contributions include:

- **Research critiques:** identify overclaims, unclear assumptions, missing
  definitions, or places where the framing could be misunderstood.
- **Counterexamples:** add cases where trusted mediation fails, makes the
  situation worse, or should choose no action.
- **Worked examples:** formalize small coordination, search, matching,
  repeated-game, or mediation scenarios.
- **Related work:** point to papers, books, talks, or concepts from game
  theory, mechanism design, information design, social choice, bargaining,
  collective intelligence, multi-agent systems, and AI governance.
- **Toy simulations:** build minimal implementations that test specific
  coordination scenarios without using private or sensitive real-world data.
- **Safety and governance:** sharpen the consent, privacy, accountability,
  misuse, and over-dependence limits.

Start with [CONTRIBUTING.md](CONTRIBUTING.md), then open one of the issue
templates that best matches your contribution.

## Repository Structure

```text
.
|-- AGENTS.md
|-- CLAUDE.md -> AGENTS.md
|-- README.md
|-- CONTRIBUTING.md
|-- CODE_OF_CONDUCT.md
|-- SECURITY.md
|-- LICENSE
|-- LICENSE-DOCS.md
|-- .agents/
|   |-- skills/
|   `-- commands/
|-- .claude/
|   |-- skills -> ../.agents/skills
|   `-- commands -> ../.agents/commands
|-- .cursor/
|   |-- skills -> ../.agents/skills
|   `-- commands -> ../.agents/commands
|-- .codex/
|   |-- skills -> ../.agents/skills
|   `-- environments/
|-- docs/
|   |-- decisions-and-actions.md
|   `-- research-paper-plan.md
`-- .github/
    |-- ISSUE_TEMPLATE/
    `-- PULL_REQUEST_TEMPLATE.md
```

## Agent Context

AI agents should start with [AGENTS.md](AGENTS.md), the canonical operating
guide for this repository. Portable reusable workflows live in
[.agents/skills](.agents/skills), and lightweight saved prompts live in
[.agents/commands](.agents/commands).

The `.claude`, `.cursor`, and `.codex` directories are compatibility layers.
They point back to the shared `.agents` assets with symlinks so agent behavior
has one source of truth. Codex-only setup belongs under `.codex/environments/`;
portable skills and commands should not be duplicated in tool-specific folders.

## Public Safety Rules

Do not submit private, personal, sensitive, confidential, or non-consensual
examples. If a real situation inspired an idea, abstract it until no person,
organization, relationship, location, or private circumstance can be identified.

Use synthetic examples for simulations. If a contribution depends on real-world
data, open an issue describing the research need without sharing the data.

See [SECURITY.md](SECURITY.md) for safety reporting and sensitive-content
guidelines.

## License

Software and code in this repository are licensed under the
[MIT License](LICENSE).

Research text, documentation, examples, diagrams, paper material, and other
non-code content are licensed under the
[Creative Commons Attribution 4.0 International License](LICENSE-DOCS.md),
unless a file says otherwise.

## Contact

For contribution discussion, use GitHub issues when possible.

For direct contact or conduct reports, email `shivam@shivamk3r.com`.
