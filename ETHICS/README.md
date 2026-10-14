# Ethics — VPO2

**Project:** VPO2  
**Category:** CLOTHING_MANUFACTURING  
**Upstream:** https://github.com/YChuan1115/vpo2-saved  
**Pinned commit:** `e31cbf7311ac1bdbde5f99dc58b85375666abe23`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `441e728820d9b61dadb162a56b2ad566040e9577323539fb2255e2556b05e289`  
**Date:** October 2026

## Position

VPO2 is packaged for offline deployment with a verifiable audit trail. The
ethical questions this raises are answered by making the system's behaviour
checkable rather than by policy statements.

## The four commitments

1. **No hidden egress.** The deployment has no external API dependency; this is
   testable by running it with the network disconnected.
2. **Attributable output.** Every artifact is recorded in a hash chain, so what
   the system produced can be reconstructed.
3. **Operator control.** The institution owns the hardware and the keys.
4. **Refusal to overclaim.** Where a certification is not held, the project says
   so rather than implying it.

## Dual use

This project is packaged for civilian and public-sector deployment. Where an
upstream has dual-use characteristics, the licence gate and the reference-only
marking in `BENCH.json` record that.
