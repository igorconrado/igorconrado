# Igor Conrado

**Senior Full Stack Software Engineer**

Node.js & TypeScript · React & Next.js · PostgreSQL · Docker & AWS

I build software from product discovery through production: interfaces, APIs, integrations and the operational workflows behind them. Over 6+ years, I have worked across engineering services, commerce and digital products, including work with US companies.

Alongside hands-on development, I have provided technical leadership and development support to 17 engineers across Engeparc, Dea Figueiredo and VALK over time, through code reviews, pairing and mentoring, with direct management at Dea and VALK.

My engineering focus is reliable full-stack delivery: consistent data, recoverable integrations and AI workflows with explicit human control. The projects below make those decisions inspectable through code, demonstrations and reproducible checks.

[Portfolio](https://igorconrado.dev) · [LinkedIn](https://www.linkedin.com/in/igorconrado/) · [Email](mailto:contact@igorconrado.dev)

> Based in Belo Horizonte, Brazil (UTC−3). Open to remote full-stack opportunities with teams in the US and Europe.

## Start here

| Project | What to evaluate | Explore |
| --- | --- | --- |
| **Commerce Operations** | Transaction correctness, concurrency and recovery across a full-stack commerce flow | [Demo](https://github.com/igorconrado/commerce-operations/blob/main/docs/demo/commerce-flow.webm) · [Tests and results](https://github.com/igorconrado/commerce-operations/blob/main/docs/verification.md) |
| **Agent Review Workbench** | Human approval, persistent workflows and safe recovery of controlled actions | [Demo](https://github.com/igorconrado/agent-review-workbench/blob/main/docs/demo/review-flow.webm) · [Evaluation](https://github.com/igorconrado/agent-review-workbench/blob/main/docs/reports/evaluation.md) |
| **Vecto** | Product thinking and the experience of a personal planning application | [Product](https://vectoapp.com) · [Case study](https://igorconrado.dev/projects/vecto) |

## Selected engineering work

### Commerce Operations

A transactional commerce application built with **Next.js, TypeScript, GraphQL, PostgreSQL and Redis/BullMQ**.

- Concurrent stock reservations with a reproducible 100-request / 10-unit correctness experiment.
- Transactional outbox/inbox, idempotent processing and payment reconciliation after worker failure.
- Organization-scoped authorization, query batching and tested database restoration.

[Code](https://github.com/igorconrado/commerce-operations) · [Recorded demo](https://github.com/igorconrado/commerce-operations/blob/main/docs/demo/commerce-flow.webm) · [Architecture](https://github.com/igorconrado/commerce-operations/blob/main/docs/architecture.md) · [Verification](https://github.com/igorconrado/commerce-operations/blob/main/docs/verification.md) · [CI](https://github.com/igorconrado/commerce-operations/actions)

### Agent Review Workbench

An operational review application built with **Next.js, Python, FastAPI, LangGraph and PostgreSQL**, with independently tested restricted **MCP** tools.

- Human decisions bound to the exact action and context version, with authorization rechecked before execution.
- Persistent checkpoints and recovery after process failure without duplicating a sandbox effect.
- A 60-case synthetic evaluation of deterministic decisions and controlled effects.

[Code](https://github.com/igorconrado/agent-review-workbench) · [Recorded demo](https://github.com/igorconrado/agent-review-workbench/blob/main/docs/demo/review-flow.webm) · [Architecture](https://github.com/igorconrado/agent-review-workbench/blob/main/docs/architecture.md) · [Evaluation](https://github.com/igorconrado/agent-review-workbench/blob/main/docs/reports/evaluation.md) · [CI](https://github.com/igorconrado/agent-review-workbench/actions)

<details>
<summary><strong>Demonstration scope and current limits</strong></summary>

Both projects are independent demonstrations with synthetic data and documented AI assistance. Their local flows and CI checks are verified within the published scope. Commerce AWS infrastructure is statically validated, not deployed. Workbench's default workflow is deterministic; live-model comparison and subjective human scoring remain pending.

</details>

**Review the evidence:** [capability → implementation → test → result → limitation](https://github.com/igorconrado/commerce-operations/blob/main/docs/evidence.md).

## Product and research

**[Vecto](https://vectoapp.com)** — My personal planning and organization product, connecting tasks, habits, studies and other areas of daily life. The application provides product context; its source repository is private. [Product case](https://igorconrado.dev/projects/vecto).

**[Quantum Logistics](https://github.com/igorconrado/quantum-logistics-case10)** — An experimental Next.js/Python application comparing classical TSP solvers with exact classical evaluation of a QUBO model on small instances. It documents algorithmic limits and reproducible experiments; it does not claim quantum hardware execution or quantum advantage. [Application](https://quantum-logistics-case10.vercel.app).

**[URLSnap](https://github.com/igorconrado/urlsnap-api)** — A Java/Spring Boot URL-shortening API, providing an additional backend implementation to review alongside the TypeScript and Python projects.

## Technical focus

| Area | Technologies and practices |
| --- | --- |
| Full-stack development | TypeScript, React, Next.js, Node.js, Python |
| APIs and data | GraphQL, PostgreSQL, transactions, Redis, background jobs |
| Reliability | Idempotency, concurrency, reconciliation, failure recovery |
| Controlled automation | LangGraph, MCP, human approval, evaluation datasets |
| Delivery | Docker, GitHub Actions, reproducible checks; Terraform/AWS configuration |
| Additional work | Java, Spring Boot, algorithm experiments with Qiskit |

Professional experience and product case studies are available on my [portfolio](https://igorconrado.dev) and [LinkedIn](https://www.linkedin.com/in/igorconrado/). The repositories above demonstrate current technical work; they do not reproduce employer systems or business results.
