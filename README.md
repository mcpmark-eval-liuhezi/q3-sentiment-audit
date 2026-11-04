# Q3 Sentiment Audit

Quarterly "street sentiment vs. our own research" check for the quant pod.

**Prepared:** 2026-11-04. **Source:** `research_pack.pdf` (12 pages) — cover; the approved watchlist on its own page; five single-name deep dives; a methodology note; a cross-reference rollup; a relative-value snapshot; a risk addendum; an appendix.

**Contents:**
- `watchlist.csv` — the approved watchlist at audit time, committed for the audit record.
- `findings.md` — sector, analyst recommendation counts (Yahoo Finance, current snapshot), recent upgrades/downgrades, ticker-mention pages, and the mention index.
- `watchlist_excerpt.pdf` — page 2 of the research pack (the approved *Q3 WATCHLIST* page) extracted locally for the audit attachment.

**Governance note (audit rule):** the sentiment pull was executed against the committed `watchlist.csv` in this repository — the file was re-read from the repository before the pull. Current tickers: AAPL, MSFT, NVDA, TSLA, AMZN.

**Quick results:** MSFT (Technology) 12/40/5/0/0 — the strongest Street; NVDA (Technology) 10/49/2/1/0 but heavy multi-firm PT-raise tension; TSLA (Consumer Cyclical) 5/15/22/2/0 — the most Street-indecisive; AAPL (Technology) 6/18/13/3/3 — drifting more cautious; AMZN (Consumer Cyclical) 15/42/2/0/0.

**Mention index:** 27 total ticker mentions across 12 pages — AAPL 5, MSFT 6, NVDA 5, TSLA 5, AMZN 6.
