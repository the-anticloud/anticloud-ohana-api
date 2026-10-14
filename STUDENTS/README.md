# Students — OHANA_API

**Project:** OHANA_API  
**Category:** GOVERNMENT  
**Upstream:** see BENCH.json  
**Pinned commit:** `e3ab28075a5fc2f2e15ce06403db5c1e785a7778`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `2f6f21be2fc235fc793cf42e90e48b7e9896b855e892e5f0bdf8cf29456b5599`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `e3ab28075a5fc2f2e15ce06403db5c1e785a7778`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `2f6f21be2fc235fc793cf42e90e48b7e9896b855e892e5f0bdf8cf29456b5599`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
