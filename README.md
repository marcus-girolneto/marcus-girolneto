# Marcus Girolneto Sousa

### Senior Software Engineer · Backend, Distributed Systems & AI Security

I build backend systems that have to stay correct under load and under attack: payments, distributed protocols and AI security. Nine years in, I still write code every day and I also lead.

At **Constellation Network** (2022–2026) I designed and built **Constellation Gate** from zero, a multi-tenant security gateway for LLM applications and AI agents, and then led its engineering team. I co-authored its public benchmark: **97.4% F1 at a 1% false-positive rate** across 16 datasets, first on 8 of them against published competitors. In parallel I worked on the network's core Scala consensus protocol and handled incidents on a live network. Before that I helped lead a monolith-to-microservices migration at **PagBank**.

I'm currently building **Akibo**, an AI personal-finance assistant (closed source, see below).

**Brazil (UTC-3) · Fluent English · Open to senior backend, platform and AI infrastructure roles, remote or relocation**

[LinkedIn](https://www.linkedin.com/in/marcusgirolneto/) · [Email](mailto:marcus.girolneto@gmail.com) · [Gate AI benchmark paper](https://constellationnetwork.io/papers/gate-ai-prompt-injection-benchmark.pdf)

---

## What I work on

**Correctness and data integrity.** Double-entry invariants enforced by the database, idempotent writes, concurrency tests that try to break balances.

**Reliability under failure.** Retries with jitter, dead-letter replay, multi-instance workers, crash-safe storage, state recovery on a live network.

**Security for AI systems.** Prompt-injection defense, sensitive-data scanning, verifiable audit trails, permission testing for agents.

---

## Independent projects

Each repository has setup instructions, design notes and tests.

| Project | What it demonstrates | Stack |
| --- | --- | --- |
| [**Ledger**](https://github.com/marcus-girolneto/ledger) | Double-entry accounting service. PostgreSQL enforces balanced postings and immutable history; idempotency and concurrency tests cover duplicate requests and competing withdrawals. | TypeScript, Fastify, PostgreSQL |
| [**Hookrelay**](https://github.com/marcus-girolneto/hookrelay) | Durable webhook delivery: HMAC signatures (Standard Webhooks), retries with backoff, idempotency, dead-letter replay, multi-instance workers with `SKIP LOCKED`. | Go, PostgreSQL |
| [**Witness**](https://github.com/marcus-girolneto/witness) | Tamper-evident transparency log: RFC 6962 Merkle inclusion and consistency proofs, Ed25519 signed checkpoints, split-view monitor. | Go |
| [**Rolecall**](https://github.com/marcus-girolneto/rolecall) | Permission tests for AI agents: who can make your agent do what? Declarative policies, adversarial prompts, pass/fail reports. | TypeScript |
| [**Agent Reliability Lab**](https://github.com/marcus-girolneto/agent-reliability-lab) | Evaluates tool-using incident-response agents with evidence-grounded scoring, fault injection and reproducible traces. | Python |
| [**Agent Engineering Kit**](https://github.com/marcus-girolneto/agent-engineering-kit) | Executable template for coding-agent workflows: reproducible setup, evidence-based reviews, security checks, tested API. | Python |
| [**Beacon**](https://github.com/marcus-girolneto/beacon) | Privacy-friendly analytics collector: batching with backpressure, PostgreSQL `COPY` sink, UTM attribution. | Go |
| [**Audit Trail Lab**](https://github.com/marcus-girolneto/audit-trail-lab) | Hash-chained audit records, trusted checkpoints and adversarial verification tests. | TypeScript |
| [**Linkpulse**](https://github.com/marcus-girolneto/linkpulse) · [**Utmly**](https://github.com/marcus-girolneto/utmly) | Concurrent broken-link checker with per-host rate limits; campaign link shortener with async click analytics. | Go |

### Akibo (closed source)

AI personal-finance assistant on WhatsApp and Telegram, with voice replies and a Next.js dashboard. Agent loop with schema-validated tools and explicit confirmations; **47 automated money-integrity invariants** that check balances, card statements and net position to the cent on every release and nightly in production; statement import from OFX, CSV, PDF and photos with reconciliation; PostgreSQL row-level security and encrypted backups. TypeScript, Node.js, Hono, PostgreSQL, Drizzle, Redis/BullMQ. Happy to walk through the architecture in a call.

---

## Open-source contributions

- [**Tessellation**](https://github.com/Constellation-Labs/tessellation), Constellation's Scala node software: consensus, snapshot rollback and recovery, L1 synchronization, state proofs, delegated staking and Merkle Patricia Trie performance.
- [**Gate Connect**](https://github.com/Constellation-Labs/gate-connect-app), desktop app and CLI that connect AI developer tools to Constellation Gate, keeping credentials in the OS secure store.
- 600+ merged pull requests across Constellation's public repositories (2022–2026).

---

## Stack

**Languages:** TypeScript, Scala, Python, Go, Java, Kotlin
**Backend:** Node.js, Fastify, Hono, PostgreSQL, Redis, REST, event pipelines, background jobs
**Distributed systems:** consensus, state recovery, synchronization, Merkle proofs, idempotency, incident response
**AI:** agent harnesses, tool calling, MCP, RAG, evaluations, prompt-injection defense
**Delivery:** AWS, Docker, Ansible, GitHub Actions, Prometheus/Grafana

## Education

B.Eng. Computer Engineering, Pontifícia Universidade Católica de Goiás · Rocketseat GoStack bootcamp

Most of my professional work lives in employer-owned or private repositories. This profile describes it without exposing proprietary code or data.
