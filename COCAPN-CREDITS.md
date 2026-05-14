# Cocapn Adaptations — Credits

## Original Author

**0xjeffro** — https://github.com/0xjeffro/pbft-rust

Practical Byzantine Fault Tolerance consensus in Rust. All original source code is preserved under MIT license.

## What We Kept (With Credit)

Message types (VoteMsg, MsgType), 3-phase commit logic, quorum calculation (f=(n-1)/3)

## What We Changed

Add PLATO tile verification, replace HTTP with I2I transport, add Lamport clocks, add view-change for dynamic primary

## What We Added (Original Cocapn Work)

Constraint-based verification, E12 tile addressing, fleet-aware throttling, content-addressed state

## License Compliance

Original MIT license preserved in LICENSE file. All original code retains original copyright.
Cocapn additions are also MIT licensed. Fork maintains clear provenance via git history.

## Attribution

See also:
- ACG-DECOMPOSITION.md, A2A-DECOMPOSITION.md, AUTOMERGE-DECOMPOSITION.md, PBFT-DECOMPOSITION.md
- PENROSE-TRIQUARTER-DECOMPOSITION.md, CREWAI-DECOMPOSITION.md
- TILE-LABEL-SYSTEM.md
- Full analysis: https://github.com/SuperInstance/forgemaster
