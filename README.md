# Marcus Girolneto

### Specialist Software Engineer · Protocol Engineer
**Backend & distributed systems · Blockchain infrastructure · AI security**

I build and operate software for financial applications, blockchain networks and AI security. My work spans hands-on product engineering, protocol development, production reliability and technical leadership.

At Constellation Network, I created Constellation Gate, an AI security gateway, and later led its engineering team. In parallel, I work on Tessellation, the network's core Scala protocol, and the production infrastructure around it. Previously, I helped lead a monolith-to-microservices modernization at PagBank.

**Based in Brazil · Fluent English · Open to remote opportunities with international teams**

[LinkedIn](https://www.linkedin.com/in/marcusgirolneto/) · [Email](mailto:marcus.girolneto@gmail.com)

---

## Selected impact

### Constellation Network · Specialist Software Engineer & Protocol Engineer

**AI security product — Constellation Gate**
- Created the product from the ground up, owning architecture, software, infrastructure and database; later led the team as it grew.
- Built a multi-tenant security gateway for AI applications and agents, with prompt-injection detection, sensitive-data scanning, prompt compression, response caching and verifiable audit records.
- Co-authored the public [Gate AI LLM Security Benchmark](https://constellationnetwork.io/papers/gate-ai-prompt-injection-benchmark.pdf): 97.4% F1 at a 1% false-positive rate across 16 public benchmarks (12,111 samples), ranking first on 8 datasets against published competitors.

**Blockchain protocol & network reliability**
- Contributed **267 merged pull requests** to [Tessellation](https://github.com/Constellation-Labs/tessellation), Constellation's core Scala protocol, across consensus, snapshot recovery, L1 sync, state proofs, delegated staking and Merkle Patricia Trie performance.
- Contributed **627 merged pull requests** across Constellation-Labs public repositories (2022–2026), spanning protocol engineering, metagraph applications, developer tooling and network operations.
- Built and operated production metagraphs and deployment, monitoring, auto-restart and snapshot-streaming tools; worked directly with node operators and partner teams.
- Investigated production failures, including a mainnet restart loop, and delivered recovery and release fixes.

### Earlier experience

At **PagBank**, helped lead the modernization of a monolithic application into microservices and worked across implementation, deployment and maintenance with Node.js, TypeScript, Java, Kotlin, Micronaut and Jenkins. Earlier roles at Saipos and ZG Soluções included product development, automated testing, customer issue resolution and relational database query optimization.

---

## Selected projects

These independent projects demonstrate backend design, data integrity, concurrency, security and operational thinking. Each repository includes setup instructions, design decisions and tests.

| Project | What it demonstrates |
| --- | --- |
| [**Ledger**](https://github.com/marcus-girolneto/ledger) | Double-entry accounting service. PostgreSQL enforces balanced postings, immutable history and balance rules; idempotency and concurrency tests cover duplicate requests and competing withdrawals. TypeScript, Fastify, PostgreSQL, React. |
| [**Hookrelay**](https://github.com/marcus-girolneto/hookrelay) | Durable webhook delivery with HMAC signatures, idempotency, retries with jitter, dead-letter replay and multi-instance workers using PostgreSQL `SKIP LOCKED`. Go. |
| [**Witness**](https://github.com/marcus-girolneto/witness) | Tamper-evident transparency log with RFC 6962 Merkle proofs, Ed25519 signed checkpoints, crash-safe storage and a monitor for forks and split views. Go. |
| [**Beacon**](https://github.com/marcus-girolneto/beacon) | Privacy-friendly event collection with batching, backpressure, PostgreSQL `COPY` and attribution. Go. |
| [**Linkpulse**](https://github.com/marcus-girolneto/linkpulse) | Concurrent broken-link checker with per-host rate limits, robots.txt support and CI-ready reports. Go. |
| [**Audit Trail Lab**](https://github.com/marcus-girolneto/audit-trail-lab) | Hash-chained audit records, trusted checkpoints and adversarial verification tests. TypeScript. |

---

## Technical focus

**Backend & languages:** Scala, TypeScript, Go, Node.js, Java, Kotlin  
**Distributed systems:** consensus, concurrency, retries, idempotency, event pipelines  
**Data:** PostgreSQL, MySQL, Oracle, NoSQL  
**Cloud & delivery:** AWS, Docker, Ansible, CI/CD, GitHub Actions  
**Product engineering:** React, APIs, microservices, automated testing, production operations

## Education

**B.S. in Computer Engineering**, Pontifícia Universidade Católica de Goiás (PUC-GO).

Most of my professional work lives in employer-owned repositories. This profile describes my contributions without exposing proprietary code or internal data.

---

**Interested in backend, protocol, distributed systems or AI security roles?** [Get in touch](https://www.linkedin.com/in/marcusgirolneto/).
