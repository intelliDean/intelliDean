# Hey, I'm Dean 👋

### Protocol Engineer · Distributed Systems & Fintech · Rust Systems · ZK & Privacy

Performance is non-negotiable. Privacy is a right. Decentralisation is the point. I build at that intersection — and when the tools don't exist to build it right, I stop and build those first. Production Rust, financial protocols, cloud-native distributed systems, cross-chain execution engines, and the writing that makes it all make sense to other developers.

Currently focused on: **Protocol Engineering** · **Financial Infrastructure & Microservices** · **ZK/Privacy Systems** · **Devtooling**

---

## 💎 Featured Projects

### 🏮 [Atupa](https://github.com/intelliDean/Atupa) — Universal Multi-VM Execution Profiler
* **Architecture**: Modular 13-crate Rust workspace (`atupa-core` on crates.io).
* **Multi-VM Coverage**: EVM, Arbitrum Stylus (WASM), Starknet (Cairo), Solana (SVM), and Stellar (Soroban).
* **Highlights**: Cross-VM execution timeline stitching, protocol-aware gas/step accounting, and local-first interactive flamegraphs (`atupa studio`).
* **Takeaway**: Shipped production tooling solving the multi-VM execution and profiling gap.

### 💳 [ISO-8583](https://github.com/intelliDean/ISO-8583) — Enterprise Payment Protocol Engine & Host Simulator
* **Core Engine**: High-performance payment switch and host simulator implementing **ISO 8583:1987**, **Visa SMS**, and **Mastercard IPM** powered by **Java 26 Virtual Threads**.
* **Dual Interface**: Raw binary TCP socket (Port 8583 with 2-byte big-endian framing & 10-char TPDU) + TLS 1.3 / mTLS client auth + REST Management API & Web Control Center.
* **Banking Cryptography & EMV**: ANSI X9.24 DUKPT key tree derivation (BDK/IPEK/PEK/MAK), ISO 9564 PIN translation (Formats 0, 1, 3, 4), ISO 9797-1 Retail MAC, and EMV BER-TLV chip decoding (DE 55).
* **Clearing & Settlement**: Dual-Message System (DMS) engine with 1240 First Presentment, 1440 Chargeback dispute filing, and scheme interchange fee calculation.
* **Stack**: `Java 21/26` · `Virtual Threads` · `Spring Boot` · `PostgreSQL 16` · `Redis 7` · `Apache Kafka 3.6` · `Prometheus`

### 🌐 [Artezan](https://github.com/intelliDean/Artezan-Microservices) — Enterprise 12-Factor Microservices Platform
* **Architecture**: Production-grade, 12-factor cloud-native microservices platform decoupled across 8 domain services (User, Booking, Listing, Task, Review, Payment, Notification, Media).
* **Distributed Resiliency**: Containerized across 16 Docker containers, featuring **Resilience4j circuit breakers**, **Kafka Dead Letter Topics (DLT)** in KRaft mode, and Spring Cloud Config Server with `{cipher}` encrypted secrets.
* **Observability & Gateway**: API Gateway with Redis rate limiting, JWT stateless auth, Zipkin distributed tracing, and Prometheus/Grafana operational metrics.
* **Stack**: `Java 25` · `Spring Boot 3.4+ / 4.1.0` · `Spring Cloud (Eureka)` · `Docker (16 Containers)` · `Kafka KRaft` · `Redis` · `Zipkin`

### 🛡️ [FNN Safeguard](https://github.com/intelliDean/fnn_safeguard) — Nervos Fiber DR & Safety Qualification
* **Safety Invariants**: Enforces machine-verifiable safety invariants (I1–I8) with deterministic fail-closed verdicts.
* **Isolated Drills**: Executes sandboxed disaster recovery drills against official `fnn v0.9.0` release binaries without endangering live node state.
* **Integrity**: Cryptographic manifests, RocksDB checkpoint validation, and upstream node issue qualification.
* **Takeaway**: Critical operator safety envelope for Nervos Fiber Network nodes.

### 🔒 [Zcash Private Receive Bridge](https://github.com/intelliDean/zcash-prb) — Zero-Leakage Wallet Daemon
* **Privacy Defense**: Eliminates IP, query timing, and metadata correlation for unmodified Zcash light wallets (Zkool, Zingo, Ledger).
* **Architecture**: Strict local gRPC endpoint (loopback), durable SQLite WAL state, and unconditional public interval ingestion with zero client-driven fallback.
* **Takeaway**: Pure defense-in-depth privacy architecture for decentralized light clients.

### ⚡ [Payego](https://github.com/intelliDean/Payego) — High-throughput Fintech Engine
* **Architecture**: Clean Architecture Rust workspace (Axum, Diesel, PostgreSQL) with React UI.
* **Highlights**: Multi-currency wallet (20+ currencies), Stripe/PayPal/Paystack integration, OpenAPI (`utoipa`), and structured `tracing` with 30+ integration tests.
* **Takeaway**: Enterprise-grade financial platform engineered for auditability and high concurrency.

### 🔮 [PhantomBet](https://github.com/intelliDean/PhantomBet) — AI-powered Prediction Market
* **Innovation**: Decentralized prediction market with GPT-4 powered settlement via Chainlink CRE.
* **Highlights**: Bespoke `CRESettlementOracle.sol` bridging off-chain LLM verification into trustless on-chain resolution.
* **Takeaway**: Leading the "AI x Blockchain" design space with trustless settlement mechanisms.

---

## 🧠 What I Care About

- **Devtools that don't suck** — if a protocol is hard to debug or profile, I'll build the tool that fixes that
- **Privacy as a primitive** — not an afterthought
- **Making hard things legible** — writing and speaking about ZK, Rust, and on-chain systems so other engineers can move faster
- **Protocol engineering** — I care about what's happening at the consensus and execution layer, not just the application layer

---

## ✍🏾 Writing

I write deep technical content on [Medium](https://intellidean.medium.com/) covering:

- Zero-knowledge proofs and their real-world tradeoffs  
- Rust performance patterns for blockchain systems  
- Decentralised architecture and protocol design  

---

## 🛠️ Stack

| Category | Technologies |
| :--- | :--- |
| **Languages** | `Rust (Nightly/Stable)` `Java 21/25/26` `Solidity` `Cairo` `TypeScript` `Python` `Go` |
| **Chains & Protocols**| `ISO 8583:1987 (Visa/MC)` `Ethereum` `Arbitrum (Stylus)` `Starknet` `Solana` `Nervos (Fiber)` `Zcash` |
| **Architectures** | `Distributed Microservices (12-Factor)` `Protocol Engineering` `Financial Switching` `Devtooling` `ZK Research` |
| **Data & Core** | `Apache Kafka (KRaft)` `PostgreSQL` `Redis` `RocksDB` `SQLite (WAL)` `Diesel` `Docker` `Zipkin` `gRPC` |

---

## 📈 GitHub Stats

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=intelliDean&layout=compact&theme=dark&cache_seconds=1800)

---

## 🤝 Let's Connect

I'm actively looking to **collaborate** with teams, L1/L2s, and dev tooling companies where I can bridge deep technical work and expertise.

[![Twitter](https://img.shields.io/badge/@dean8ix-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/dean8ix)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/michaeldean8ix)
[![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://intellidean.medium.com/)
[![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=firefox&logoColor=white)](https://dean8ix.vercel.app/)
[![Resume](https://img.shields.io/badge/Resume-FF5722?style=for-the-badge&logo=firefox&logoColor=white)](https://flowcv.com/resume/gnsu9bqkm4)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:o.michaeldean@gmail.com)
[![Linktr](https://img.shields.io/badge/Linktr-FF5722?style=for-the-badge&logo=firefox&logoColor=white)](https://linktr.ee/dean8ix)
