---
title: "A small prompt template"
description: "I've been refining a simple structure for prompts that consistently produces better results. Context, constraints, format — in that order."
pubDate: 2026-01-28
tag: "prompt"
---

I've been refining a simple structure for prompts that consistently produces better results. It's nothing revolutionary — just three sections in a specific order.

## The template

```
CONTEXT: [What you're working on and why]
CONSTRAINTS: [What the output must or must not do]
FORMAT: [How you want the response structured]
```

That's it. Context first, because without it the model is guessing. Constraints second, because they narrow the space. Format last, because it shapes the output without affecting the thinking.

## Why order matters

I used to lead with format — "give me a bullet list of..." — and the results were always shallow. Leading with context changes the depth of the response entirely. The model spends its capacity on understanding rather than formatting.

> Prompting well is less about clever tricks and more about clear communication. The same skills that make you good at writing specs make you good at writing prompts.

### An example

Here's one I used recently:

```
CONTEXT: I'm debugging a memory leak in a Node.js service that
processes webhook events. The service runs in Kubernetes and
memory grows linearly with uptime.

CONSTRAINTS: Focus on common patterns that cause leaks in
event-driven architectures. Don't suggest generic profiling
steps — I've already done heap snapshots.

FORMAT: List the top 3 most likely causes with a one-sentence
explanation each, then expand on the most likely one.
```

The response was specific, actionable, and skipped the basics I already knew.

---

Templates are starting points, not rules. Adapt the structure to the problem. But if you're not sure where to start, context-constraints-format is a reliable default.
