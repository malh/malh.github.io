---
title: "On naming things"
description: "Names are the first interface. They shape how we think about a system before we ever read its code. A bad name doesn't just confuse — it misdirects."
pubDate: 2026-02-03
tag: "draft"
---

Names are the first interface. They shape how we think about a system before we ever read its code. A bad name doesn't just confuse — it misdirects. It creates a mental model that you then have to unlearn.

I renamed a service last week. It was called `DataProcessor`. It could have been anything. It turned out to be a rate limiter that also logged metrics. The name told you nothing and implied everything.

## What a name should do

A good name compresses understanding. It should answer the question: "what does this do?" without requiring you to open the file.

Some heuristics I've found useful:

- If the name contains "Manager", "Handler", or "Processor", it probably does too much
- If you can't explain what it does in one sentence, the abstraction might be wrong
- If two people on the team would name it differently, there's a concept that hasn't been agreed on yet

### The naming conversation

The most productive technical discussions I've had weren't about architecture or performance. They were about what to call things. Because naming forces you to agree on what something _is_ — and that's the hard part.

---

Naming things is famously one of the two hard problems in computer science. I think it's hard because it requires clarity of thought, and clarity of thought is hard.
