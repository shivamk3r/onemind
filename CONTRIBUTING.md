# Contributing To OneMind

Thank you for considering a contribution. OneMind is an early open research
project, so the most valuable contributions are precise critiques, careful
examples, missing literature, and small simulations that test one claim at a
time.

## Before You Contribute

Please read:

- [README.md](README.md) for the project framing and safety boundaries.
- [SECURITY.md](SECURITY.md) for sensitive-content rules.
- [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) for community expectations.
- [docs/research-paper-plan.md](docs/research-paper-plan.md) for the current
  research roadmap.

## Good Early Contributions

- **Research critique:** point out unclear assumptions, overclaims, missing
  definitions, unsupported jumps, or ways the framing could be misread.
- **Counterexamples:** describe cases where a trusted mediator cannot help,
  should delay, should ask a question, or could make things worse.
- **Worked examples:** formalize small coordination, matching, bargaining,
  search, repeated-game, or mediation scenarios.
- **Related work:** suggest papers, books, talks, or concepts that should be in
  the bibliography.
- **Toy simulations:** add minimal code or pseudocode that tests a narrow
  mediated-coordination scenario using synthetic data.
- **Safety and governance:** improve privacy, consent, accountability,
  contested-welfare, misuse, and over-dependence analysis.

## What Not To Submit

- Private, personal, sensitive, confidential, or non-consensual real-world
  examples.
- Identifying details about real people, relationships, organizations, or
  disputes.
- Claims that a real system should know everything about everyone.
- Broad implementation proposals that skip the research assumptions and safety
  constraints.
- Large rewrites that combine many unrelated arguments in one pull request.

## Safe Example-Writing

Use abstract or synthetic scenarios. If a real situation inspired an example,
remove or change enough detail that no person, group, place, organization,
relationship, or private circumstance can be inferred.

Good examples state:

- the agents,
- their preferences or constraints,
- what each agent knows,
- what the mediator knows in the idealized model,
- the mediator's allowed actions,
- the welfare or success criterion,
- why the mediator should act, ask, delay, or do nothing.

## Issue Workflow

Open one of the issue templates:

- Research critique
- Example or counterexample
- Related work

Use GitHub issues for public discussion whenever possible. For private conduct
or safety concerns, email `shivam@shivamk3r.com`.

## Pull Request Workflow

Keep pull requests small and focused. A good pull request usually changes one
of these at a time:

- one claim,
- one example,
- one counterexample,
- one section of related work,
- one safety or governance point,
- one tiny simulation.

In your pull request, describe what changed, why it matters, and any remaining
uncertainty. Mark speculative claims as speculative.

## Authorship And Acknowledgements

OneMind is open to adding substantial intellectual contributors to the paper
author list. People who make substantial intellectual contributions, such as
formal model development, major examples, proofs, simulations, related-work
synthesis, or safety and governance analysis, may be added to the author list if
they also participate in drafting or revising the paper and accept
responsibility for their contribution.

Smaller but useful contributions, including critiques, citation suggestions,
minor examples, issue discussion, and wording improvements, should be credited
in acknowledgements or public project history when appropriate. Authorship,
contribution roles, acknowledgements, affiliations, and conflicts should be
confirmed before any external submission or public preprint.

## Licensing

By contributing, you agree that code contributions are licensed under the MIT
License and documentation/research-text contributions are licensed under CC BY
4.0, unless a file clearly says otherwise.
