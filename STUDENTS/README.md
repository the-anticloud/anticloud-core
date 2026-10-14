# Students — CORE

**Project:** CORE  
**Category:** ELECTRICITY_MANAGEMENT  
**Upstream:** https://github.com/home-assistant/core  
**Pinned commit:** `bbfbdee65e4ee67b25bbdc7238788d2bcfb84c86`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `cc8f8ba2644ecfc38ea279d9781c13217c2938fe50fa2196020842e77e9e0541`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `bbfbdee65e4ee67b25bbdc7238788d2bcfb84c86`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `cc8f8ba2644ecfc38ea279d9781c13217c2938fe50fa2196020842e77e9e0541`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
