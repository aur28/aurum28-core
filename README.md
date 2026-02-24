# Aurum28 Core

Official Aurum28 (AUR28) Layer-1 blockchain core implementation.

Aurum28 is an independent SHA-256 Proof-of-Work blockchain designed as digital gold with transparent monetary policy and fixed long-term supply.

---

## Overview

Aurum28 Core connects to the Aurum28 peer-to-peer network to:

- Validate blocks and transactions
- Maintain full node consensus
- Support mining infrastructure
- Provide RPC interface for services and applications
- Enable wallet functionality (CLI & GUI optional)

This repository contains the full reference implementation of the Aurum28 protocol.

---

## Monetary Policy

- Consensus: SHA-256 Proof-of-Work
- Initial block reward: 60 AUR
- Halving interval: 229,167 blocks
- Maximum supply: ~28,000,000 AUR (Exact cap ≈ 28,000,040 AUR)

Aurum28 is designed as a long-term store of value with predictable issuance and transparent supply.

---

## Network

- Independent Layer-1 blockchain
- Mainnet live and operational
- ASIC / GPU / CPU mining supported
- Public block explorer available

Explorer:
https://explorer.aurum28.org

Website:
https://aurum28.org

---

## Build Instructions

See documentation in the /doc directory for platform-specific build instructions.

Standard build (Unix):

    ./autogen.sh
    ./configure
    make

---

## Security

Aurum28 Core is open source under the MIT License.

This project is security-critical software.  
All contributions must follow responsible disclosure practices.

---

## License

Released under the MIT License.
See LICENSE file for details.

© 2025 Aurum28
