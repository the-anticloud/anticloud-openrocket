# Educators — OPENROCKET

**Project:** OPENROCKET  
**Category:** SPACE_AEROTECH  
**Upstream:** https://github.com/openrocket/openrocket  
**Pinned commit:** `259ba462a4bfeda676af9f9cf018ad3f1a9148c8`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `a1dcf24582edd329f2b6064892a4c62f0d38659bcc5ac39a8b55c3505e355b6a`  
**Date:** October 2026

## Teaching with OPENROCKET

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `a1dcf24582edd329f2b6064892a4c62f0d38659bcc5ac39a8b55c3505e355b6a` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
