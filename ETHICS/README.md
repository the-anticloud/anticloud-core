# Ethics — CORE

**Project:** CORE  
**Category:** ELECTRICITY_MANAGEMENT  
**Upstream:** https://github.com/home-assistant/core  
**Pinned commit:** `bbfbdee65e4ee67b25bbdc7238788d2bcfb84c86`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `cc8f8ba2644ecfc38ea279d9781c13217c2938fe50fa2196020842e77e9e0541`  
**Date:** October 2026

## Position

CORE is packaged for offline deployment with a verifiable audit trail. The
ethical questions this raises are answered by making the system's behaviour
checkable rather than by policy statements.

## The four commitments

1. **No hidden egress.** The deployment has no external API dependency; this is
   testable by running it with the network disconnected.
2. **Attributable output.** Every artifact is recorded in a hash chain, so what
   the system produced can be reconstructed.
3. **Operator control.** The institution owns the hardware and the keys.
4. **Refusal to overclaim.** Where a certification is not held, the project says
   so rather than implying it.

## Dual use

This project is packaged for civilian and public-sector deployment. Where an
upstream has dual-use characteristics, the licence gate and the reference-only
marking in `BENCH.json` record that.
