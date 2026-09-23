# Hi, I'm Jelena 👋

### Python Backend Engineer

I build reliable backend services, APIs, third-party integrations, and cloud-based applications using Python.

My main focus is backend engineering — designing APIs, integrating external services, working with asynchronous systems, and building maintainable production-ready applications.

## 🛠 Tech Stack

**Backend**

Python · FastAPI · REST APIs · gRPC · AsyncIO · Pydantic

**Data & Messaging**

PostgreSQL · Redis · RabbitMQ

**Cloud & DevOps**

AWS · Docker · GitHub Actions · CI/CD

**Testing**

Pytest · Unit Testing · Integration Testing · End-to-End Testing · BDD

---

## 🚀 Featured Projects

### [SubFlow — Subscription Management API](https://github.com/jecas/subflow)

Production-style asynchronous backend for managing customers, plans, subscriptions, and payments.

**Stack:** Python 3.12 · FastAPI · PostgreSQL · SQLAlchemy · Redis · Alembic · Docker · Pytest

**Highlights:**

* Async FastAPI and SQLAlchemy architecture
* JWT authentication and role-based authorization
* Subscription lifecycle management
* Calendar-aware monthly and yearly billing periods
* Redis cache-aside strategy
* Payment provider abstraction
* Idempotent payment processing using `Idempotency-Key`
* Protected payment webhooks with duplicate-event handling
* Alembic database migrations
* Structured JSON logging and request IDs
* Unit and integration tests
* GitHub Actions CI with migration validation and Docker build

👉 [View SubFlow on GitHub](https://github.com/jecas/subflow)

---

### [RelayForge — Resilient API Integration Service](https://github.com/jecas/relayforge)

Asynchronous integration service demonstrating resilient communication with external API providers through different authentication and request flows.

**Stack:** Python 3.12 · FastAPI · HTTPX · PostgreSQL · SQLAlchemy · Alembic · Docker · Pytest

**Highlights:**

* Provider abstraction with multiple external integrations
* Multi-step `authorize → token → verify` provider flow
* API-key-based provider integration
* Async HTTP communication with HTTPX
* Configurable timeouts and retry handling
* Exponential retry delay and `Retry-After` support
* Provider error normalization
* Correlation ID generation and propagation
* Structured JSON logging
* PostgreSQL verification audit persistence
* Mock external provider for realistic testing
* Unit, integration, and full-stack E2E tests
* Docker Compose environment
* GitHub Actions CI with migration and Docker validation

👉 [View RelayForge on GitHub](https://github.com/jecas/relayforge)

---

### Event-Driven Python Service

Event-driven backend demonstrating asynchronous processing using RabbitMQ.

**Planned architecture:**

`FastAPI → RabbitMQ → Worker → PostgreSQL / Redis → External API`

Planned features include retry handling, idempotency, background processing, caching, and automated testing.

`Coming soon`

---

## 💻 What I Can Help With

* Python backend development
* FastAPI applications and microservices
* REST and gRPC API development
* Third-party API integrations
* Async Python services
* Existing Python application debugging
* API performance and reliability improvements
* AWS-based backend applications
* Redis and RabbitMQ integrations
* Automated testing and CI/CD

---

## 🌐 Web Development

I also build complete web applications and digital solutions for businesses through **Webnica**.

Web applications · Booking systems · Business websites · Desktop applications · Chatbots

👉 [Visit Webnica](https://jecas.github.io/)

---

## 🤝 Available for Freelance Projects

I'm available for selected freelance projects involving:

**Python · FastAPI · Backend Development · API Integrations · AWS · Automation**

If you have an existing Python system that needs a new integration, a backend service built from scratch, or a difficult API problem to solve, feel free to get in touch.

📧 Contact: jelena_s7@yahoo.com

🌐 Webnica: https://jecas.github.io/
