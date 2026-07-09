# Implied vs Realized Volatility — Complete Research Dossier

> A complete-dossier research note: VIX (implied) vs realized SPX
> variance over 36 years. Documents that implied > realized 85% of
> days, with Newey-West t-statistic +6.5 on the premium.

## What this dossier is

A research-level write-up of a single factor: the **variance risk
premium** = implied volatility − realized volatility, computed
end-of-day over 36 years of SPX data. Methodology, raw numbers,
Newey-West-corrected significance, and the conclusion that the
premium is positive and statistically significant — independent of
the 1987 and 2008 outliers.

## Format

| File | How to read |
|---|---|
| [`implied_vs_realized_volatility.html`](./implied_vs_realized_volatility.html) | Open in any browser |
| [`implied_vs_realized_volatility.pdf`](./implied_vs_realized_volatility.pdf) | Download for printing |

## Related repos

- [`variance-risk-premium`](https://github.com/christianmacion26/variance-risk-premium)
  — the standalone reproducible Python implementation
- [`vol-surface-svi`](https://github.com/christianmacion26/vol-surface-svi)
  — front-end SVI fit, complementary surface work
- [`vol-regime-classifier`](https://github.com/christianmacion26/vol-regime-classifier)
  — 2-state HMM that the VRP signal pairs naturally with

---

© Christian T. Macion. Released under the MIT License.
