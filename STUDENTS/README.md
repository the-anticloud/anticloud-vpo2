# Students — VPO2

**Project:** VPO2  
**Category:** CLOTHING_MANUFACTURING  
**Upstream:** https://github.com/YChuan1115/vpo2-saved  
**Pinned commit:** `e31cbf7311ac1bdbde5f99dc58b85375666abe23`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `441e728820d9b61dadb162a56b2ad566040e9577323539fb2255e2556b05e289`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `e31cbf7311ac1bdbde5f99dc58b85375666abe23`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `441e728820d9b61dadb162a56b2ad566040e9577323539fb2255e2556b05e289`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
