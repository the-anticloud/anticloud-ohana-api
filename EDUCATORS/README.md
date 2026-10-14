# Educators — OHANA_API

**Project:** OHANA_API  
**Category:** GOVERNMENT  
**Upstream:** see BENCH.json  
**Pinned commit:** `e3ab28075a5fc2f2e15ce06403db5c1e785a7778`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `2f6f21be2fc235fc793cf42e90e48b7e9896b855e892e5f0bdf8cf29456b5599`  
**Date:** October 2026

## Teaching with OHANA_API

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `2f6f21be2fc235fc793cf42e90e48b7e9896b855e892e5f0bdf8cf29456b5599` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
