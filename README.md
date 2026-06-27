# OneMind: All Humans In One Team

An omniscient trusted mediator framework for cooperative human coordination.

## Abstract

OneMind is a framework for an omniscient mediator that helps humans coordinate as if a deeply trusted friend knew everyone, understood everyone's situation, and could proactively reach out to say, ask, introduce, warn, negotiate, or recommend. The central idea is that many human conflicts, missed opportunities, and inefficient games are not caused by the absence of good outcomes, but by fragmented information, mistrust, hidden constraints, and failures of timely communication.

OneMind studies what changes when a mediator has complete context about all participants and is trusted by all of them. The paper does not begin as a product design or deployment proposal. Instead, it asks a theoretical question: if an omniscient and benevolent mediator existed, which classes of human coordination problems would become easier, which would remain hard, and what new failure modes would appear?

## Motivation

Human coordination often fails even when mutually beneficial outcomes exist. People make decisions with partial information, hidden preferences, incomplete trust, asymmetric visibility, and limited reachability. In game-theoretic terms, participants may settle into inefficient equilibria, fail to discover compatible partners, defect from cooperation because they cannot verify intent, or avoid negotiation because they do not know what to ask or whom to ask.

OneMind asks whether an omniscient trusted mediator can reduce these failures by giving humanity a shared coordinating mind: not a coercive authority, but a universally trusted agent that knows enough to suggest better moves and has enough social access to contact the right people at the right time.

## Core Thesis

OneMind is a proposal about the solvability boundary of human coordination under complete mediation. It asks which strategic problems collapse when a trusted mediator has complete information, universal reachability, and the ability to communicate with each participant.

Can an omniscient, benevolent, and universally trusted mediator transform certain adversarial, search, bargaining, and coordination games into better cooperative or mediated games under explicit assumptions about complete information, trust, communication, and participant reachability?

The thesis is that many real-world games become easier when a trusted mediator can:

- identify mutually beneficial outcomes hidden by fragmented information,
- understand hidden constraints, preferences, histories, and incentives across all participants,
- select better equilibria in coordination games,
- reduce search and matching costs,
- proactively ask clarifying questions before a coordination failure hardens,
- proactively tell participants what they need to know when timing matters,
- introduce people, negotiate terms, and mediate misunderstandings,
- help participants distinguish evidence, inference, preference, and uncertainty,
- recommend no action when action would make the overall situation worse.

## Solvability Boundary

OneMind should distinguish between games that are solvable by omniscient mediation and games that remain structurally hard even under omniscience.

Problems OneMind can solve or greatly reduce include:

- **Incomplete-information failures:** participants do not know each other's preferences, constraints, plans, beliefs, or available options.
- **Search failures:** compatible people, needs, skills, resources, or opportunities exist but cannot find each other.
- **Coordination failures:** participants prefer the same outcome but fail to select it because they lack common knowledge, timing, or a trusted signal.
- **Mistrust failures:** participants would cooperate if a trusted mediator could verify intent, remember commitments, or explain likely behavior.
- **Communication failures:** participants need to ask, warn, clarify, apologize, negotiate, or disclose something at the right time but do not know how or when.
- **Misaligned local incentives caused by poor context:** participants appear adversarial because each sees only a narrow slice of the whole situation.

Problems OneMind cannot fully solve by information alone include:

- **True preference conflict:** participants knowingly want incompatible outcomes.
- **Scarcity:** the same indivisible resource cannot satisfy everyone who wants it.
- **Distributional conflict:** a surplus exists, but participants disagree on how benefits, costs, risk, or credit should be divided.
- **Commitment without enforcement:** participants may understand the cooperative outcome but still have incentives to defect later.
- **Zero-sum or negative-sum games:** one participant's gain necessarily reduces another's welfare, or all available actions impose loss.
- **Contested welfare functions:** participants disagree about what the mediator should optimize.

The core research question is therefore not whether OneMind solves all games, but how much of human strategic conflict belongs to the first class rather than the second. If many apparent conflicts are actually information, search, trust, and communication failures, an omniscient trusted mediator would transform a large part of social life from adversarial interaction into mediated coordination.

## Model Sketch

The initial model contains:

- **Agents:** human participants with preferences, goals, constraints, and lived context.
- **Complete participant state:** the mediator's assumed knowledge of preferences, constraints, histories, relationships, beliefs, capacities, obligations, and incentives.
- **Evidence and commitments:** messages, promises, observations, agreements, and shared facts that shape what participants believe and can reasonably act on.
- **Reachability:** the mediator's ability to proactively contact participants, ask questions, give information, introduce people, and coordinate timing.
- **Trust assumption:** participants treat the mediator as a trusted friend whose intent is benevolent and whose recommendations deserve serious consideration.
- **Mediator:** the OneMind process that reasons over complete context, anticipates coordination failures, and proposes or initiates interventions.
- **Proposed action:** a recommendation, introduction, mediation step, negotiation option, clarifying question, warning, reminder, or deliberate no-action decision.

A valid OneMind output should satisfy three requirements in the main theoretical model:

- It should improve expected collective outcome under the paper's welfare assumptions.
- It should preserve participant agency by recommending, asking, or mediating rather than coercing.
- It should communicate in a way that each participant can understand and act on.

## Research Claims

The paper will investigate claims such as:

- **Coordination games:** OneMind can improve equilibrium selection when participants accept a shared mediator and the mediator can identify shared goals.
- **Search and matching games:** OneMind can reduce discovery costs by matching compatible needs, offers, skills, and constraints across a large participant set.
- **Mediation games:** OneMind can use complete context to avoid harmful proposals, ask better clarifying questions, and produce more neutral summaries.
- **Repeated games:** OneMind can support cooperation by preserving memory, commitments, and evidence across interactions.
- **Proactive communication:** OneMind can prevent coordination failures by contacting participants before they would naturally discover the need to communicate.
- **Trusted-friend interventions:** OneMind can ask difficult questions, surface overlooked options, and suggest conciliatory actions in ways that would be rejected from an untrusted source.
- **No-action optimality:** In some cases, the best mediator action is to decline, delay, ask a question, or state uncertainty rather than force a recommendation.

These are theorem candidates and empirical hypotheses, not established results.

## Labor Market Implications

OneMind also raises a labor-market research question: if an idealized trusted mediator could reliably perform search, matching, triage, scheduling, routing, remembering, clarifying, and low-stakes negotiation across many people, which jobs would shrink, which would remain, and which new jobs would become necessary? This should be treated as a conditional hypothesis about the OneMind model, not as a near-term deployment forecast or a claim that whole occupations vanish cleanly.

Roles most likely to shrink, merge, or disappear as standalone jobs are roles whose primary value is routine coordination under incomplete information:

- schedulers,
- dispatch coordinators,
- basic recruiters,
- executive assistants focused mainly on routine coordination,
- data-entry clerks,
- customer support triage agents,
- claims processors,
- travel coordinators,
- simple brokerage and matching roles,
- routine project coordinators.

Roles likely to stay or become more valuable are roles grounded in care, embodied practice, professional accountability, judgment under contested values, creative responsibility, or trust that cannot be reduced to information routing:

- nurses,
- therapists,
- teachers,
- judges and arbitrators,
- doctors,
- engineers,
- craftspeople,
- frontline managers,
- caregivers,
- artists and designers,
- community leaders,
- negotiators in high-stakes value conflicts.

New roles may emerge around governing, auditing, interpreting, and contesting mediated coordination:

- OneMind governance auditor,
- consent and data steward,
- mediator behavior evaluator,
- welfare-function reviewer,
- human agency advocate,
- coordination systems designer,
- transition counselor,
- AI-mediated relationship coach,
- trust-and-safety mediator.

The key distinction is not "AI replaces humans" versus "AI helps humans." In the OneMind model, work changes according to how much of a role depends on fragmented information, delayed communication, search costs, memory, triage, and trusted mediation. Roles remain harder to compress when they depend on scarcity, embodied care, legal or moral accountability, contested welfare, physical execution, taste, legitimacy, or deep human relationship. The paper should compare this taxonomy against current labor-market evidence, including the [World Economic Forum Future of Jobs Report 2025](https://www.weforum.org/publications/the-future-of-jobs-report-2025/), the [ILO 2025 generative AI occupational exposure index](https://www.ilo.org/publications/generative-ai-and-jobs-refined-global-index-occupational-exposure), [BLS AI employment-projection case studies](https://www.bls.gov/opub/ted/2025/ai-impacts-in-bls-employment-projections.htm), and the [OECD future of work overview](https://www.oecd.org/en/topics/policy-issues/future-of-work.html).

## Limits

OneMind must explicitly acknowledge its limits.

Even with omniscience and trust, OneMind cannot erase incompatible preferences, eliminate scarcity, make every welfare comparison objective, or resolve social choice conflicts where values are fundamentally contested. It may also create new problems: over-dependence on the mediator, manipulation of the mediator's objective function, disagreement about what counts as collective welfare, and loss of individual initiative.

The research therefore treats OneMind as an idealized mechanism for studying certain classes of human coordination problems, not as a practical claim that a real system should immediately know everything about everyone.

## Paper Roadmap

The first paper should develop:

- a formal model of agents, complete participant state, trust, reachability, and mediator actions,
- a mechanism design framing for omniscient mediated coordination,
- theorem candidates for coordination games, matching games, mediation games, and repeated games,
- small simulations or worked examples showing when OneMind improves outcomes and when it must avoid intervention,
- a social interpretation of OneMind as trusted-friend intelligence rather than centralized control,
- an appendix on privacy, governance, consent, and practical constraints for any real-world approximation of the model.

## Status

This repository is an early research draft for the OneMind paper. The current goal is to turn the idea into a rigorous mathematical and social document that preserves the ambition of "all humans in one team" while making claims that can be examined, challenged, and improved.
