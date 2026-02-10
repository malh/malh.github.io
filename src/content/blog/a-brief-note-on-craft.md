---
title: "A brief note on craft"
description: "There's a difference between code that works and code that was crafted. The difference isn't complexity — it's care. And care shows up in the smallest details."
pubDate: 2026-01-12
tag: "thinking"
---

There's a difference between code that works and code that was crafted. The difference isn't complexity — it's care. And care shows up in the smallest details.

I reviewed a pull request last week that was technically correct. Every test passed. The logic was sound. But the variable names were afterthoughts, the error messages were generic, and the commit history was a single "wip" squash. It worked. But nobody had _thought_ about it.

## What craft looks like

Craft in software isn't about writing clever code. It's about:

- Choosing names that teach the next reader what's happening
- Writing error messages that help the person debugging at 2am
- Structuring commits so the _reasoning_ is preserved, not just the result
- Leaving the codebase slightly better than you found it

None of these show up in metrics. None of them will make a feature ship faster. But they compound over time into the difference between a codebase people dread and one they enjoy.

> Craft is what you do when no one is measuring.

### The counterargument

"We don't have time for craft." I hear this a lot. But craft isn't about spending more time — it's about spending the same time more intentionally. A good name takes five extra seconds. A clear commit message takes thirty. These aren't luxuries. They're investments that pay back within the week.

---

Ship fast, but don't ship carelessly. The two are not the same thing.
