# Compliance — OHANA_API

**Project:** OHANA_API  
**Category:** GOVERNMENT  
**Upstream:** see BENCH.json  
**Pinned commit:** `e3ab28075a5fc2f2e15ce06403db5c1e785a7778`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `2f6f21be2fc235fc793cf42e90e48b7e9896b855e892e5f0bdf8cf29456b5599`  
**Date:** October 2026

## Position

OHANA_API is mapped against eleven frameworks in `BENCH.json`:
OWASP LLM Top 10, OWASP Top 10 (2021), SOC 2 Type II readiness, NIST AI RMF,
NIST SP 800-53 Rev. 5, NIST CSF 2.0, FedRAMP Rev. 5, PCI DSS v4.0.1,
ISO/IEC 27001:2022, MITRE ATT&CK v16, and ML TRL.

**Current result: 16/16 checks passing.**

## What the mapping asserts

For each framework, every in-scope control is bound to a named evidence source
in this project, and that source exists and is re-runnable. The control counts
and evidence counts are recorded per framework in `BENCH.json`.

## What is not claimed

No audit opinion, SOC report, FedRAMP authorisation, PCI attestation or ISO
certificate is held. Those are issued by an independent assessor against a
defined period of operation; no project can self-issue one. See
`OFFICIAL_BENCHMARKS/` for the per-framework scope statement.

## Verification

Open `ISOLATED_LAB_RESULTS/03_Result_Register.md`, read a row, recompute the
SHA3-256 of its evidence file in `04_Evidence/`, compare.
