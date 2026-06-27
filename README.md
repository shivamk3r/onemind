# OneMind: All Humans In One Team

A privacy-preserving mediator framework for cooperative human coordination.

## Abstract

OneMind is a research proposal for an opt-in, bounded mediator that helps groups coordinate as if they shared a larger common context while preserving individual privacy and consent. The central idea is that many human conflicts, missed opportunities, and inefficient games are not caused by the absence of good outcomes, but by fragmented information, mistrust, private constraints, and fear of exposure.

OneMind studies whether a mediator with scoped access to participant-approved context can recommend, negotiate, or initiate actions that improve collective outcomes without revealing private facts. The mediator may use sensitive information as an internal constraint, but its public explanations must rely only on evidence visible to the relevant participants.

## Motivation

Human coordination often fails even when mutually beneficial outcomes exist. People make decisions with partial information, hidden preferences, incomplete trust, and asymmetric visibility. In game-theoretic terms, participants may settle into inefficient equilibria, fail to discover compatible partners, defect from cooperation because they cannot verify intent, or avoid negotiation because the cost of revealing private context is too high.

OneMind asks whether a privacy-preserving mediator can reduce these failures by giving groups a bounded shared mind: not a central authority, but a consent-based coordination layer that can see enough context to suggest better moves while remaining constrained by visibility, consent, and evidence.

## Core Thesis

OneMind does not claim to magically solve every game theory problem or guarantee a universal optimum in every setting. Instead, it frames a narrower and more defensible research question:

Can an opt-in mediator transform certain adversarial, search, bargaining, and coordination games into better cooperative or mediated games under explicit assumptions about consent, evidence, privacy, and participant reachability?

The thesis is that many real-world games become easier when a trusted mediator can:

- identify mutually beneficial outcomes hidden by fragmented information,
- preserve private constraints without exposing them,
- select better equilibria in coordination games,
- reduce search and matching costs,
- help participants distinguish evidence, inference, preference, and uncertainty,
- recommend no action when privacy, consent, or safety constraints make action inappropriate.

## Model Sketch

The initial model contains:

- **Agents:** human participants with preferences, goals, constraints, and private context.
- **Private facts:** participant-approved facts that may guide the mediator but may not be revealed without consent.
- **Public evidence:** messages, commitments, observations, and shared facts visible to the relevant audience.
- **Visibility boundaries:** rules determining which participants can see which evidence, explanation, or recommendation.
- **Consent:** explicit or contextual permission for the mediator to observe, remember, reason, contact, or introduce.
- **Mediator:** the OneMind process that receives scoped context, reasons over public evidence and hidden constraints, and proposes actions.
- **Proposed action:** a recommendation, introduction, mediation step, negotiation option, question, or deliberate no-action decision.

A valid OneMind output should satisfy three requirements:

- It must stay inside the active scope of consent.
- It must not reveal private facts or hidden rationale to unauthorized participants.
- Any factual claim should be grounded in evidence visible to the recipient, or clearly marked as uncertainty or inference.

## Research Claims

The paper will investigate claims such as:

- **Coordination games:** OneMind can improve equilibrium selection when participants accept a shared mediator and the mediator can identify visible shared goals.
- **Search and matching games:** OneMind can reduce discovery costs by matching compatible needs, offers, skills, and constraints across a bounded participant set.
- **Mediation games:** OneMind can use private constraints to avoid harmful proposals, ask better clarifying questions, and produce more neutral summaries without exposing sensitive context.
- **Repeated games:** OneMind can support cooperation by preserving memory, commitments, and evidence across interactions.
- **Privacy-preserving matchmaking:** OneMind can rank or filter possible introductions using hidden constraints while revealing only safe, recipient-visible reasons.
- **No-action optimality:** In some cases, the best mediator action is to decline, delay, ask for consent, or state uncertainty rather than force a recommendation.

These are theorem candidates and empirical hypotheses, not established results.

## Limits

OneMind must explicitly acknowledge its limits.

It cannot guarantee a global optimum for every game. It cannot force truthful revelation, override incompatible preferences, eliminate adversarial behavior, or resolve social choice conflicts where welfare functions are fundamentally contested. It should not claim authority over high-stakes legal, medical, financial, employment, housing, credit, or safety-critical decisions without strong governance and domain-specific safeguards.

The research therefore treats OneMind as a bounded mechanism for improving certain classes of human coordination problems, not as a universal optimizer for society.

## Paper Roadmap

The first paper should develop:

- a formal model of agents, private facts, visible evidence, consent, and mediator actions,
- a mechanism design framing for opt-in mediated coordination,
- privacy and visibility rules for hidden-constraint reasoning,
- theorem candidates for coordination games, matching games, mediation games, and repeated games,
- small simulations or worked examples showing when OneMind improves outcomes and when it must refuse action,
- a social interpretation of OneMind as local cooperative intelligence rather than centralized control.

## Status

This repository is an early research draft for the OneMind paper. The current goal is to turn the idea into a rigorous mathematical and social document that preserves the ambition of "all humans in one team" while making claims that can be examined, challenged, and improved.
