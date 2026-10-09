# Ethics — OPENROCKET

**Project:** OPENROCKET  
**Category:** SPACE_AEROTECH  
**Upstream:** https://github.com/openrocket/openrocket  
**Pinned commit:** `259ba462a4bfeda676af9f9cf018ad3f1a9148c8`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `a1dcf24582edd329f2b6064892a4c62f0d38659bcc5ac39a8b55c3505e355b6a`  
**Date:** October 2026

## Position

OPENROCKET is packaged for offline deployment with a verifiable audit trail. The
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
