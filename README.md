# Hi there, I'm Joel Lalruatkima 

Full-Stack & Mobile Engineer specializing in high-concurrency cross-platform applications (Flutter), production RAG pipelines (FastAPI, Qdrant, pgvector), financial payment systems, and client-side cryptography.

[![GitHub](https://img.shields.io/badge/GitHub-joelaah-181717?style=flat-square&logo=github)](https://github.com/joelaah)
[![Email](https://img.shields.io/badge/Email-joelapachuau64%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:joelapachuau64@gmail.com)
[![Location](https://img.shields.io/badge/Location-Aizawl%2C%20India-blue?style=flat-square)](https://maps.google.com)

---

##  Featured Flagship Projects

###  [PulseFit AI – Fitness Marketplace, Two-Stage RAG & E2EE Chat](https://joelaah.github.io/fitness_app/)
**[🌐 Live Demo](https://joelaah.github.io/fitness_app/)** | **[📱 Flutter Client Repo](https://github.com/joelaah/fitness_app)** | **[⚡ FastAPI RAG Backend Repo](https://github.com/joelaah/fitness-rag-api)** | **[🛡️ Security & Testing Case Study](https://github.com/joelaah/fitness_app/blob/main/MARKETPLACE_SECURITY_AND_TESTING.md)**

*Enterprise-grade fitness marketplace, real-time AI copilot, and encrypted communication engine backed by 484 automated tests passing 100%.*

- **Signal-Protocol E2EE Real-Time Chat**: Client-side X25519 ECDH key agreement, HKDF-SHA256 derivation, and AES-256-GCM authenticated encryption with 96-bit nonces. Zero-knowledge database storage where the server never sees plaintext.
- **Razorpay Route Split Payments**: Dynamic 10% platform fee deduction with dual-layer idempotency (in-memory lock manager + PostgreSQL 23505 collision handling) guaranteeing zero double-charges on retries.
- **Two-Stage RAG Intelligence**: Qdrant Cloud HNSW vector search (768-dim embeddings via Google GenAI) paired with Cohere Cross-Encoder (`rerank-v3.5`) reranking and deterministic Python math guardrails.
- **High-Concurrency Benchmarking**: Stress-tested under a 500-user Locust swarm achieving 676.2 req/s with 99.96% success rate and 160ms median latency.

---

### 🔍 [JOB SeArCh – Autonomous Semantic Job Hunter & Matcher](https://joelaah.github.io/Job-Searcher/)
**[🌐 Live Web Application](https://joelaah.github.io/Job-Searcher/)** | **[💻 Source Code](https://github.com/joelaah/Job-Searcher)**

*Intelligent, privacy-first career discovery and automated application system projecting resumes and live postings into a 768-dimensional latent vector space.*

- **Semantic Matching Engine**: Supabase `pgvector` HNSW indexing with FastEmbed 768-dim embeddings, Groq LLM inference, and reinforcement learning match scoring.
- **Zero-Knowledge RAM Vault**: Privacy-isolated, in-memory credential storage protecting candidate data during automated ATS form filling.
- **Reactive UI**: Marine Glassmorphism Bento Grid built with Flutter Web and reactive BLoC state management.

---

## 📂 Production & Systems Work

- **🛡️ [Compliance Checker](https://github.com/joelaah/compliance-checker)**: Automated compliance and policy verification engine with deterministic rule validation and audit trail telemetry.
- **🎥 Video Streaming App**: Cross-platform Flutter platform with Vimeo video streaming, Stripe checkout, and Firebase backend.
- **💰 [Finance Tracker](https://github.com/joelaah/finance_tracker)**: Offline-first expense tracker with interactive data visualization and budget analytics.
- **📰 [FlutterNews](https://github.com/joelaah/flutternews)**: Swipeable, responsive news reader with dynamic topic categorization.

---

## 🛠️ Technical Arsenal

- **Languages:** Dart, Python 3.12, SQL (PostgreSQL), JavaScript/TypeScript
- **Frontend & Mobile:** Flutter (Web, iOS, Android), BLoC Pattern, Provider, CanvasKit, PWA
- **AI, RAG & Vectors:** Qdrant Cloud HNSW, Supabase `pgvector`, Google Gemini, Cohere Rerank, FastEmbed
- **Backend & Cloud:** FastAPI, Supabase (PostgreSQL, Triggers, RLS), Docker, Render, RESTful APIs
- **Security & Payments:** Signal Protocol (X25519 ECDH + AES-256-GCM), Razorpay Route Split, HMAC-SHA256, Zero-Knowledge Storage

---

*Open to Full-Stack Engineering roles and AI/mobile architecture opportunities.*
