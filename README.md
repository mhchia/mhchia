### About

Software engineer — backend, distributed systems, P2P networking; applied cryptography (ZK, MPC) as a specialization. 

8+ years:
- **Ethereum Foundation** (6 years): P2P networking @ Research team; privacy-preserving applications @ [Privacy & Scaling Explorations](https://pse.dev/)
- **XY Finance**: production cross-chain financial systems
- **[Lawskey](https://lawskey.com/)**: 0→1 AI product as co-founder & CTO

### Currently

Open to backend / distributed-systems / payments / blockchain protocol roles — Taipei or remote.

### Selected work

**Production**

- **XY Finance** — cross-chain bridge across 15+ networks (~$3M avg TVL). Owned the swap engine, backend services, and internal Python libraries; co-designed and implemented the custody / swap smart contracts; built the PostgreSQL transaction manager (nonce coordination, row-level locking, rollback / re-validation / retry). [xy-protocol](https://github.com/XY-Finance/xy-protocol)
- **Lawskey** — led engineering for a [B2C AI contract-review product](https://app.lawskey.com/) and a [B2B contract-lifecycle platform](https://lawskey.com/): FastAPI / PostgreSQL / Cloud Run, async LLM review workflow, LLM-as-judge evaluation, organization-scoped access control.

**Open source / systems**

- [py-libp2p](https://github.com/libp2p/py-libp2p) — primary maintainer (600+ stars). Re-architected and re-implemented most of an early prototype — transport, secure channel, stream multiplexing, GossipSub — and led the asyncio → Trio migration. Led the first py-libp2p ↔ go-libp2p interop.
- [p2pclient](https://github.com/mhchia/py-libp2p-daemon-bindings) — control the Go libp2p daemon from Python over a Protobuf protocol; CI interop tests.
- [Trinity](https://github.com/ethereum/trinity-eth2) — early Eth2 client in Python; networking integration on py-libp2p.

**Applied cryptography**

- [baby-lattice-folding](https://github.com/coset-io/baby-lattice-folding) — a complete Rust implementation of SALSAA, a lattice-based folding scheme, from the finite field up (cyclotomic ring → NTT → sumcheck → folding, end-to-end, with CI and tests). Companion Python/SageMath implementations in [cipher-playground](https://github.com/mhchia/cipher-playground).
- [MPCStats](https://github.com/MPCStats/mpc-demo-infra) — led a 3-person team: TLSNotary proves the provenance of exchange-balance inputs, MP-SPDZ (3-party honest-majority, maliciously secure) computes aggregate statistics without revealing individual balances. Live demo at Devcon 2024.
- [TLSNotary extension](https://github.com/tlsnotary/tlsn-extension) — ported the Rust prover to browser WASM; added a WebSocket-to-TCP proxy so the browser can open TLS sessions.
- [rlnjs](https://github.com/Rate-Limiting-Nullifier/rlnjs) — TypeScript SDK for RLN (rate limiting for anonymous P2P networks), integrating its ZK circuits and contracts.
- [BlindFind](https://github.com/zkopru-network/blind-find) — private peer discovery on a self-implemented SMP (two-party secure computation) protocol with circom / snarkJS circuits.

### Stack

Python · TypeScript · Solidity · Rust · C/C++ · Go — FastAPI · PostgreSQL · GCP Cloud Run · libp2p · circom · MP-SPDZ

📍 Taipei, Taiwan
