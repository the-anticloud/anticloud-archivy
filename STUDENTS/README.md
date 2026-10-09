# Students — ARCHIVY

**Project:** ARCHIVY  
**Category:** LEGAL_TECH  
**Upstream:** see BENCH.json  
**Pinned commit:** `bdcdd39ac6cf9f7b3709b984d8be2f0fa898139e`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `f52816df766393cfd64bbaf09de6c7918cfa319ed056f896d6f3b1ee4d646307`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `bdcdd39ac6cf9f7b3709b984d8be2f0fa898139e`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `f52816df766393cfd64bbaf09de6c7918cfa319ed056f896d6f3b1ee4d646307`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
