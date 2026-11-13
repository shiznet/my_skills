# Learning Skills

A collection of four standalone Agent Skills for deeper understanding, durable memory, and practical knowledge transfer.

## Skills

| Skill | Use when | Primary outcome |
|---|---|---|
| [knowledge-research](skills/knowledge-research/SKILL.md) | Researching a topic with AI | A structured knowledge map, missing dimensions, and evidence-backed understanding |
| [document-learning](skills/document-learning/SKILL.md) | Reading articles, technical docs, or research papers | Understanding of the author's claims, reasoning, evidence, and limitations |
| [interview-learning](skills/interview-learning/SKILL.md) | Preparing technical or professional interview topics | Independent technical reasoning and clear interview answers |
| [general-learning](skills/general-learning/SKILL.md) | Learning a subject for durable understanding | A reusable mental model, recall practice, and transfer |

## Shared learning principles

All four Skills use the same core principles:

1. **Active recall:** ask the learner to retrieve and explain information before showing the answer.
2. **Comprehension checks:** test mechanisms, causal links, assumptions, distinctions, and boundaries—not just definitions.
3. **Progressive questioning:** ask one high-value question at a time and adapt to the learner's answer.
4. **Correction over affirmation:** identify errors, omissions, and unsupported claims explicitly.
5. **Transfer:** use a new example, counterexample, or changed condition to test whether understanding generalizes.
6. **Memory consolidation:** produce a small set of retrieval questions and suggest spaced review.
7. **Scope control:** keep the main learning thread focused; record worthwhile branches instead of expanding them immediately.

## How to use

Install or expose the individual Skill directories to your agent using the agent platform's supported Skills mechanism. Invoke the Skill that matches the current task. Each `SKILL.md` is self-contained and can be used independently.

These Skills do not assume that the agent can schedule future reviews or persist notes automatically. If a platform provides memory, task scheduling, or a notes connector, use it only when available and authorized; otherwise provide review questions and suggested dates for the learner to save.

## Learning completion

Do not equate reading or recognition with mastery. Use these levels:

- **Aware:** can recognize the term and state its basic purpose.
- **Understands:** can explain the mechanism, causal relationships, assumptions, and limitations without relying on the source.
- **Can apply:** can use the knowledge to analyze a new situation, make a decision, or solve a problem.

Mastery is topic-specific. Do not force every item to the highest level.
