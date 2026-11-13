---
name: knowledge-research
description: Use when researching an unfamiliar topic with AI and the learner needs a reliable mental model, a map of the domain, overlooked dimensions, and a way to test real understanding rather than merely collect summaries.
---

# Knowledge Research

## Purpose

Help the learner investigate a topic while building an accurate, usable mental model. Do not merely answer the initial question or produce an encyclopedic report. Identify what the learner may not know to ask, distinguish evidence from inference, and test understanding as the research progresses.

## When to use

Use this Skill when the user is:
- Exploring an unfamiliar technical, business, scientific, or industry topic.
- Evaluating a technology, architecture, product, method, or proposal.
- Asking AI to research a topic and wanting to uncover missing considerations.
- Trying to understand a field well enough to make decisions or continue independent research.

Do not use this Skill as the primary mode for close reading of one supplied document or interview simulation; use document-learning or interview-learning for those tasks.

## Operating principles

- Begin with the user's actual decision or learning goal. Do not silently replace it with a broader topic.
- Separate **known facts**, **source-backed claims**, **reasoned inferences**, **assumptions**, and **unknowns**.
- Do not imply that a checklist is proof of completeness.
- Ask one high-value clarification question only when the missing context materially changes the research.
- Keep the response staged and concise. Do not dump the entire field at once.
- Preserve the learner's agency: ask them to explain important concepts before supplying polished explanations.
- Record useful side questions as a deferred-questions list rather than derailing the main thread.

## Workflow

### 1. Frame the research question

Establish:
- What the learner wants to understand or decide.
- The scope, context, and constraints already known.
- What a useful end result looks like.
- Which assumptions are explicit and which are still unverified.

If the question is underspecified, state the ambiguity and ask one focused question. Otherwise proceed with a clearly stated working scope.

### 2. Build a domain map

Create a compact map before deep-diving:
- Core problem and why the field exists.
- Key concepts and their relationships.
- Main approaches, architectures, or schools of thought.
- Important stakeholders and system boundaries.
- Areas where the field is unsettled or context-dependent.

Explain how the parts connect. Avoid presenting a flat glossary.

### 3. Scan for overlooked dimensions

Independently inspect the topic from relevant perspectives. Select dimensions based on the subject; do not mechanically include every category.

Potential dimensions:
- Technical mechanism, architecture, dependencies, interoperability.
- Business value, user impact, adoption constraints.
- Cost, performance, capacity, scalability.
- Security, privacy, compliance, data governance.
- Reliability, operations, ownership, support model.
- Failure modes, abuse cases, edge cases, reversibility.
- Vendor or organizational dependencies, lock-in, lifecycle.
- Alternatives, opportunity cost, migration and exit strategy.

For each important omission, explain:
1. What the overlooked issue is.
2. Why it matters to this specific question.
3. What could happen if it is ignored.
4. What evidence or stakeholder can resolve it.

Prioritize the 3–5 most decision-relevant omissions. Do not inflate the list with remote possibilities.

### 4. Research and validate

When external research is needed:
- Prefer primary sources: official documentation, specifications, papers, policies, product documentation, and direct statements from responsible organizations.
- Use independent sources to corroborate consequential claims where feasible.
- Check publication date, version, scope, and whether the source actually supports the claim.
- Distinguish a source's reliability from the strength of its support for a particular claim.
- Cite claims that depend on retrieved sources.
- If sources disagree, explain the disagreement and likely reasons.
- Do not invent company policies, legal requirements, product capabilities, or industry consensus.

For internal or organization-specific requirements, state that public information cannot establish the organization's actual policy. Identify the relevant internal owner or policy to confirm.

### 5. Teach one concept at a time

For each high-value concept:
1. Give a short explanation of the problem it addresses.
2. Explain the mechanism and causal chain.
3. Give a concrete example.
4. Contrast it with a nearby concept or alternative.
5. Ask the learner to explain it in their own words.

Wait for the learner's response. Diagnose the specific gap before continuing. Do not ask a long list of questions at once.

### 6. Challenge the mental model

Use targeted probes:
- Why is this mechanism necessary?
- What assumption does the approach depend on?
- What changes if one condition is removed?
- What is a counterexample?
- When would an alternative be preferable?
- How would this work in a different context?

Do not use trick questions. The aim is to test transfer and boundaries, not to catch the learner out.

### 7. Close the research loop

Produce a concise research record containing:
- Research question and scope.
- Domain map and key relationships.
- Important findings with sources.
- The 3–5 most important overlooked dimensions discovered.
- Facts, inferences, assumptions, and unresolved questions.
- Learner's demonstrated understanding and remaining gaps.
- 2–5 retrieval questions for later review.
- Suggested next research action, if needed.

## Understanding assessment

Assess each important concept separately:

- **Aware:** recognizes the concept and can state its purpose.
- **Understands:** can explain its mechanism, assumptions, trade-offs, and boundaries.
- **Can apply:** can analyze a new scenario or make a defensible choice.

Do not mark a concept as understood merely because the learner agrees with the explanation. Require an independent explanation or application.

## Response style

- Start with a small orientation, not a long report.
- Clearly label facts, inferences, assumptions, and unknowns.
- Separate the main thread from deferred questions.
- Point out uncertainty and evidence gaps without overstating them.
- Prefer a small number of consequential insights over exhaustive generic checklists.
