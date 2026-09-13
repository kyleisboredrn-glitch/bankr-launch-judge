# Bankr scheduled prompt

Paste this as a recurring agent prompt on Bankr (every 1–2 hours is enough; the public launches endpoint only returns the latest 50).

```
Run bankr-launch-judge.

1. GET https://api.bankr.bot/token-launches
2. Keep Base and Robinhood Chain deploys only.
3. Load /cases/bankr-launch-judge/ledger.json (create it if missing).
4. Open a new case for every new tokenAddress.
5. Re-review any case whose nextReview is due.
6. Facts only. Labels must be rug, vapor, slow cook, or diamond, each with a confidence decimal.
7. Note every concern and every reason for sustained doubt.
8. Write a two-sided thesis (what could go wrong vs what could change for the better) on each touched case.
9. Compare new cases to the last 20 ledger entries for serial wallets, ticker clones, brand hijacks, and fee-without-product.
10. Save the updated ledger and a dated markdown report under /cases/bankr-launch-judge/.
11. Chat back only: counts by label, new flags, label changes, and full writeups for rug or diamond calls.

Do not recommend buys. Do not invent market caps or holder counts.
```
