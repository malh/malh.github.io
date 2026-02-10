---
title: "Tools I reach for"
description: "A snapshot of the tools and workflows that have stuck around in my daily work. Not a recommendation list — just an honest inventory of what I actually use."
pubDate: 2026-01-20
tag: "tooling"
---

Every few months I take stock of what I'm actually using versus what I have installed. The gap is always embarrassing. Here's what survived the last audit.

## The short list

- **Neovim** — I switched from VS Code about a year ago. The learning curve was real but the payoff is that my editor never surprises me anymore.
- **tmux** — Session management. I have a script that sets up project-specific layouts. It's five lines of shell and saves me ten minutes a day.
- **ripgrep** — I grep more than I search in any GUI. `rg` is fast enough that I never feel the urge to reach for anything else.
- **jq** — For any JSON wrangling. Most of my debugging starts with piping API responses through `jq`.
- **git worktrees** — Underrated. I can review a PR while keeping my current branch untouched.

## What didn't stick

I tried Warp, Fig, and a handful of AI-powered terminal tools. They were impressive demos but added friction to my actual workflow. The common thread: they optimised for discovery when I needed speed.

### The principle

I've noticed my tool choices follow a pattern: I reach for things that are **fast, composable, and text-based**. If it can't be piped, scripted, or version-controlled, it eventually gets replaced by something that can.

---

Your tools should disappear into your workflow. If you're thinking about the tool, you're not thinking about the problem.
