# OneMind Public Research Paper Plan

Last updated: 2026-06-27

## Summary

This plan turns OneMind from an early public research draft into a paper-quality
research contribution over a 12-week cycle. The goal is to investigate the model
carefully, report what holds and what fails, and make the result useful for
people or institutions making decisions about mediated coordination and AI
systems. The first research output should be a technical theory-and-examples
paper, not a manifesto or product proposal. The paper should define an idealized
omniscient trusted mediator, identify which coordination failures become easier
under complete mediation, and clearly separate those cases from problems that
remain structurally hard.

Possible dissemination routes:

- Prepare a preprint-ready draft if the work becomes strong enough to release.
- Consider a relevant NeurIPS 2026 workshop if the accepted workshop calls match
  the paper and the draft is ready.
- Use the NeurIPS workshop suggested contribution date of 2026-08-29 as a
  planning anchor until a specific call for papers is checked.
- Develop a stronger version for AAMAS 2027 if the work gains enough
  game-theoretic or multi-agent substance.
- Use 2026-10-02 for abstract registration and 2026-10-09 for full paper
  submission planning only as conditional anchors, subject to checking the live
  venue instructions.

The project may pursue workshops, conferences, journals, or preprint release for
visibility and credibility, but no venue acceptance is promised or treated as the
core goal.

The paper should be positioned as a research contribution in game theory,
mechanism design, multi-agent systems, and mediated coordination. It should not
claim that a real deployed system should know everything about everyone. The
practical governance, consent, privacy, and safety issues belong in the limits
section and appendix.

## Contribution Shape

The first paper should make a crisp technical contribution:

- A formal model of agents, complete participant state, mediator knowledge,
  reachability, trust, welfare assumptions, mediator actions, and
  agency-preserving constraints.
- A solvability-boundary analysis that distinguishes information, search,
  trust, communication, and equilibrium-selection failures from scarcity,
  incompatible preferences, enforcement gaps, zero-sum conflict, and contested
  welfare.
- Proposition-level claims or theorem candidates, with proof sketches where
  possible and conjectural status clearly marked where proof is not complete.
- Worked examples showing where OneMind improves coordination and where
  intervention should be delayed, declined, or treated as unsafe.
- A labor-market implications section that analyzes which roles could shrink,
  persist, transform, or emerge under the idealized OneMind model, while
  avoiding unsupported deployment forecasts.
- A related-work map that places the paper near mechanism design, information
  design, social choice, bargaining, coordination games, multi-agent systems,
  collective intelligence, and AI governance.
- A governance appendix that explains why the paper studies an idealized
  mediator rather than proposing immediate real-world omniscience.

## 12-Week Milestone Checklist

### Week 1: Scope And Claim Posture

- [ ] Lock working title, author and contributor roles, audience, possible
      dissemination route, and non-goals.
- [ ] Write a one-page contribution memo covering the problem, model, novelty,
      falsifiable claims, and claims the paper will not make.
- [ ] Decide whether the first external version should emphasize game theory,
      multi-agent systems, social choice, or AI governance.
- [ ] Completion criterion: the research question, non-goals, and usefulness can
      be explained in one paragraph without sounding like a product pitch.

### Week 2: Related-Work Map

- [ ] Build a 30-40 paper bibliography across mechanism design, information
      design, social choice, coordination games, bargaining, matching,
      collective intelligence, multi-agent systems, and AI governance.
- [ ] Group sources by role: direct foundations, adjacent framings, competing
      concepts, and safety or governance constraints.
- [ ] Identify 5-8 papers that reviewers are likely to expect.
- [ ] Completion criterion: every major claim in the introduction has an
      obvious literature neighborhood.

### Week 3: Formal Model

- [ ] Define agents, preferences, goals, constraints, beliefs, histories,
      capacities, obligations, and incentives.
- [ ] Define complete participant state and specify what the mediator is
      assumed to know in the idealized model.
- [ ] Define reachability, trust, mediator action space, welfare objective, and
      agency-preserving constraints.
- [ ] Separate recommendations, clarifying questions, introductions, warnings,
      mediation steps, negotiation options, reminders, delays, and no-action
      decisions.
- [ ] Completion criterion: the model is precise enough for a skeptical reader
      to identify what is assumed, optimized, and constrained.

### Week 4: Solvability Boundary

- [ ] Define classes of failures that omniscient mediation can reduce:
      incomplete information, search, equilibrium selection, mistrust, and
      communication timing.
- [ ] Define cases that remain hard: true preference conflict, scarcity,
      distributional conflict, commitment without enforcement, zero-sum or
      negative-sum games, and contested welfare.
- [ ] Add at least one example for each class.
- [ ] Draft the labor-market implication boundary: roles likely to transform
      when they mainly perform routine coordination, and roles likely to persist
      when they depend on embodied care, accountability, contested values,
      creative judgment, legitimacy, or physical execution.
- [ ] Completion criterion: the paper does not imply that information alone
      solves all human conflict.

### Week 5: Worked Examples

- [ ] Write an equilibrium-selection example where a trusted mediator improves
      coordination.
- [ ] Write a search or matching example where complete context reduces
      discovery cost.
- [ ] Write a repeated-cooperation example where memory, commitments, and
      evidence improve outcomes.
- [ ] Write a no-action or harmful-intervention example where the mediator
      should delay, ask, decline, or state uncertainty.
- [ ] Completion criterion: examples are formal enough to support the model and
      readable enough to carry the intuition.

### Week 6: Propositions And Proof Sketches

- [ ] Draft proposition-level results or theorem candidates for coordination,
      matching, mediation, and repeated games.
- [ ] Add proof sketches where the claims are already supportable.
- [ ] Mark unfinished claims as conjectures or empirical hypotheses.
- [ ] Remove or soften claims that cannot be made precise.
- [ ] Completion criterion: technical claims are clearly separated from
      intuition and speculation.

### Week 7: Draft v0.1

- [ ] Complete a full draft with abstract, introduction, related work, model,
      solvability boundary, labor-market implications, examples, propositions,
      limits, and appendix outline.
- [ ] Check that the abstract states the idealized nature of the model.
- [ ] Check that the introduction explains why the paper is a research
      contribution rather than a deployment proposal.
- [ ] Completion criterion: an external reader, including a researcher,
      policymaker, or AI lab reviewer, can review the full argument without
      needing repository context.

### Week 8: External Feedback

- [ ] Get feedback from at least one game theory or mechanism design reader.
- [ ] Get feedback from at least one multi-agent systems, AI, or
      collective-intelligence reader.
- [ ] Get feedback from at least one ethics, governance, social systems, or
      social choice reader.
- [ ] Track comments in buckets: fatal flaw, missing citation, unclear model,
      overclaim, example gap, writing issue.
- [ ] Completion criterion: at least three serious readers have reviewed the
      draft and their main objections are recorded.

### Week 9: External-Ready Draft

- [ ] Revise the paper into a draft that is strong enough for outside review,
      preprint consideration, or a workshop if one fits.
- [ ] Prepare title, abstract, keywords, PDF, source files, and short submission
      description.
- [ ] Review accepted NeurIPS 2026 workshop calls and select the best-fit
      workshop only if the call for papers matches the paper.
- [ ] If one fits and the draft is strong enough, decide whether to submit by the
      relevant workshop deadline; otherwise preserve the draft for preprint,
      AAMAS-style development, or further research.
- [ ] Completion criterion: the draft is strong enough to circulate without
      relying on future explanation.

### Week 10: Preprint Readiness

- [ ] Prepare preprint metadata, bibliography, source files, acknowledgements,
      and reproducibility notes.
- [ ] Decide whether arXiv submission is appropriate.
- [ ] Use arXiv `cs.GT` as the primary category and `cs.MA` as a secondary
      category only if the paper is clearly technical research.
- [ ] Avoid arXiv CS submission if the draft is mainly a position paper, survey,
      or speculative essay without completed peer review.
- [ ] Completion criterion: the draft is either ready for preprint release or
      explicitly held back with a reason.

### Week 11: AAMAS-Style Strengthening

- [ ] Incorporate workshop, preprint, or reader feedback.
- [ ] Tighten definitions, proofs, examples, and related work.
- [ ] Reformat and restructure toward an AAMAS-style main or blue-sky submission
      if appropriate.
- [ ] Completion criterion: the paper has a credible development path beyond the
      first workshop opportunity.

### Week 12: Submission Decision

- [ ] Decide whether to submit to AAMAS 2027 main track, AAMAS 2027 blue-sky
      track, CSCW Rolling Design and Theory, or a journal-style venue.
- [ ] If targeting AAMAS 2027, prepare abstract registration by 2026-10-02 and
      full paper submission by 2026-10-09.
- [ ] If targeting CSCW or journal-style review, revise the paper to better
      foreground social systems, governance, and design theory.
- [ ] Completion criterion: the next dissemination or research-development
      action is chosen, dated, and assigned.

## Dissemination Plan

Venue planning is useful for deadlines, formatting, and credibility, but it is a
dissemination aid rather than a promise. Use venue names and dates as planning
anchors only when the research quality and call fit justify them.

### Possible: NeurIPS 2026 Workshop Route

Use this route if an accepted NeurIPS workshop call fits one of these framings:

- AI for coordination, cooperation, or collective intelligence.
- Multi-agent systems and human-AI interaction.
- AI governance, safety, alignment, or mediated decision-making.
- Mechanism design, incentive design, or social choice under AI mediation.

Submission posture:

- Present the paper as an idealized model for studying mediated coordination.
- Keep the strongest claims technical and scoped.
- Include examples and limits to reduce the risk of being read as utopian or
  product-oriented.

### Possible: AAMAS 2027

Use this route if the paper develops enough multi-agent systems and
game-theoretic substance.

Submission posture:

- Emphasize agent models, mediator action space, strategic settings, formal
  claims, and examples.
- Consider the blue-sky route if the idea is compelling but not theorem-heavy
  enough for a standard technical submission.

### Longer-Horizon Alternatives

Consider CSCW Rolling Design and Theory if the paper becomes more about social
systems, governance, mediation, and interaction design. Consider a journal-style
route if the related work and theory become too broad for a workshop or
conference paper.

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
- What is new relative to mechanism design, information design, social choice,
  bargaining, and multi-agent coordination?
- Which roles plausibly shrink, persist, transform, or emerge under the model,
  and are those claims stated as conditional research hypotheses?
- Are the examples formal enough to test the claims?
- Are privacy, consent, governance, and misuse limits acknowledged without
  taking over the paper?

## Acceptance Criteria

The plan is complete when:

- [ ] `docs/research-paper-plan.md` exists and renders cleanly as Markdown.
- [ ] Every weekly milestone has a concrete deliverable and completion
      criterion.
- [ ] The dissemination plan includes optional workshop, conference, preprint,
      journal, and longer-horizon routes without promising acceptance.
- [ ] The plan clearly distinguishes technical research claims from speculative
      or governance claims.
- [ ] Source links are listed for venue timing and arXiv category guidance.

The paper is ready for a first external submission when:

- [ ] The paper has a complete draft with abstract, introduction, related work,
      formal model, solvability boundary, labor-market implications, examples,
      propositions or theorem candidates, limits, and appendix material.
- [ ] At least three relevant readers have reviewed it.
- [ ] The strongest claims are either proven, marked as conjectural, or
      softened.
- [ ] The target venue's current call for papers, formatting rules, and deadline
      have been re-checked.
- [ ] The draft can stand alone without relying on the README or personal
      explanation.

## Source Links

- NeurIPS 2026 workshop timing: [NeurIPS Workshops Guidance](https://neurips.cc/Conferences/2026/WorkshopsGuidance)
- AAMAS 2027 timing: [AAMAS 2027 OpenReview](https://openreview.net/group?id=ifaamas.org%2FAAMAS%2F2027%2FConference)
- arXiv category fit: [arXiv category taxonomy](https://arxiv.org/category_taxonomy)
- arXiv CS position and review-paper caution: [arXiv CS moderation update](https://blog.arxiv.org/2025/10/31/attention-authors-updated-practice-for-review-articles-and-position-papers-in-arxiv-cs-category/)
- CSCW fallback route: [CSCW Rolling model](https://cscw.acm.org/2026/rolling.html)
- Labor-market baseline: [World Economic Forum Future of Jobs Report 2025](https://www.weforum.org/publications/the-future-of-jobs-report-2025/)
- Occupational exposure baseline: [ILO generative AI occupational exposure index](https://www.ilo.org/publications/generative-ai-and-jobs-refined-global-index-occupational-exposure)
- U.S. employment projection baseline: [BLS AI impacts in employment projections](https://www.bls.gov/opub/ted/2025/ai-impacts-in-bls-employment-projections.htm)
- Future-of-work policy baseline: [OECD future of work overview](https://www.oecd.org/en/topics/policy-issues/future-of-work.html)
