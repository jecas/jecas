# Hi, I'm Jelena 👋

### Python Backend Engineer

I build reliable backend services, APIs, third-party integrations, and event-driven systems using Python.

My focus is backend engineering: designing maintainable APIs, integrating external services, building asynchronous and distributed workflows, and developing production-style applications with strong testing and observability.

---

## 🛠 Tech Stack

**Backend**

Python · FastAPI · REST APIs · gRPC · AsyncIO · Pydantic · SQLAlchemy

**Data & Messaging**

PostgreSQL · Redis · RabbitMQ

**Cloud & DevOps**

AWS · Docker · Docker Compose · GitHub Actions · CI/CD

**Testing**

Pytest · Unit Testing · Integration Testing · End-to-End Testing · BDD

---

## 🚀 Featured Projects

### [SubFlow — Subscription Management API](https://github.com/jecas/subflow)

Production-style asynchronous backend for managing customers, plans, subscriptions, and payments.

**Python 3.12 · FastAPI · PostgreSQL · Redis · SQLAlchemy · Alembic · Docker**

**Highlights**

- JWT authentication and role-based authorization
- Subscription lifecycle and calendar-aware billing periods
- Redis cache-aside strategy
- Payment provider abstraction
- Idempotent payment processing with `Idempotency-Key`
- Protected webhooks with duplicate-event handling
- Structured JSON logging and request IDs
- Unit and integration tests
- GitHub Actions CI with migration validation

👉 [Explore SubFlow](https://github.com/jecas/subflow)

---

### [RelayForge — Resilient API Integration Service](https://github.com/jecas/relayforge)

Async integration service designed around reliable communication with external API providers.

**Python 3.12 · FastAPI · HTTPX · PostgreSQL · SQLAlchemy · Alembic · Docker**

**Highlights**

- Multiple providers behind a common abstraction
- Multi-step `authorize → token → verify` integration flow
- API-key-based provider integration
- Async HTTP communication with HTTPX
- Timeouts, retries, exponential delay, and `Retry-After`
- Normalized provider errors
- Correlation ID propagation
- PostgreSQL audit persistence
- Deterministic mock providers
- Unit, integration, and full-stack E2E tests

👉 [Explore RelayForge](https://github.com/jecas/relayforge)

---

### [EventPulse — Event-Driven Processing Platform](https://github.com/jecas/eventpulse)

Reliable asynchronous event-processing service built around RabbitMQ and background workers.

**Python 3.12 · FastAPI · RabbitMQ · PostgreSQL · Redis · aio-pika · Docker**

**Highlights**

- `202 Accepted` asynchronous event ingestion
- RabbitMQ publisher and async worker architecture
- Durable exchanges and queues
- Delayed retry queue with automatic redelivery
- Dead-letter queue for exhausted retries
- Redis-based event deduplication
- PostgreSQL event lifecycle persistence
- External service integration with HTTPX
- Correlation ID propagation and structured logging
- Full-stack E2E validation of success, retry, and failure flows
- GitHub Actions CI with migration and Docker validation

👉 [Explore EventPulse](https://github.com/jecas/eventpulse)

---

## 💻 What I Can Help With

- Python backend development
- FastAPI applications and microservices
- REST and gRPC APIs
- Third-party API integrations
- Async and event-driven Python services
- RabbitMQ and Redis integrations
- Existing Python application debugging
- Backend reliability and API improvements
- AWS-based backend applications
- Automated testing and CI/CD

---

## 🧩 Backend Engineering Focus

Across my projects, I focus on problems that appear in real backend systems:

`API design` · `async processing` · `external integrations` · `retries` · `idempotency` · `message queues` · `caching` · `database migrations` · `observability` · `automated testing`

My portfolio projects intentionally cover different backend architectures:

| Project | Main Engineering Focus |
|---|---|
| **SubFlow** | SaaS backend, authentication, subscriptions, payments, caching |
| **RelayForge** | Third-party integrations, resilience, retries, provider abstraction |
| **EventPulse** | Event-driven architecture, RabbitMQ, workers, retry queues, DLQ |

---

## 🌐 Web Development

I also build complete web applications and digital solutions for businesses through **Webnica**.

Web applications · Booking systems · Business websites · Desktop applications · Chatbots

👉 [Visit Webnica](https://jecas.github.io/)

*Webnica is currently available in Serbian, as it primarily serves the local Serbian market.*

---

## 🤝 Available for Freelance Projects

I'm available for selected freelance projects involving:

**Python · FastAPI · Backend Development · API Integrations · AWS · Async Systems**

If you need a Python backend service, an external API integration, an asynchronous processing system, or help improving an existing backend application, feel free to get in touch.

📧 **Contact:** jelena_s7@yahoo.com

🌐 **Webnica:** https://jecas.github.io/
