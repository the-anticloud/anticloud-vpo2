# Educators — VPO2

**Project:** VPO2  
**Category:** CLOTHING_MANUFACTURING  
**Upstream:** https://github.com/YChuan1115/vpo2-saved  
**Pinned commit:** `e31cbf7311ac1bdbde5f99dc58b85375666abe23`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `441e728820d9b61dadb162a56b2ad566040e9577323539fb2255e2556b05e289`  
**Date:** October 2026

## Teaching with VPO2

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `441e728820d9b61dadb162a56b2ad566040e9577323539fb2255e2556b05e289` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
