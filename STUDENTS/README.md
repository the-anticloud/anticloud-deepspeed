# Students — DEEPSPEED

**Project:** DEEPSPEED  
**Category:** FRONTIER_HARNESSES  
**Upstream:** see BENCH.json  
**Pinned commit:** `0c6dd5ed1ec0f0967ae0564534ecfa6f157c6746`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `7622fbb07c106a159e6c63c3bd948aa952eb064b9a83754fbc9cb1e5230c2344`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `0c6dd5ed1ec0f0967ae0564534ecfa6f157c6746`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `7622fbb07c106a159e6c63c3bd948aa952eb064b9a83754fbc9cb1e5230c2344`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
