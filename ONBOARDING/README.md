# Onboarding — CORE

**Project:** CORE  
**Category:** ELECTRICITY_MANAGEMENT  
**Upstream:** https://github.com/home-assistant/core  
**Pinned commit:** `bbfbdee65e4ee67b25bbdc7238788d2bcfb84c86`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `cc8f8ba2644ecfc38ea279d9781c13217c2938fe50fa2196020842e77e9e0541`  
**Date:** October 2026

## First hour

1. Read `README.md` — what the project is and what it measures.
2. Read `ISOLATED_LAB_RESULTS/03_Result_Register.md` — the 16 checks and their
   evidence hashes.
3. Run the suite: `python tools/run_bench.py --out BENCH.json`.
4. Verify a hash: recompute SHA3-256 of a file in `04_Evidence/` and compare.

## First day

- `10_TECHNICAL_HANDOFF` — architecture and interfaces
- `11_TUTORIAL_DEVELOPERS` — build and test
- `18_COMMAND_LINE_INTERFACE` — CLI reference
- `27_DEPENDENCIES` — the offline dependency mirror

## Getting help

lois@0-1.gg · 0-1.gg
