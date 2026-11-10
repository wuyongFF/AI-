# Axiom One Core (open part)

A **memory-and-verification loop** for coding agents, distilled from a
production agent system that has been running daily since 2025.

## What it does

- **Cognitive loop**: the agent tags its own results (7 tag types),
  stores them in a layered memory (auto tags + human notes), recalls
  them through a four-layer funnel before acting, and writes the
  *outcome* back (adopt / effect score). The more you use it, the less
  it repeats past mistakes.
- **Task loop**: five-question scoping, step gates, an audit agent that
  cross-checks every plan step, chain documents with stage sign-off,
  and a machine-verifiable DONE gate. No step may be closed on words alone.
- **Portable**: everything (data + agent) ships on a USB stick; your
  data never leaves the stick.

## This repo (what is public)

| File | What you get |
|---|---|
| `docs/*` | Full design write-ups: the cognitive loop end-to-end (hard-core version), the open-source strategy, and the persuasion-grade walkthrough |
| `README.md` | This file |

The commercial desktop engine, distribution server, and paid features
are **not** part of this repository. This repo publishes the *design
and the method*, not the closed-source product.

## License

Apache-2.0
