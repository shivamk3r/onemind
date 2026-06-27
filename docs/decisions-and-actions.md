# OneMind Public Roadmap And Maintainer Checklist

Last updated: 2026-06-27

## Purpose

This checklist tracks the decisions and actions needed to turn OneMind from an
early open research idea into a rigorous public paper and small set of testable
examples. It is written for maintainers and contributors so the project can be
reviewed without private context.

This file complements [research-paper-plan.md](research-paper-plan.md). The
research paper plan is the schedule; this checklist is the set of choices and
review gates that keep the public work precise, safe, and useful.

## Current Public Priorities

- [ ] Keep the project framed as idealized research on trusted mediation, not a
      product pitch or deployment proposal.
- [ ] Strengthen the solvability boundary between coordination failures that
      trusted mediation can reduce and conflicts that remain structurally hard.
- [ ] Collect critique from readers in game theory, mechanism design,
      multi-agent systems, social choice, AI governance, and social systems.
- [ ] Add worked examples and counterexamples that can be safely discussed in
      public.
- [ ] Build a related-work map with expected citations and adjacent concepts.
- [ ] Keep privacy, consent, governance, misuse, and over-dependence limits
      visible in the main project materials.

## Contribution Decisions

### Paper Positioning

- [ ] Confirm the first paper is a technical research paper about idealized
      omniscient mediated coordination.
- [ ] Choose the one-sentence contribution claim the paper should defend.
- [ ] Choose the primary framing: solvability boundary, mechanism design model,
      multi-agent coordination model, or governance-aware theory paper.
- [ ] Decide which phrases remain central, such as "trusted friend,"
      "omniscient mediator," "all humans in one team," or "solvability
      boundary."
- [ ] Identify claims the paper must explicitly avoid, especially any claim that
      a real system should know everything about everyone.

### Target Audience And Venue

- [ ] Choose the main target audience: game theory, mechanism design,
      multi-agent systems, social choice, AI governance, or a hybrid.
- [ ] Choose the intended rigor level for the first version: theorem-heavy
      technical paper, theory-and-examples workshop paper, or position-style
      paper with formal scaffolding.
- [ ] Keep the default primary route as a NeurIPS 2026 workshop if a matching
      accepted workshop call appears.
- [ ] Keep the default fallback route as AAMAS 2027 if the paper becomes strong
      enough in game-theoretic or multi-agent substance.
- [ ] Use CSCW Rolling Design and Theory or a journal-style route only if the
      paper becomes more about social systems, governance, mediation, and
      interaction design.
- [ ] Re-check the exact call for papers, page limits, anonymity rules,
      formatting rules, and submission deadline before any submission.

### Claim Strength

- [ ] Decide which claims should be stated as propositions, conjectures,
      hypotheses, or intuitions.
- [ ] Decide whether the first submission should include proof sketches or
      reserve them for a later version.
- [ ] Decide how much of the paper should emphasize what OneMind cannot solve.
- [ ] Remove or soften claims that cannot be formalized cleanly.
- [ ] State labor-market implications as conditional research hypotheses, not
      deployment forecasts.

### Formal Model

- [ ] Define what counts as an agent in the model.
- [ ] Define what "complete participant state" includes: preferences,
      constraints, beliefs, histories, relationships, capacities, obligations,
      incentives, or other context.
- [ ] Decide whether trust is modeled as full compliance, serious
      consideration, belief in mediator benevolence, or another weaker
      assumption.
- [ ] Decide whether reachability means the mediator can contact everyone at any
      time or only when intervention is allowed by the setting.
- [ ] Decide which mediator actions are in scope: recommendations, clarifying
      questions, introductions, warnings, mediation steps, negotiation options,
      reminders, delays, and no-action decisions.
- [ ] Specify how strongly the model preserves participant agency.

### Welfare Assumptions

- [ ] Choose the welfare objective for the idealized model.
- [ ] Decide whether the paper assumes interpersonal welfare comparisons or
      avoids them where possible.
- [ ] Explain how contested welfare functions are handled.
- [ ] Decide whether the mediator optimizes collective welfare, Pareto
      improvement, harm reduction, equilibrium selection, or another criterion.
- [ ] Define when the correct mediator action is no action, delay, uncertainty,
      or a clarifying question.

### Examples And Counterexamples

- [ ] Pick the main equilibrium-selection example.
- [ ] Pick the main search or matching example.
- [ ] Pick the repeated-cooperation example involving memory, commitments, or
      evidence.
- [ ] Pick the harmful-intervention or no-action example.
- [ ] Decide whether examples should be abstract games, realistic social
      scenarios, or paired versions of both.
- [ ] Ensure any real-world inspiration is safely abstracted before it appears
      in public materials.

### Labor-Market Implications

- [ ] Review the initial "likely to shrink or transform" job-title list:
      schedulers, dispatch coordinators, basic recruiters, routine executive
      assistants, data-entry clerks, customer support triage agents, claims
      processors, travel coordinators, simple brokerage or matching roles, and
      routine project coordinators.
- [ ] Review the initial "likely to stay or become more valuable" job-title
      list: nurses, therapists, teachers, judges or arbitrators, doctors,
      engineers, craftspeople, frontline managers, caregivers, artists or
      designers, community leaders, and negotiators in high-stakes value
      conflicts.
- [ ] Review the initial "likely to emerge" role list: OneMind governance
      auditor, consent and data steward, mediator behavior evaluator,
      welfare-function reviewer, human agency advocate, coordination systems
      designer, transition counselor, AI-mediated relationship coach, and
      trust-and-safety mediator.
- [ ] Decide whether job-title lists belong in the main text, a table, or an
      appendix.
- [ ] Compare the labor-market section against current sources and soften any
      category that feels overstated, missing, or politically sensitive.

### Related Work

- [ ] Decide which literature neighborhoods are central rather than merely
      adjacent.
- [ ] Map mechanism design, information design, social choice, bargaining,
      matching, coordination games, collective intelligence, multi-agent
      systems, and AI governance.
- [ ] Identify 5-8 citations that reviewers are likely to expect.
- [ ] Mark references as direct foundations, adjacent framings, competing
      concepts, or safety and governance constraints.

### Feedback Readers

- [ ] Invite at least one game theory or mechanism design reader.
- [ ] Invite at least one multi-agent systems, AI, or collective-intelligence
      reader.
- [ ] Invite at least one ethics, governance, social systems, or social choice
      reader.
- [ ] Ask each reader for a specific kind of feedback: fatal flaw, missing
      citation, unclear model, overclaim, example gap, or writing clarity.
- [ ] Collect reader comments into buckets so revisions can be prioritized.

### Public-Risk Posture

- [ ] Decide how directly to discuss privacy, consent, governance, misuse, and
      over-dependence.
- [ ] Decide whether governance material belongs in the main text, appendix, or
      both.
- [ ] Prevent the paper from being read as a proposal for real-world omniscient
      surveillance.
- [ ] Ensure safety disclaimers appear in the abstract, introduction, limits
      section, and appendix.
- [ ] Confirm that public examples contain no private, sensitive, or
      non-consensual real-world information.

## Ready Gates

### Ready For First Serious External Review

- [ ] Contribution memo is approved.
- [ ] Model assumptions and terminology are clear.
- [ ] Solvability boundary is explicit.
- [ ] At least four worked examples or counterexamples are drafted.
- [ ] Initial related-work map is drafted.
- [ ] The draft is readable without personal explanation.

### Ready For First External Submission

- [ ] Target venue and exact call for papers are confirmed.
- [ ] Author list, affiliations, conflicts, acknowledgements, and submission
      metadata are confirmed.
- [ ] At least three relevant readers have reviewed the draft, or the risk of
      submitting without them is intentional.
- [ ] Strong claims are proven, marked conjectural, or softened.
- [ ] Privacy, consent, governance, and misuse limits are acknowledged without
      taking over the paper.
- [ ] Final PDF and source files are approved before submission.

### Ready For Public Preprint

- [ ] The paper is technical research rather than mainly a manifesto, survey, or
      position paper.
- [ ] arXiv category fit and any cross-listing are confirmed.
- [ ] Public-risk language is present in the abstract, introduction, limits
      section, and appendix.
- [ ] There is no private, sensitive, or non-consensual real-world example in
      the paper.
- [ ] Public metadata and acknowledgements are final.
