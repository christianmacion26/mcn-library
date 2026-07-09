# MCN Library

> **A public library of teaching workbooks, research dossiers, and
> field guides by Christian T. Macion — Quantitative Researcher & AI Engineer.**

| | |
|---|---|
| **Live site** | [christianmacion26.github.io/portfolio/](https://christianmacion26.github.io/portfolio/) |
| **Author** | [@christianmacion26](https://github.com/christianmacion26) |
| **Stack** | MD primary (in-repo rendered) · HTML / PDF for full content |
| **License** | [MIT](./LICENSE) |

---

## What this library is

The **MCN Library** is the public, in-repo mirror of a teaching series
in the same shape as the author's private Macion Library — a single
flat index over a dozen cookbooks that, together, form the working
notes for a senior Quantitative Researcher + AI Engineer who has spent
five years publishing methodology in the open.

It is **not**:

- A personal homepage — see the [portfolio site](https://christianmacion26.github.io/portfolio/) for that.
- A blog — posts go to Medium Christian.
- A live research log — that lives in the author's private vault.

It **is** a set of cookbooks whose version grows when the underlying
method moves. Each entry is a teaching artifact with a `README.md`
(hand-readable in the repo view), an HTML file (browser-readable
when downloaded), and a PDF (printable).

---

## Categories

```
MCN Library/
├── 01-Mentee-Workbooks/   ← the "from the Ground Up" teaching series
├── 03-Research-Dossiers/  ← completed research write-ups
├── 04-Field-Guides/       ← practitioner workflow guides
├── README.md              ← this file
├── INDEX.md               ← every entry, alphabetical
└── LICENSE                ← MIT
```

> `02-Craft-Courses` and `05-Reference-Exemplars` are reserved but currently empty — the
> materials for those are either internal-only or third-party-consent.
> `06-Skill-Definition` is private infra, not published.

---

## How to read

1. **In browser** — read the `README.md` of any workbook. Each README
   is a hand-written description, citations, related work.
2. **For the full content** — open the matching `*.html` in any browser
   (no dependency, fully self-contained). Or download the `*.pdf` for
   offline / print.
3. **For the running implementation** — every workbook points at
   standalone repos under [@christianmacion26](https://github.com/christianmacion26?tab=repositories&q=public)

---

## Where the live research goes

The author publishes standalone reproducible research repos as the work
ships. The MCN Library links to them but does not duplicate the source
code. The current set of public research repos:

| Topic | Repo |
|---|---|
| Calibration pipeline (60 markets) | [`prediction-market-calibration`](https://github.com/christianmacion26/prediction-market-calibration) |
| Cross-asset carry IS→OOS decay | [`cross-asset-carry`](https://github.com/christianmacion26/cross-asset-carry) |
| Crypto funding carry decay | [`funding-carry`](https://github.com/christianmacion26/funding-carry) |
| BTC-ETH pairs honest null | [`pairs-cointegration`](https://github.com/christianmacion26/pairs-cointegration) |
| Cross-sectional momentum | [`cross-sectional-momentum`](https://github.com/christianmacion26/cross-sectional-momentum) |
| Time-series momentum + vol-target | [`timeseries-momentum-voltarget`](https://github.com/christianmacion26/timeseries-momentum-voltarget) |
| VRP 36-year study | [`variance-risk-premium`](https://github.com/christianmacion26/variance-risk-premium) |
| Vol-regime 2-state HMM | [`vol-regime-classifier`](https://github.com/christianmacion26/vol-regime-classifier) |
| SVI vol surface fit | [`vol-surface-svi`](https://github.com/christianmacion26/vol-surface-svi) |
| VIX term-structure overlay | [`skew-term-structure`](https://github.com/christianmacion26/skew-term-structure) |
| Macro regime overlay | [`macro-regime-overlay`](https://github.com/christianmacion26/macro-regime-overlay) |
| Backtest engine with TC | [`backtest-engine-costs`](https://github.com/christianmacion26/backtest-engine-costs) |
| Bias audit (look-ahead) | [`bias-audit`](https://github.com/christianmacion26/bias-audit) |
| Validation gate stack | [`validation-gate-stack`](https://github.com/christianmacion26/validation-gate-stack) |
| Deflated Sharpe analysis | [`multiple-testing-deflated-sharpe`](https://github.com/christianmacion26/multiple-testing-deflated-sharpe) |
| Prediction-market edge | [`prediction-market-edge`](https://github.com/christianmacion26/prediction-market-edge) |
| Tool-call agent (offline) | [`toolcall-agent`](https://github.com/christianmacion26/toolcall-agent) |
| Reflect-revise agent | [`reflect-revise`](https://github.com/christianmacion26/reflect-revise) |
| RAG-recall measurement | [`rag-recall`](https://github.com/christianmacion26/rag-recall) |
| Judge harness (Cohen's κ) | [`judge-harness`](https://github.com/christianmacion26/judge-harness) |
| MCP eval server | [`eval-mcp-server`](https://github.com/christianmacion26/eval-mcp-server) |
| Streamlit slop-gate | [`slop-scanner`](https://github.com/christianmacion26/slop-scanner) |

---

## Contributing

This library is **a single-author teaching series**. Pull requests
that correct typos are welcome; corrections to substantive claims
should come with a citation or a reproducible notebook.

---

## Author

**Christian T. Macion** — Quantitative Researcher + AI Engineer. Digos
City, Davao del Sur (UTC+8). Background: PSHS-SMC → USeP units → UM → STA.

- Portfolio: [christianmacion26.github.io/portfolio/](https://christianmacion26.github.io/portfolio/)
- GitHub: [@christianmacion26](https://github.com/christianmacion26)
- Medium: [@christianmacion](https://medium.com/@christianmacion)

---

© Christian T. Macion. Released under the MIT License. See [LICENSE](./LICENSE).
