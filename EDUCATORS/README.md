# Educators — DEEPSPEED

**Project:** DEEPSPEED  
**Category:** FRONTIER_HARNESSES  
**Upstream:** see BENCH.json  
**Pinned commit:** `0c6dd5ed1ec0f0967ae0564534ecfa6f157c6746`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `7622fbb07c106a159e6c63c3bd948aa952eb064b9a83754fbc9cb1e5230c2344`  
**Date:** October 2026

## Teaching with DEEPSPEED

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `7622fbb07c106a159e6c63c3bd948aa952eb064b9a83754fbc9cb1e5230c2344` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
