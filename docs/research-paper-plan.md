# OneMind Research Paper Publication Plan

Last updated: 2026-06-27

## Summary

This plan turns the current OneMind research draft into a publishable research paper over a 12-week cycle. The first target is a technical theory-and-examples paper, not a manifesto or product proposal. The paper should define an idealized omniscient trusted mediator, identify which coordination failures become easier under complete mediation, and clearly separate those cases from problems that remain structurally hard.

Primary publication route:

- Prepare a preprint-ready draft.
- Submit to a relevant NeurIPS 2026 workshop if the accepted workshop calls match the paper.
- Use the NeurIPS workshop suggested contribution date of 2026-08-29 as the first external deadline.

Fallback publication route:

- Develop the stronger version for AAMAS 2027.
- Use 2026-10-02 for abstract registration and 2026-10-09 for full paper submission planning.

The paper should be positioned as a research contribution in game theory, mechanism design, multi-agent systems, and mediated coordination. It should not claim that a real deployed system should know everything about everyone. The practical governance, consent, privacy, and safety issues belong in a limits and appendix section.

## Contribution Shape

The first paper should make a crisp technical contribution:

- A formal model of agents, complete participant state, mediator knowledge, reachability, trust, welfare assumptions, mediator actions, and agency-preserving constraints.
- A solvability-boundary analysis that distinguishes information, search, trust, communication, and equilibrium-selection failures from scarcity, incompatible preferences, enforcement gaps, zero-sum conflict, and contested welfare.
- Proposition-level claims or theorem candidates, with proof sketches where possible and conjectural status clearly marked where proof is not yet complete.
- Worked examples showing where OneMind improves coordination and where intervention should be delayed, declined, or treated as unsafe.
- A related-work map that places the paper near mechanism design, information design, social choice, bargaining, coordination games, multi-agent systems, collective intelligence, and AI governance.
- A governance appendix that explains why the paper studies an idealized mediator rather than proposing immediate real-world omniscience.

## 12-Week Milestone Checklist

### Week 1: Scope and Claim Posture

- [ ] Lock working title, author list, audience, target route, and non-goals.
- [ ] Write a one-page contribution memo covering the problem, model, novelty, falsifiable claims, and claims the paper will not make.
- [ ] Decide whether the first submission should emphasize game theory, multi-agent systems, social choice, or AI governance.
- [ ] Completion criterion: the paper can be explained in one paragraph without sounding like a product pitch.

### Week 2: Related-Work Map

- [ ] Build a 30-40 paper bibliography across mechanism design, information design, social choice, coordination games, bargaining, matching, collective intelligence, multi-agent systems, and AI governance.
- [ ] Group sources by role: direct foundations, adjacent framings, competing concepts, and safety/governance constraints.
- [ ] Identify 5-8 papers that reviewers are likely to expect.
- [ ] Completion criterion: every major claim in the introduction has an obvious literature neighborhood.

### Week 3: Formal Model

- [ ] Define agents, preferences, goals, constraints, beliefs, histories, capacities, obligations, and incentives.
- [ ] Define complete participant state and specify what the mediator is assumed to know in the idealized model.
- [ ] Define reachability, trust, mediator action space, welfare objective, and agency-preserving constraints.
- [ ] Separate recommendations, clarifying questions, introductions, warnings, mediation steps, negotiation options, and no-action decisions.
- [ ] Completion criterion: the model is precise enough for a skeptical reader to identify what is assumed, optimized, and constrained.

### Week 4: Solvability Boundary

- [ ] Define classes of failures that omniscient mediation can reduce: incomplete information, search, equilibrium selection, mistrust, and communication timing.
- [ ] Define cases that remain hard: true preference conflict, scarcity, distributional conflict, commitment without enforcement, zero-sum or negative-sum games, and contested welfare.
- [ ] Add at least one example for each class.
- [ ] Completion criterion: the paper does not imply that information alone solves all human conflict.

### Week 5: Worked Examples

- [ ] Write an equilibrium-selection example where a trusted mediator improves coordination.
- [ ] Write a search or matching example where complete context reduces discovery cost.
- [ ] Write a repeated-cooperation example where memory, commitments, and evidence improve outcomes.
- [ ] Write a no-action or harmful-intervention example where the mediator should delay, ask, decline, or state uncertainty.
- [ ] Completion criterion: examples are formal enough to support the model and readable enough to carry the intuition.

### Week 6: Propositions and Proof Sketches

- [ ] Draft proposition-level results or theorem candidates for coordination, matching, mediation, and repeated games.
- [ ] Add proof sketches where the claims are already supportable.
- [ ] Mark unfinished claims as conjectures or empirical hypotheses.
- [ ] Remove or soften claims that cannot be made precise.
- [ ] Completion criterion: technical claims are clearly separated from intuition and speculation.

### Week 7: Draft v0.1

- [ ] Complete a full draft with abstract, introduction, related work, model, solvability boundary, examples, propositions, limits, and appendix outline.
- [ ] Check that the abstract states the idealized nature of the model.
- [ ] Check that the introduction explains why the paper is a research contribution rather than a deployment proposal.
- [ ] Completion criterion: an external reader can review the full argument without needing the repository README.

### Week 8: External Feedback

- [ ] Get feedback from at least one game theory or mechanism design reader.
- [ ] Get feedback from at least one multi-agent systems, AI, or collective-intelligence reader.
- [ ] Get feedback from at least one ethics, governance, social systems, or social choice reader.
- [ ] Track comments in buckets: fatal flaw, missing citation, unclear model, overclaim, example gap, writing issue.
- [ ] Completion criterion: at least three serious readers have reviewed the draft and their main objections are recorded.

### Week 9: Workshop-Ready Draft

- [ ] Revise the paper into a workshop-ready draft.
- [ ] Prepare title, abstract, keywords, PDF, source files, and short submission description.
- [ ] Review accepted NeurIPS 2026 workshop calls and select the best-fit workshop only if the CFP matches the paper.
- [ ] Submit by the relevant workshop deadline if one fits; otherwise preserve the draft for preprint and AAMAS development.
- [ ] Completion criterion: the draft is strong enough to submit without relying on future explanation.

### Week 10: Preprint Readiness

- [ ] Prepare preprint metadata, bibliography, source files, acknowledgements, and reproducibility notes.
- [ ] Decide whether arXiv submission is appropriate.
- [ ] Use arXiv `cs.GT` as the primary category and `cs.MA` as a secondary category only if the paper is clearly technical research.
- [ ] Avoid arXiv CS submission if the draft is mainly a position paper, survey, or speculative essay without completed peer review.
- [ ] Completion criterion: the draft is either ready for preprint release or explicitly held back with a reason.

### Week 11: AAMAS-Style Strengthening

- [ ] Incorporate workshop, preprint, or reader feedback.
- [ ] Tighten definitions, proofs, examples, and related work.
- [ ] Reformat and restructure toward an AAMAS-style main or blue-sky submission if appropriate.
- [ ] Completion criterion: the paper has a credible fallback path beyond the first workshop route.

### Week 12: Submission Decision

- [ ] Decide whether to submit to AAMAS 2027 main track, AAMAS 2027 blue-sky track, CSCW Rolling Design and Theory, or a journal-style venue.
- [ ] If targeting AAMAS 2027, prepare abstract registration by 2026-10-02 and full submission by 2026-10-09.
- [ ] If targeting CSCW or journal-style review, revise the paper to better foreground social systems, governance, and design theory.
- [ ] Completion criterion: the next publication action is chosen, dated, and assigned.

## Venue Plan

### Primary: NeurIPS 2026 Workshop Route

Use this route if an accepted NeurIPS workshop call fits one of these framings:

- AI for coordination, cooperation, or collective intelligence.
- Multi-agent systems and human-AI interaction.
- AI governance, safety, alignment, or mediated decision-making.
- Mechanism design, incentive design, or social choice under AI mediation.

Submission posture:

- Present the paper as an idealized model for studying mediated coordination.
- Keep the strongest claims technical and scoped.
- Include examples and limits to reduce the risk of being read as utopian or product-oriented.

### Fallback: AAMAS 2027

Use this route if the paper develops enough multi-agent systems and game-theoretic substance.

Submission posture:

- Emphasize agent models, mediator action space, strategic settings, formal claims, and examples.
- Consider the blue-sky route if the idea is compelling but not yet theorem-heavy enough for a standard technical submission.

### Longer-Horizon Alternatives

Consider CSCW Rolling Design and Theory if the paper becomes more about social systems, governance, mediation, and interaction design. Consider a journal-style route if the related work and theory become too broad for a workshop or conference paper.

## Reviewer Checklist

Before submission, the draft should answer these reviewer questions:

- What is the exact research question?
- What is the formal object being studied?
- Which assumptions are idealized, and why are they useful?
- What does omniscience mean in the model?
- What does trust mean in the model?
- What does the mediator optimize?
- How does the paper preserve participant agency?
- Which problems become easier under the model?
- Which problems provably or structurally remain hard?
- What is new relative to mechanism design, information design, social choice, bargaining, and multi-agent coordination?
- Are the examples formal enough to test the claims?
- Are privacy, consent, governance, and misuse limits acknowledged without taking over the paper?

## Acceptance Criteria

The plan is complete when:

- [ ] `docs/research-paper-plan.md` exists and renders cleanly as Markdown.
- [ ] Every weekly milestone has a concrete deliverable and completion criterion.
- [ ] The venue plan includes primary, fallback, and longer-horizon routes.
- [ ] The plan clearly distinguishes technical research claims from speculative or governance claims.
- [ ] Source links are listed for venue timing and arXiv category guidance.

The paper is ready for a first external submission when:

- [ ] The paper has a complete draft with abstract, introduction, related work, formal model, solvability boundary, examples, propositions or theorem candidates, limits, and appendix material.
- [ ] At least three relevant readers have reviewed it.
- [ ] The strongest claims are either proven, marked as conjectural, or softened.
- [ ] The target venue's current CFP, formatting rules, and deadline have been re-checked.
- [ ] The draft can stand alone without relying on the README or personal explanation.

## Source Links

- NeurIPS 2026 workshop timing: [NeurIPS Workshops Guidance](https://neurips.cc/Conferences/2026/WorkshopsGuidance)
- AAMAS 2027 timing: [AAMAS 2027 OpenReview](https://openreview.net/group?id=ifaamas.org%2FAAMAS%2F2027%2FConference)
- arXiv category fit: [arXiv category taxonomy](https://arxiv.org/category_taxonomy)
- arXiv CS position and review-paper caution: [arXiv CS moderation update](https://blog.arxiv.org/2025/10/31/attention-authors-updated-practice-for-review-articles-and-position-papers-in-arxiv-cs-category/)
- CSCW fallback route: [CSCW Rolling model](https://cscw.acm.org/2026/rolling.html)
