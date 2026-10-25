# Hi, I'm Akshay Mundra 👋

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/akshaymundra)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/akshaymundra)
[![Email](https://img.shields.io/badge/Email-akshay.mundra08@gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:akshay.mundra08@gmail.com)

Backend engineer with 2+ years of experience building scalable, event-driven distributed systems using **Golang, Node.js, and AWS**. Focused on high-concurrency event pipelines, data consistency under concurrent writes, query optimization, and production AI/RAG integrations.

---

### ⚡ What I Do

- **Distributed Systems & Event Pipelines**: Architecting high-throughput fan-out pipelines using SQS, SNS, and Go worker pools with idempotent, atomic state transitions.
- **Performance & Latency Optimization**: Tuning database access patterns and query paths (cut production p95 API latency by 86% on DynamoDB).
- **Concurrency & Data Consistency**: Eliminating race conditions and duplicate processing using Redis distributed locking, conditional writes, and exponential backoff with jitter.
- **Search & Applied AI**: Designing hybrid RAG pipelines combining lexical search (BM25) and dense vector embeddings (pgvector, local vector stores) reranked via Reciprocal Rank Fusion (RRF).

---

### 🛠 Tech Stack

| Domain | Technologies |
| :--- | :--- |
| **Languages** | Go, TypeScript, JavaScript, Python, Bash |
| **Backend & APIs** | Node.js, NestJS, Express.js, RESTful APIs, gRPC, Protobuf, WebSockets, SSE |
| **Databases & Caching** | PostgreSQL, DynamoDB, Redis, pgvector, MySQL, Prisma ORM |
| **Cloud & DevOps** | AWS (Lambda, SQS, SNS, S3, CloudWatch, EC2, RDS), Docker, CI/CD, Linux |
| **System Design** | Distributed Locking, Event Fan-out, Idempotent Consumers, RBAC, Multi-tenant Isolation |
| **AI & Retrieval** | Hybrid RAG, BM25 Lexical Search, Vector Embeddings, Reciprocal Rank Fusion (RRF), LLM APIs |

---

### 🚀 Engineering Highlights

- **Event-Driven Processing**: Built an SNS to SQS fan-out pipeline with Go worker pools for a high-volume gaming engagement platform. Handled at-least-once delivery with atomic multi-table updates to guarantee zero duplicate payouts on retries.
- **Sub-Second Batch Ingestion**: Optimized an enterprise bulk CSV ingestion engine from 10 minutes down to 3 to 5 seconds per 1,000 records using BullMQ worker queues, batching, and multi-tier caching.
- **Production Query Tuning**: Reduced an API endpoint p95 latency from 1.5s to 200ms (86% drop monitored in Datadog) by restructuring filtered queries into targeted Global Secondary Indexes (GSI).
- **Zero Data Loss Concurrency**: Eliminated lost-update race conditions between live write APIs and validation crons through Redis distributed locks and conditional database writes.
- **Multi-Tenant Security & Reliability**: Audited microservices architectures, resolved critical multi-tenant data leakage risks, and standardized schema migration pipelines across staging and production environments.

---

### 🔍 Featured Projects

#### [PageLens](https://github.com/akshaymundra/PageLens) (AI Web Page Assistant)
*TypeScript, Vite, Chrome Extension MV3, Shadow DOM, Hybrid RAG, BM25, Vector Embeddings, Ollama / Claude / OpenAI*
- Manifest V3 extension providing in-page streaming Q&A against live web documents.
- Features hybrid retrieval: merges sparse BM25 search with dense local vector embeddings via Reciprocal Rank Fusion (RRF) to optimize LLM context window tokens and latency.
- Renders an isolated Shadow DOM to avoid host stylesheet bleed and processes background jobs inside MV3 Service Workers.

#### Enterprise RAG & Workforce Assistant
*Node.js, Express.js, PostgreSQL, pgvector, Redis, Docker*
- Semantic retrieval assistant indexing internal enterprise documentation and company policies.
- Built an automated ingestion and chunking pipeline with vector similarity search feeding precision context to LLM completions.

---

### 📈 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=akshaymundra&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="Akshay's GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=akshaymundra&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" />
</p>

---

### 📫 Connect With Me

- **Email**: [akshay.mundra08@gmail.com](mailto:akshay.mundra08@gmail.com)
- **LinkedIn**: [linkedin.com/in/akshaymundra](https://linkedin.com/in/akshaymundra)
- **GitHub**: [github.com/akshaymundra](https://github.com/akshaymundra)
