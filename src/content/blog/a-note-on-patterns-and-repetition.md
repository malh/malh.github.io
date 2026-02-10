---
title: "A note on patterns and repetition"
description: "Most of what we call 'best practice' is just a pattern someone repeated enough times that it stuck. But repetition alone doesn't make something good — it makes it familiar."
pubDate: 2026-02-10
tag: "notes"
featured: true
---

Most of what we call "best practice" is just a pattern someone repeated enough times that it stuck. But repetition alone doesn't make something good — it makes it familiar. And familiarity is a poor substitute for understanding.

I've been thinking about this in the context of how we build things. A template gets copied. A workflow gets shared. A convention gets adopted — not because it was reasoned about, but because it was there.

## The cost of convenience

There's nothing wrong with templates. The problem starts when we stop asking _why_ the template looks the way it does. When the shape of the solution becomes invisible, we lose the ability to adapt it.

> The first time you follow a pattern, you're learning. The second time, you're practicing. The third time, you might just be avoiding thought.

This isn't an argument against convention. It's an argument for periodic re-examination. Every pattern carries assumptions about context — and context changes.

### What I've been doing about it

Lately I've been keeping a small log of every time I reach for a familiar pattern. Not to stop myself, but to notice. The log looks something like this:

```yaml
pattern: "retry with exponential backoff"
context: "background job processing"
question: "is retry even the right response here?"
```

Half the time, the pattern is fine. But the other half, I find something better — or at least, something more honest about the problem.

---

The point isn't to reinvent everything. It's to stay awake while you work.
