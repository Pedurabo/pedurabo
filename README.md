# Hi, I'm Joshua Wabulo 👋

**Android & Software Engineer | Kotlin • Jetpack Compose • Offline-first systems • TypeScript • Python**

I build practical, production-oriented software with a strong current focus on native Android engineering: reliable mobile architecture, local-first data flows, camera/sensor-driven experiences, realtime consistency, secure authentication, and systems that behave predictably when networks or external services fail.

I also work across backend systems, document intelligence, Web3 integrations, and applied AI.

Computer Science professional based in Uganda 🇺🇬 and open to remote software engineering opportunities.

## 🚀 Featured Projects

### [TeleRehab](https://github.com/Pedurabo/TeleRehab)
Native Android tele-rehabilitation application for therapist-managed exercise programs, stable patient onboarding, guided camera sessions, adherence tracking, and local-first rehabilitation data.

- Kotlin + Jetpack Compose Android client
- Therapist and patient email/password authentication
- Therapist-managed patient provisioning with generated temporary credentials
- Firestore role and relationship rules with emulator-tested authorization
- Therapist-created Knee Flexion assignments
- Guided rehabilitation sessions with camera-based pose analysis
- Repetition and flexion/extension threshold tracking
- Room-backed local state and WorkManager-oriented synchronization
- Patient history, progress comparison, and therapist adherence summaries
- Physical-device validation on Android

**Stack:** Kotlin • Jetpack Compose • Room • WorkManager • Firebase Auth • Cloud Firestore • CameraX • Hilt

---

### [ChainPay](https://github.com/Pedurabo/ChainPay)
Native Android Web3 payment application for wallet connectivity, Sepolia ETH payments, merchant payment requests, QR-based ERC-681 checkout, and direct on-chain transaction confirmation.

- Kotlin + Jetpack Compose Android client
- Reown AppKit / WalletConnect session integration
- Wallet connection and account-aware payment flows
- Ethereum Mainnet ETH and USDC balance reads
- Recent Ethereum transaction history
- Sepolia ETH payment requests with explicit chain binding
- Merchant receive mode with amount, recipient, and reference
- ERC-681 payment URI generation with QR codes
- Persistent merchant requests across navigation
- Direct Sepolia `eth_getTransactionReceipt` verification
- Wallet-return transaction hash capture and payment confirmation
- Explorer links, transaction hash copy, and payment reset flows
- Physical-device validation with SafePal

**Stack:** Kotlin • Jetpack Compose • Reown AppKit / WalletConnect • Ethereum JSON-RPC • ERC-20 • ERC-681 • ZXing

---

### [Relay](https://github.com/Pedurabo/Relay)
Real-time incident coordination Android application focused on correctness across unreliable networks, retries, reconnects, process death, and account changes.

- Kotlin + Jetpack Compose native Android client
- Room-backed incident, timeline, sequence-gap, and command persistence
- WebSocket realtime updates with ordered event processing and active replay
- Durable severity-command outbox with stable idempotency keys
- Atomic delivery leases with abandoned-lease recovery after process death
- Exponential retry backoff with cross-incident queue fairness
- Optimistic updates that converge to authoritative server state
- Session-bound command ownership with proven cross-account isolation
- Background severity-aware incident notifications
- Deterministic physical-device failure-mode validation

**Stack:** Kotlin • Jetpack Compose • Room • Coroutines/Flow • OkHttp WebSockets • Node.js

---

### [FinSight](https://github.com/Pedurabo/Finsight)
Evidence-aware financial document analysis project for extracting, reconciling, verifying, and calculating financial information from source documents.

- Supports Revenue, Operating Income, Net Income, Gross Margin, Assets, Liabilities, and Equity
- Handles same-scope and cross-scope arithmetic
- Reconciles original vs. restated evidence
- Preserves provenance across embedded text and OCR
- Normalizes compatible currencies and financial scales
- Uses structured abstention when evidence is missing, conflicting, ambiguous, or unsafe
- Includes automated evidence and regression coverage
- Uses real financial documents for regression-oriented validation

**Stack:** TypeScript • Express • document extraction • financial evidence reconciliation • automated testing

---

### [ContractLens](https://github.com/Pedurabo/ContractLens)
AI contract analysis platform focused on grounded answers, verified evidence, multi-document reasoning, clause-level comparison, and document research.

- PDF and DOCX ingestion
- Large-document chunking and retrieval
- Streaming contract Q&A
- Independently verified citations with source highlighting
- Multi-document comparative analysis
- Clause-level comparison
- Bounded multi-round research workflows
- PostgreSQL persistence with Prisma
- Graceful provider-failure fallbacks

**Stack:** Next.js • React • TypeScript • Gemini API • Prisma • PostgreSQL • Tailwind CSS

---

### [SignalDesk](https://github.com/Pedurabo/Signaldesk)
Offline-capable incident management system centered on a native Android client with a Kotlin/Spring Boot backend.

- Jetpack Compose Android UI
- Room-backed offline persistence
- Offline mutation outbox
- WorkManager background synchronization
- Observable retry and sync state
- Spring Boot REST API
- PostgreSQL + Flyway
- Signed Android release builds
- Dockerized backend
- Automated and physical-device testing

**Stack:** Kotlin • Jetpack Compose • Room • WorkManager • Spring Boot • PostgreSQL • Flyway • Docker

---

### [Tourism Mobile App](https://github.com/Pedurabo/Tourism-Mobile-App)
Native Android tourism application covering discovery, bookings, hotels, flights, cars, landmarks, maps, notifications, profile, administrative workflows, and local Room persistence.

**Stack:** Kotlin • Jetpack Compose • Material 3 • Navigation Compose • Room • ViewModel • Coil

---

## 📊 Additional Data / ML Work

### [MITSUI & CO. Commodity Prediction Challenge](https://github.com/Pedurabo/MITSUI-CO.-Commodity-Prediction-Challenge)
Multi-target commodity and financial-market forecasting project with feature engineering, time-series cross-validation, ensemble methods, and model pipelines spanning LightGBM, XGBoost, CatBoost, Random Forest, and Ridge regression.

---

## 🛠️ Core Technologies

**Android & Mobile**  
Kotlin • Jetpack Compose • Room • WorkManager • Coroutines/Flow • CameraX • Firebase • WebSockets • WalletConnect • Google Maps

**Architecture & Reliability**  
Offline-first design • local-first data flows • durable outboxes • idempotent synchronization • process-death recovery • deterministic validation • role-based authorization

**Backend & Web**  
TypeScript • Express • Next.js • React • Spring Boot • Node.js • REST APIs • PostgreSQL • Prisma • Flyway • Docker

**Web3 / Blockchain**  
Ethereum JSON-RPC • Reown AppKit • WalletConnect • ERC-20 • ERC-681 • wallet transactions • merchant payment flows

**AI / Data**  
Python • Gemini API • ML Kit • LightGBM • XGBoost • retrieval pipelines • evidence verification

**Engineering Practices**  
Unit and integration testing • Firebase rules testing • regression testing • physical-device validation • provenance tracking • release hardening • Git/GitHub

## 📈 Current Focus

- Becoming an exceptional production Android engineer through complete, real-world applications
- Building local-first Android systems that remain reliable across poor connectivity and process death
- Camera-, sensor-, and realtime-driven mobile experiences
- Secure identity, role, and synchronization architecture
- Deepening automated testing and physical-device validation
- Continuing selected backend, document-intelligence, Web3, and applied-data projects

## 📫 Connect

- GitHub: [github.com/Pedurabo](https://github.com/Pedurabo)
- LinkedIn: [Joshua Wabulo](https://www.linkedin.com/in/joshua-wabulo-025894275/)
- X: [@tobeyjos1](https://x.com/tobeyjos1)
- Portfolio / links: [linktr.ee/Tobjos](https://linktr.ee/Tobjos)

---

I’m interested in Android and software engineering work where reliability, architecture, and real-world usability matter.
