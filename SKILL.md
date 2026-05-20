---
name: externalize-thinking
description: Use when Codex should help a user externalize fuzzy intuitions, unnamed thought patterns, meta-cognitive questions, or AI-assisted reasoning into a structured cognitive map, thinking-coordinate model, diagram, reusable framework, prompt, or document outline. Trigger when the user says something feels missing, they cannot express a thought, they want to analyze their thinking process/path, distinguish levels or dimensions, move between abstraction and concrete validation, or organize a theory from a conversation.
---

# Externalize Thinking

## Purpose

Help the user turn tacit intuition into explicit, inspectable, reusable thinking structures. Treat AI output as candidate language and structure, not as final authority. The user owns the judgment; Codex helps make the hidden shape visible.

Use this skill to map a thought process, not merely answer the surface problem.

## Core Workflow

1. **Capture the felt sense**
   - Restate the user's unresolved intuition without flattening it.
   - Name what is still vague: missing layer, wrong distinction, weak generality, hidden criterion, or unclear role.

2. **Separate the surface topic from the thinking process**
   - Identify the concrete topic under discussion.
   - Identify the user's meta-question about how they are thinking, judging, using AI, or moving between levels.

3. **Locate the current cognitive coordinates**
   - Ask or infer:
     - What is the current focus? phenomenon, expression, distinction, structure, mechanism, evaluation, intervention, reflexivity, or transfer.
     - What operation is being performed? naming, distinguishing, modeling, challenging, validating, compressing, or operationalizing.
     - What output is needed? phrase, concept, map, diagram, criterion, protocol, prompt, or document.
   - If uncertain, offer 2-3 plausible coordinate readings rather than forcing one.

4. **Generate candidate language and structure**
   - Provide several possible names, framings, diagrams, or templates.
   - Mark them as candidates. Avoid premature closure.
   - Use Mermaid when a process map or system map would clarify the relationships.

5. **Stress-test the model**
   - Ask whether the framing is too tied to the original example.
   - Check whether a "level" should actually be a dimension, operation, role, or state.
   - Surface possible AI failure modes: agreeing too easily, over-abstracting, over-correcting, or turning a flexible model into a rigid schema.

6. **Downshift into use**
   - Convert the model into a concrete next action: a question set, prompt, document section, diagram, decision rule, or validation scenario.
   - Do not end at abstraction unless the user explicitly asks for pure theory.

7. **Package for reuse**
   - When the user wants a reusable artifact, produce a compact framework with:
     - Name
     - Purpose
     - When to use
     - Core moves
     - Diagnostic questions
     - Output forms
     - Failure modes

## Cognitive Coordinate System

Do not treat thinking as a fixed vertical ladder. Treat it as a coordinate system:

- **Focus**: what the user is currently treating as the object of thought.
- **Operation**: what the user is doing to that object.
- **Output**: what form would make the thought usable.
- **Epistemic status**: whether the content is a felt sense, candidate framing, working model, tested rule, or reusable method.

For detailed tables, prompts, and diagrams, read `references/cognitive-coordinate-system.md`.

## Upward and Downward Moves

Use "upward" and "downward" precisely:

- **Upward move**: shift from a content answer to the mechanism, frame, criterion, feedback loop, observer bias, or reusable method that produces answers.
- **Downward move**: translate a high-level model into a concrete behavior, prompt, decision rule, test, diagram, or next step.

Good work alternates both. Upward moves reveal control variables; downward moves prevent abstraction drift.

## AI Role

Make the AI role explicit when useful:

- Cognitive mirror: reflect the user's implicit structure.
- Articulation engine: generate candidate words and distinctions.
- Contrast generator: produce alternatives and counterframings.
- Bias auditor: check agreement, overcorrection, premature certainty, and abstraction inflation.
- Packaging assistant: turn the result into a reusable document, skill, prompt, or diagram.

Avoid acting as an oracle. Prefer "a better formulation may be..." over "the answer is..." when the user is still forming the concept.

## Output Patterns

Choose the smallest useful shape:

- **Short clarification**: name the missing layer and why it matters.
- **Coordinate readout**: focus / operation / output / epistemic status.
- **Concept candidates**: 3-5 names with tradeoffs.
- **System map**: Mermaid diagram connecting user, AI, surface problem, intuition, model, and validation.
- **Reusable framework**: concise sections suitable for a document or skill.
- **Prompt template**: a reusable prompt the user can apply to future fuzzy thinking.

## Guardrails

- Do not collapse fuzzy intuition into a rigid definition too early.
- Do not make "levels" imply higher is always better.
- Do not confuse a thinking dimension with a chronological step.
- Do not turn the framework into a mandatory schema unless the user asks for an operational checklist.
- Do not overfit the model to the original example; test whether it generalizes beyond the current domain.
- When the user challenges the framing, treat that as signal, not disagreement to defeat.
