# Decision tree

Walk top to bottom. Stop at the first matching primary label. Then set confidence from the evidence quality, not from how much you like the name.

## 1. Is this a Bankr Doppler launch on Base or Robinhood?

If no, refuse the four-label scheme or mark `out_of_scope`.

## 2. Brand, parasite, or serial extraction?

Apply **rug** when at least one is true and documented:

- BRAND_HIJACK plus measurable first-hour flow, or BRAND_HIJACK plus no disclaimer that this is unofficial
- SERIAL_FARM of unrelated tickers with no shared product and no builder continuity
- False claim of official affiliation that is contradicted by the real entity or by the fee-recipient identity
- Same wallet previously labeled rug at medium+ confidence

If the impersonation is obvious but there is zero flow and a joke framing from a known account, you may stay on vapor with a BRAND_HIJACK flag. State why you withheld rug.

## 3. Diamond test (all five required)

1. Identifiable builder matching deployer or fee recipient
2. Product or agent flywheel exists off the ticker
3. Persistent volume or creator fees after 48 hours
4. No BRAND_HIJACK, no SERIAL_FARM in the last 7 days from that wallet
5. Public claims survive source check

## 4. Slow cook test

Need at least three of: identifiable builder, no BRAND_HIJACK, post-launch signal, vest still locked, not a 3+ ticker spray in 24h.

## 5. Default

vapor. Do not promote to diamond on launch day.
