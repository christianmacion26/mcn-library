# MCN Library — INDEX

> Always-updated live index of every entry in the MCN Library. MD
> primary (in-repo readable); HTML / PDF downloadable per entry.

**Library root:** `/` of this repo
**INDEX last regenerated:** 2026-07-09

---

## Categories

1. [Mentee Workbooks](#01-mentee-workbooks) — the "from the Ground Up" teaching series
2. ~~Craft Courses~~ — reserved, currently empty
3. [Research Dossiers](#03-research-dossiers) — completed research write-ups
4. [Field Guides](#04-field-guides) — practitioner workflow guides
5. ~~Reference Exemplars~~ — reserved, currently empty (third-party)
6. ~~Skill Definition~~ — reserved, currently empty (private infra)

---

## 01. Mentee Workbooks

| # | Workbook | Topics | Size |
|---|---------|--------|-----:|
| 1 | [Loop Engineering — from the Ground Up](./01-Mentee-Workbooks/loop-engineering/) | Self-improving agent loops, convergence criteria, postmortem patterns | ~ MD README + HTML + PDF |
| 2 | [Context Engineering — from the Ground Up](./01-Mentee-Workbooks/context-engineering/) | Context window discipline, retrieval primitives, M3 economy | README + HTML + PDF |
| 3 | [Obsidian Wikilinks and the Karpathy Wiki — from the Ground Up](./01-Mentee-Workbooks/obsidian-wikilinks/) | Hand-curated knowledge graphs, PPR-over-graph retrieval | README + HTML + PDF |
| 4 | [Quant Research and Trading with a Tight-Context LLM — from the Ground Up](./01-Mentee-Workbooks/quant-engineering/) | Quant research + tight-context LLM, eval gates G1–G31 | README + HTML + PDF |
| 5 | [AI Architecture — from the Ground Up (Guide)](./01-Mentee-Workbooks/ai-architecture-guide/) | Multi-agent AI architecture, boundaries, orchestration | README + HTML + PDF |
| 6 | [AI in Hedge Funds — Workbook](./01-Mentee-Workbooks/ai-in-hedge-funds/) | Institutional operating standard, audit-trail expectations | README + HTML + PDF |

---

## 03. Research Dossiers

| # | Dossier | Topic | Files |
|---|---------|-------|-------|
| 1 | [Implied vs Realized Volatility — Complete Dossier](./03-Research-Dossiers/implied-vs-realized-volatility/) | VIX vs realized SPX var, 36y, Newey-West t +6.5 | README + HTML + PDF |

---

## 04. Field Guides

| # | Guide | Topic | Files |
|---|-------|-------|-------|
| 1 | [Medium Christian — Workflow Guide](./04-Field-Guides/medium-workflow-guide/) | Self-publishing workflow, Claude-as-team pattern | README + HTML |

---

## Refresh commands

```bash
# Clone this repo, then update the index
git pull origin main
python3 scripts/generate_index.py    # future: auto-gen this file
```

Or for a manual refresh, regenerate via the same `INDEX.md` by
walking every entry folder.
