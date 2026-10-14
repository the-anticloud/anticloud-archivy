# Independent Insurance — ARCHIVY

**Project:** ARCHIVY  
**Category:** LEGAL_TECH  
**Upstream:** see BENCH.json  
**Pinned commit:** `bdcdd39ac6cf9f7b3709b984d8be2f0fa898139e`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `f52816df766393cfd64bbaf09de6c7918cfa319ed056f896d6f3b1ee4d646307`  
**Date:** October 2026

## Why AI-specific cover matters

Deploying AI in a regulated sector creates liability surfaces that ordinary
technology cover does not reach: inference liability, audit-trail liability,
data-breach liability and IP-infringement liability.

## How this project's architecture reduces insurable risk

| Risk | Cloud AI | ARCHIVY with AIOSS |
|---|---|---|
| Audit-trail loss | high — vendor-controlled logs | low — append-only chain, verifiable offline |
| Data breach in transit | high — data transits external servers | low — no external endpoint |
| Compliance violation | high — cannot satisfy air-gap requirements | low — structural |
| IP liability | moderate | low — pinned provenance chain |

## Evidence package for an insurer

- AIOSS chain verification for head `f52816df766393cfd64bbaf09de6c7918cfa319ed056f896d6f3b1ee4d646307`
- The 16-check register with per-check evidence hashes
- Framework control mapping in `BENCH.json`

## Contact

lois@0-1.gg
