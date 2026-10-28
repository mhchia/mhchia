### About

Software engineer with 8+ years of experience in P2P networking and applied cryptography (MPC, zero-knowledge proofs, and lattice-based).

Previously 6 years in total at the Ethereum Foundation:
- P2P networking @ Research team
- Privacy-preserving applications @ ZKP-Applied team and [Privacy & Scaling Explorations](https://pse.dev/)

### Applied cryptography

- [baby-lattice-folding](https://github.com/coset-io/baby-lattice-folding): a complete Rust implementation of SALSAA, a lattice-based folding scheme, from the finite field up (cyclotomic ring → NTT → sumcheck → folding, end-to-end, with CI and tests). Companion Python/SageMath implementations in [cipher-playground](https://github.com/mhchia/cipher-playground).
- [MPCStats](https://github.com/MPCStats/mpc-demo-infra): TLSNotary proves the provenance of exchange-balance inputs; MP-SPDZ (3-party honest-majority, maliciously secure) computes aggregate statistics without revealing individual balances. Live demo at Devcon 2024.
- [TLSNotary extension](https://github.com/tlsnotary/tlsn-extension): ported the Rust MPC-TLS prover to browser WASM and wired in a WebSocket-to-TCP proxy so the browser can open TLS sessions.
- [rlnjs](https://github.com/Rate-Limiting-Nullifier/rlnjs): TypeScript SDK for RLN (rate limiting for anonymous P2P networks), integrating its ZK circuits and contracts.
- [BlindFind](https://github.com/zkopru-network/blind-find): private peer discovery on a self-implemented SMP (two-party secure computation) protocol with circom / snarkJS circuits.
- [js-smp](https://github.com/mhchia/js-smp) / [PeekABook](https://github.com/mhchia/peek-a-book): the SMP implementation in TypeScript, and private order matching over WebRTC built on it.

### P2P networking

- [py-libp2p](https://github.com/libp2p/py-libp2p): primary maintainer (600+ stars). Re-architected most of an early prototype (transport, secure channel, stream multiplexing, GossipSub) and led the asyncio → Trio migration.
- [p2pclient](https://github.com/mhchia/py-libp2p-daemon-bindings): drive the Go libp2p daemon from Python over Protobuf; the first py-libp2p ↔ go-libp2p interop tests in CI.
- [Trinity](https://github.com/ethereum/trinity-eth2): early Eth2 client in Python; networking integration on py-libp2p.

### Stack

Python · Rust · TypeScript · Go · Solidity · circom · MP-SPDZ · libp2p

→ [mhchia.com](https://mhchia.com) · 📍 Taipei
