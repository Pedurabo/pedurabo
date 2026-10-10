# Hi, I'm Joshua Wabulo 👋

**Computer Scientist & Software Engineer | Android | Applied AI/ML**

I'm a Computer Scientist and Software Engineer working across software systems, applied AI/ML, and native Android engineering. I build production-oriented software with a strong focus on reliable mobile architecture, offline-first state, durable background work, realtime consistency, camera-assisted experiences, secure authentication, and systems that continue to behave correctly when networks, processes, or external services fail.

My recent work spans resilient Android systems, tele-rehabilitation, Web3 payments, document intelligence, applied AI/ML, backend/data systems, and reliability-focused software architecture.

Computer Scientist and Software Engineer based in Uganda 🇺🇬, with a BSc in Computer Science and currently completing an MSc in Information Technology. Open to remote software engineering, computer science, Android, and applied AI/ML opportunities.

## 🚀 Featured Projects

### [Relay](https://github.com/Pedurabo/Relay)
Resilient realtime incident-coordination Android application designed around failure recovery, exactly-once effects, and local/server convergence.

- Kotlin + Jetpack Compose native Android client with Room-backed durable state
- Ordered WebSocket event processing with durable sequence-gap detection, replay, and reconnect recovery
- Durable handling of out-of-order incident updates and timeline events across process death
- Production replay seams for input collection, reconciliation policy, execution, job registration, ownership, and cancellation barriers
- Generation-safe replay-job replacement so stale coroutine cleanup cannot delete newer owners
- Durable outboxes, stable idempotency keys, delivery leases, bounded retry backoff, and queue fairness
- Session-bound command ownership and cross-account isolation
- Modular `core:model`, `core:session`, `core:database`, `core:realtime`, `core:notifications`, and `feature:incidents` architecture
- Structured realtime/outbox diagnostics plus release endpoint, CI, minification, resource-shrinking, and optional signing hardening
- Accessibility, keyboard-flow, loading/empty-state, and incident/timeline UX hardening validated on a physical Android 13 device
- Room schema migration coverage through version 15 plus deterministic unit/instrumentation regression tests

**Stack:** Kotlin • Jetpack Compose • Room • Coroutines/Flow • OkHttp WebSockets • Firebase • Node.js • SQLite

---

### [TeleRehab](https://github.com/Pedurabo/TeleRehab)
Native Android tele-rehabilitation system for therapist-managed exercise programs, guided camera sessions, patient progress, and reliable local-first session handling.

- Therapist and patient email/password authentication
- Therapist-managed patient provisioning and exercise assignment
- Guided **Seated Knee Extension** sessions using CameraX + ML Kit pose landmarks
- Repetition and knee-angle range tracking with therapist and patient progress views
- Room-backed local persistence with WorkManager session synchronization
- Patient-scoped sync, retryable auth-loss handling, terminal-only uploads, and multi-batch draining
- Explicit interruption, restart recovery, concurrent-session prevention, and finish/back race protection
- End-to-end patient and therapist regression validation on a physical Android device
- MVP validated with unit, ViewModel, and Firestore security-rule testing; release variant builds (distribution signing pending)

**Stack:** Kotlin • Jetpack Compose • Room • WorkManager • Firebase Auth • Cloud Firestore • CameraX • ML Kit • Hilt

---

### [ChainPay](https://github.com/Pedurabo/ChainPay)
Native Android Web3 payment application for wallet connectivity, Sepolia payments, transaction recovery, and merchant QR checkout.

- Reown AppKit / WalletConnect session integration
- Ethereum Mainnet ETH/USDC balance reads and recent transaction history
- Sepolia ETH payment requests with persisted submitted-transaction recovery
- Receipt polling with confirmed/reverted/timeout handling
- Merchant Mode with ERC-681 payment URIs and QR codes
- HTTPS-only release networking, disabled backups, sanitized errors, and debug-only diagnostics

**Stack:** Kotlin • Jetpack Compose • Reown AppKit • WalletConnect • Ethereum JSON-RPC • ERC-20 • ERC-681 • ZXing

---

### [ContractLens](https://github.com/Pedurabo/ContractLens)
AI contract-analysis platform focused on grounded answers and independently verifiable source evidence.

- PDF and DOCX ingestion
- Streaming contract Q&A and saved chat history
- Deterministic citation verification with source navigation/highlighting
- Multi-document Q&A and clause-level comparison
- Bounded document-research workflows with graceful provider-failure fallbacks

**Stack:** Next.js • React • TypeScript • Gemini API • Prisma • PostgreSQL

---

### [FinSight](https://github.com/Pedurabo/Finsight)
Provenance-aware financial-document QA workbench for evidence-backed numerical reasoning.

- Financial evidence extraction, retrieval, reconciliation, and verification
- Deterministic calculations with period/unit consistency checks
- Source-page citations and provenance preservation
- Conservative abstention for missing, conflicting, ambiguous, or unsafe evidence
- Regression evaluation using Microsoft FY2024/FY2025 financial materials

**Stack:** Python • TypeScript • React • retrieval • financial reasoning • evidence verification

---

### [SignalDesk](https://github.com/Pedurabo/Signaldesk)
Offline-capable incident-management system with a native Android client and Kotlin/Spring Boot backend.

- Jetpack Compose Android UI with Room-backed local persistence
- Offline mutation outbox and WorkManager synchronization
- Observable retry and sync state
- Spring Boot REST API with PostgreSQL + Flyway
- Signed Android release builds, Dockerized backend, and layered testing

**Stack:** Kotlin • Jetpack Compose • Room • WorkManager • Spring Boot • PostgreSQL • Flyway • Docker

---

## 🛠️ Core Technologies

**Android & Mobile**  
Kotlin • Jetpack Compose • Room • WorkManager • Coroutines/Flow • CameraX • ML Kit • Firebase • WebSockets • WalletConnect

**Architecture & Reliability**  
Offline-first design • local-first state • durable outboxes • idempotent synchronization • process-death recovery • sequence-gap replay • cancellation barriers • generation-safe coroutine ownership • deterministic validation • role-based authorization

**Backend & Web**  
Node.js • TypeScript • Express • Next.js • React • Spring Boot • REST APIs • PostgreSQL • Prisma • Flyway • Docker

**AI / Data**  
Python • Gemini API • PyTorch • scikit-learn • Transformers • NLP • computer vision • retrieval pipelines • evidence verification

**Web3 / Payments**  
Ethereum JSON-RPC • Reown AppKit • WalletConnect • ERC-20 • ERC-681 • merchant payment flows

**Engineering Practices**  
Unit and integration testing • coroutine testing • Room migration testing • Firebase rules testing • regression testing • physical-device validation • release hardening • Git/GitHub

## 🧠 Computer Science & Research

My broader computer science interests include software architecture, algorithms, distributed/realtime systems, data-intensive applications, applied AI/ML, computer vision, and dependable software engineering. My MSc work explores AI-assisted mobile tele-rehabilitation, connecting research with practical Android engineering.

## 📈 Current Focus

- Growing as a Computer Scientist and Software Engineer while deepening production Android expertise
- Building resilient local-first and realtime Android systems
- Advancing Relay from reliability hardening into product-quality, UX, observability, and release-readiness validation
- Camera-assisted and sensor-driven mobile experiences
- Session lifecycle correctness, background work, and reliable synchronization
- Applied AI systems with verifiable evidence and deterministic reasoning
- Stronger automated testing, release readiness, and physical-device validation

## 📫 Connect

- GitHub: [github.com/Pedurabo](https://github.com/Pedurabo)
- LinkedIn: [Joshua Wabulo](https://www.linkedin.com/in/joshua-wabulo-025894275/)
- X: [@tobeyjos1](https://x.com/tobeyjos1)
- Portfolio / links: [linktr.ee/Tobjos](https://linktr.ee/Tobjos)

---

I'm interested in Computer Science and Software Engineering roles where strong fundamentals, reliability, architecture, applied AI, and real-world usability matter.
