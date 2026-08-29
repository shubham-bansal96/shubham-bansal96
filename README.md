# 👋 Hi, I'm Shubham Bansal!

**Senior Software Engineer | Golang | Cloud Native**

🚀 Welcome to my GitHub! I'm a passionate **software engineer** with **9 years** of experience in building distributed scalable applications using Golang.

---

## 🛠️ Tech Stack & Skills

- **Programming & Frameworks:** Go (Golang), REST APIs, WebSockets, Temporal, LangChain, C#
- **Distributed Systems & Messaging:** Event-driven architecture, Kafka, Distributed workflows, Microservices
- **Container Orchestration & Infrastructure:** Kubernetes, Helm, Docker, developing custom Kubernetes Operators and Controllers using kubebuilder & operator SDK
- **Databases:** MySql
- **CI/CD & DevOps:** GitHub Actions, GitLab CI/CD
- **Monitoring & Observability:** Prometheus, Grafana, OpenTelemetry, Sumologic
- **Cloud:** AWS(KMS, S3, CloudWatch, Secrets Manager, Route 53)
- **Security:** OAuth, JWT, secure service-to-service communication
- **AI:** Claude, Agentic AI, GitHub Copilot, LangChain, Retrieval-Augmented Generation (RAG)‚ and actively leveraging AI tooling to enhance development velocity and code quality
- **Operating Systems:** Linux, macOS, Windows

---

## 📚 Open-Source Contribution

### 📦 [Fission](https://github.com/fission/fission) — [60+ PRs merged](https://github.com/fission/fission/pulls?q=is%3Apr+author%3Ashubham-bansal96+is%3Aclosed+sort%3Acomments-desc)
**Fission is an open-source, Kubernetes-native serverless framework that simplifies the deployment of functions and applications on Kubernetes.**
- Implemented **multi-namespace support** across executor, builder manager, logger, and kube watcher — enabling namespace-scoped informers and RBAC for isolated multi-tenant deployments
- Integrated **OpenTelemetry** tracing and metrics into executor and MQ trigger connectors (e.g. Kafka message lag metric)
- Improved **security posture** — Alpine upgrades, GHCR migration, scoped RBAC roles for function/builder namespaces, and authentication fixes
- Enhanced **Helm chart releases** — version bumps, dependency upgrades, Prometheus integration, and fixes for upgrade-path issues
- Fixed critical bugs: package stuck in pending state, namespace resolution, idle-timeout pod termination, configmap-triggered pod restarts, and CLI robustness improvements
- Strengthened **CI/CD pipeline** — backward-compatibility test jobs, integration test fixes, and cleanup improvements

## 📚 Personal Projects

### 📦 [doc-qa](https://github.com/shubham-bansal96/doc-qa)
**An intelligent Retrieval Augmented Generation (RAG) system built in Go using LangChainGo — ingest documents and ask natural language questions with AI-generated answers grounded in your data.**
- **Multi-format ingestion** — supports `.txt`, `.md`, `.csv`, `.html`, `.pdf`, and images (`.png`, `.jpg`, `.gif`, `.webp`) with hybrid PDF handling and Tesseract OCR + Llava vision model fallback
- **Local-first architecture** — embeddings run entirely on-device via Ollama (`nomic-embed-text`); Qdrant vector DB for similarity search with cosine distance scoring
- **Conversational memory** — session-based follow-up questions with automatic query rewriting for better retrieval context
- **Source attribution** — every answer includes references to the source document chunks used, powered by Anthropic Claude

### 📦 [ms-url-shortner](https://github.com/shubham-bansal96/ms-url-shortner)
**A lightweight URL Shortener microservice built in Go with Gin, designed for production-grade Kubernetes deployments.**
- REST API with 8-character unique ID generation, in-memory caching, and input validation
- Prometheus metrics, rate limiting middleware, structured logging (Logrus), and pprof profiling
- Multi-stage Docker build and Helm chart with HPA, ServiceMonitor, and configurable replicas
- Swagger-documented API with comprehensive unit tests and Makefile automation

---

## 🤝 Let's Connect!

- 💼 **LinkedIn:** [Shubham Bansal](https://www.linkedin.com/in/shubham-bansal-b5b799129/)
