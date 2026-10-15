# Igor Conrado

**Senior Full Stack Software Engineer**

I build full-stack products with TypeScript, React, Next.js, Node.js and Python, with a focus on data consistency, reliable integrations and controlled AI workflows. My portfolio connects implementation to executable tests, recovery experiments and architectural decisions.

[Portfolio](https://igorconrado.dev) · [LinkedIn](https://www.linkedin.com/in/igorconrado/) · [Email](mailto:contact@igorconrado.dev)

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

Both projects are independent demonstrations with synthetic data and documented AI assistance. Their local flows and CI checks are verified within the published scope. Commerce AWS infrastructure is statically validated, not deployed. Workbench's default workflow is deterministic; live-model comparison and subjective human scoring remain pending.

**Review the evidence:** [capability → implementation → test → result → limitation](https://github.com/igorconrado/commerce-operations/blob/main/docs/evidence.md).

## Product and research

**[Vecto](https://vectoapp.com)** — My personal planning and organization product, connecting tasks, habits, studies and other areas of daily life. The application provides product context; its source repository is private. [Product case](https://igorconrado.dev/projects/vecto).

**[Quantum Logistics](https://github.com/igorconrado/quantum-logistics-case10)** — An experimental Next.js/Python application comparing classical TSP solvers with exact classical evaluation of a QUBO model on small instances. It documents algorithmic limits and reproducible experiments; it does not claim quantum hardware execution or quantum advantage. [Application](https://quantum-logistics-case10.vercel.app).

**[URLSnap](https://github.com/igorconrado/urlsnap-api)** — Additional Java/Spring Boot backend work.

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
