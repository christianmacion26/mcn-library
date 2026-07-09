# Obsidian Wikilinks and the Karpathy Wiki — from the Ground Up
**Public edition · Made by Christian Macion — Quantitative Researcher & AI Engineer**

> A teaching workbook on **hand-curated knowledge graphs** as cheap,
> local, fully-offline retrieval. The Obsidian vault + Karpathy Wiki
> plugin stack — what it is, why it helps on tight context windows, how
> to set it up, how to maintain it, and how to wire the
> **hooks pattern** (the most important things as routing files).

This is the third workbook in the **Mentee Workbooks** series.

## What's in the workbook (5 parts, 12 chapters)

| Part | Chapters | Covers |
|---|---|---|
| **A. The shape** | 1 – 3 | Obsidian the editor, `[[wikilinks]]` the syntax, the Karpathy Wiki plugin the LLM retriever |
| **B. Why it helps** | 4 – 5 | The four retrieval strategies ranked by cost, the tight-context LLM economy, the four retrieval primitives |
| **C. How to use it** | 6 – 8 | Setup, daily workflow (capture / query / maintain), vault shape (six folders × six jobs) |
| **D. Optimizing** | 9 – 10 | 12 techniques that compound (3 tiers) + 10 anti-patterns |
| **E. The hooks pattern** | 11 – 12 | The principle + its empirical foundation; wiring the three startup files (`CLAUDE.md`, `MEMORY.md`, `index.md`) |

The **hooks pattern chapter (Part E)** is new in this public edition.
It covers the principle — that the most important things should be
small, eagerly-loaded structural hooks — and how to wire it into your
vault with three startup files that any modern AI agent will load
automatically on session start.

## Format

| File | How to read |
|---|---|
| [`Obsidian-Wikilinks-and-the-Karpathy-Wiki-Public-Edition.html`](./Obsidian-Wikilinks-and-the-Karpathy-Wiki-Public-Edition.html) | Open in any browser |
| [`Obsidian-Wikilinks-and-the-Karpathy-Wiki-Public-Edition.pdf`](./Obsidian-Wikilinks-and-the-Karpathy-Wiki-Public-Edition.pdf) | Download for printing or offline reading |

## Sources

- [Karpathy Wiki plugin (Obsidian community)](https://community.obsidian.md/plugins/karpathywiki)
- [Karpathy `llm-wiki` gist (April 2026)](https://gist.github.com/karpathy/442a6bf555914893e9891c11519de94f) — the routing-file pattern
- [Anthropic — Equipping agents for the real world with Agent Skills](https://www.anthropic.com/engineering/equipping-agents-for-the-real-world-with-agent-skills)
- [Anthropic — Effective context engineering for AI agents](https://www.anthropic.com/engineering/effective-context-engineering-for-ai-agents)
- [Claude Code skills docs](https://code.claude.com/docs/en/skills)
- [Liu et al., TACL 2024 — Lost in the Middle](https://aclanthology.org/2024.tacl-1.9/) — the U-shaped position bias
- [Chroma Research — Context rot, July 2025](https://research.trychroma.com/context-rot) — context rot + distractor cost
- [arxiv 2510.05381](https://arxiv.org/abs/2510.05381) — length as independent failure mode

## A note on this edition

This is the **public-shareable edition** of the workbook. It is
model-agnostic (any tight-context LLM, not a specific model), and
internal references have been scrubbed. Made by **Christian Macion —
Quantitative Researcher & AI Engineer**, who uses this exact pattern
in his own working vault.

## Related

- [Context-Engineering](../context-engineering/) — the retrieval discipline the vault serves
- [Loop-Engineering](../loop-engineering/) — the convergence discipline that runs over the vault
- [AI-Architecture Guide](../ai-architecture-guide/) — multi-agent boundaries and orchestration

---

© Christian Macion. Released under the MIT License.
