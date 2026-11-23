# Manthan Moharana

**Backend & Systems Software Engineer | Python · FastAPI · PostgreSQL · Docker · Linux**

Software Engineer (B.Tech CS) focused on asynchronous backend architectures, distributed task processing, containerized Linux deployments, and automated data/API validation. Currently building low-latency, zero-egress edge telemetry and backend pipelines at **GarageBy Technologies** (STPI / MeitY Pre-Incubated).

- **Algorithmic Foundation:** Cleared Google Foobar Challenge (Level 2) · HackerRank Python Gold Badge
- **Core Stack:** Python (`asyncio`, FastAPI, Celery, Pytest), SQL (PostgreSQL), Redis (Connection Pooling & Lua Scripting), Docker, NGINX, AWS (EC2, RDS, S3), Linux (Ubuntu)

---

### Selected Systems & Backend Architecture

#### 1. High-Throughput Distributed Routing Engine (`qa-routing-engine`)
- **Architecture:** Asynchronous FastAPI ingress layer backed by `aioredis` connection pooling and decoupled Celery worker queues for background compute offloading.
- **Reliability & Testing:** Atomic Token-Bucket rate limiting via in-memory Redis Lua scripts to prevent race conditions under concurrent load, paired with automated `pytest` functional and edge-case test suites.

#### 2. Production Social Platform Backend (`socialmedia-backend`)
- **Architecture:** RESTful service built with FastAPI and normalized PostgreSQL schemas enforcing strict ACID transaction boundaries and JWT authentication.
- **Infrastructure:** Containerized via Docker with automated GitHub Actions CI/CD pipelines and reverse-proxied through NGINX on AWS EC2.

#### 3. Contextual RAG & Vector Retrieval Pipeline (`rag-pdf-chatbot`)
- **Architecture:** Document ingestion and semantic retrieval service utilizing Python, FastAPI, structured chunking pipelines, and ChromaDB vector indexing for context-bounded query resolution.

#### 4. Low-Latency WebRTC Signaling Server (`zoom-clone`)
- **Architecture:** Event-driven WebRTC signaling state machine and peer-to-peer media session negotiation built with TypeScript, Node.js, and Socket.io.

---

### Connect
- **Portfolio:** [manthanmoharana.click](https://manthanmoharana.click)
- **LinkedIn:** [://linkedin.com](https://www.://linkedin.com/)
- **Email:** manthanmoharana03583@gmail.com
