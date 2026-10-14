# Independent Insurance — OHANA_API

**Project:** OHANA_API  
**Category:** GOVERNMENT  
**Upstream:** see BENCH.json  
**Pinned commit:** `e3ab28075a5fc2f2e15ce06403db5c1e785a7778`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `2f6f21be2fc235fc793cf42e90e48b7e9896b855e892e5f0bdf8cf29456b5599`  
**Date:** October 2026

## Why AI-specific cover matters

Deploying AI in a regulated sector creates liability surfaces that ordinary
technology cover does not reach: inference liability, audit-trail liability,
data-breach liability and IP-infringement liability.

## How this project's architecture reduces insurable risk

| Risk | Cloud AI | OHANA_API with AIOSS |
|---|---|---|
| Audit-trail loss | high — vendor-controlled logs | low — append-only chain, verifiable offline |
| Data breach in transit | high — data transits external servers | low — no external endpoint |
| Compliance violation | high — cannot satisfy air-gap requirements | low — structural |
| IP liability | moderate | low — pinned provenance chain |

## Evidence package for an insurer

- AIOSS chain verification for head `2f6f21be2fc235fc793cf42e90e48b7e9896b855e892e5f0bdf8cf29456b5599`
- The 16-check register with per-check evidence hashes
- Framework control mapping in `BENCH.json`

## Contact

lois@0-1.gg
