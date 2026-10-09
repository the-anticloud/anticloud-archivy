# Educators — ARCHIVY

**Project:** ARCHIVY  
**Category:** LEGAL_TECH  
**Upstream:** see BENCH.json  
**Pinned commit:** `bdcdd39ac6cf9f7b3709b984d8be2f0fa898139e`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `f52816df766393cfd64bbaf09de6c7918cfa319ed056f896d6f3b1ee4d646307`  
**Date:** October 2026

## Teaching with ARCHIVY

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `f52816df766393cfd64bbaf09de6c7918cfa319ed056f896d6f3b1ee4d646307` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
