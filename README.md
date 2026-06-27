# OneMind: All Humans In One Team

An omniscient trusted mediator framework for cooperative human coordination.

## Abstract

OneMind is a framework for an omniscient mediator that helps humans coordinate as if a deeply trusted friend knew everyone, understood everyone's situation, and could proactively reach out to say, ask, introduce, warn, negotiate, or recommend. The central idea is that many human conflicts, missed opportunities, and inefficient games are not caused by the absence of good outcomes, but by fragmented information, mistrust, hidden constraints, and failures of timely communication.

OneMind studies what changes when a mediator has complete context about all participants and is trusted by all of them. The paper does not begin as a product design or deployment proposal. Instead, it asks a theoretical question: if an omniscient and benevolent mediator existed, which classes of human coordination problems would become easier, which would remain hard, and what new failure modes would appear?

## Motivation

Human coordination often fails even when mutually beneficial outcomes exist. People make decisions with partial information, hidden preferences, incomplete trust, asymmetric visibility, and limited reachability. In game-theoretic terms, participants may settle into inefficient equilibria, fail to discover compatible partners, defect from cooperation because they cannot verify intent, or avoid negotiation because they do not know what to ask or whom to ask.

OneMind asks whether an omniscient trusted mediator can reduce these failures by giving humanity a shared coordinating mind: not a coercive authority, but a universally trusted agent that knows enough to suggest better moves and has enough social access to contact the right people at the right time.

## Core Thesis

OneMind does not claim to magically solve every game theory problem or guarantee a universal optimum in every setting. Instead, it frames a narrower and more defensible research question:

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

## Limits

OneMind must explicitly acknowledge its limits.

Even with omniscience and trust, it cannot guarantee a global optimum for every game. It cannot erase incompatible preferences, eliminate scarcity, make every welfare comparison objective, or resolve social choice conflicts where values are fundamentally contested. It may also create new problems: over-dependence on the mediator, manipulation of the mediator's objective function, disagreement about what counts as collective welfare, and loss of individual initiative.

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
