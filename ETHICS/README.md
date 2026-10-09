# Ethics — ARCHIVY

**Project:** ARCHIVY  
**Category:** LEGAL_TECH  
**Upstream:** see BENCH.json  
**Pinned commit:** `bdcdd39ac6cf9f7b3709b984d8be2f0fa898139e`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `f52816df766393cfd64bbaf09de6c7918cfa319ed056f896d6f3b1ee4d646307`  
**Date:** October 2026

## Position

ARCHIVY is packaged for offline deployment with a verifiable audit trail. The
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
