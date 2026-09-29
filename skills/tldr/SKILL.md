---
name: tldr
description: Distil a response to its essence — key points, examples and diagrams in a short, scannable shape.
disable-model-invocation: true
argument-hint: "[question]"
---

Give the user the essence of the content. Cut everything else.

## Scope

Applies to one response only.

- `/tldr` — summarise the response just given. Do not re-answer.
- `/tldr <question>` — answer the question in this format.

## What to keep

- The direct answer or conclusion, first.
- The few points the user must know or act on.
- A caveat only if ignoring it would cause a mistake.

Drop background, reasoning steps, alternatives, and edge cases. If the user wants more, they will ask.

## Format

Short and direct. No paragraphs. Write in ASD-STE100 Simplified Technical English. State points directly; avoid "X, not Y" contrasts.

Show the essence visually wherever possible. Use a short example, a diagram, or a small table when the content allows one. Keep each visual small and focused on the key point.

Use point form for the rest. **Bold** the key takeaways.

When the content covers several concepts, group related points under short headings. Give each group its own essence and order the groups by importance or by logical sequence.
