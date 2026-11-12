Backend AI Engineering Standards
A reusable reference library of backend engineering standards and AI-ready project documentation for Node.js, Express.js, and TypeScript applications.

The package helps developers establish consistent architecture, coding conventions, security practices, testing expectations, and AI-assisted development workflows across projects.
What this package is
This repository is a standards and reference documentation package. It is not a ready-to-run Node.js application, starter template, or generated production backend.

Use the guidance to plan and build projects, and adapt each standard to your actual requirements, runtime, infrastructure, and team conventions.
What's included
The documentation is organized into these areas:
1. Project Foundation — setup, technology choices, environment configuration, application lifecycle.
2. Architecture & Design — modular monoliths, microservices, clean and layered architecture, dependency injection, design patterns.
3. Folder Structure — feature organization, naming conventions, shared modules, configuration placement.
4. Coding Standards — SOLID, Clean Code, TypeScript, asynchronous programming, error handling, logging.
5. Reusable Functionality — utilities, functions, classes, base classes, shared services.
6. API & Middleware — routes, controllers, services, repositories, authentication, authorization, validation, rate limiting, versioning.
7. Database Management — connectivity, pooling, transactions, migrations, repositories, indexing, query optimization.
8. Communication & Integrations — email, third-party APIs, webhooks, sockets, events, queues, file storage.
9. Background Processing — scheduled tasks, workers, queues, retries, distributed job execution.
10. AI Integration — provider abstraction, model management, prompt versioning, token/cost tracking, response validation.
11. Security Standards — secrets, password and JWT security, injection prevention, encryption, audit logging.
12. Testing & Quality — unit, integration, API, mocking, load testing, linting, code review.
13. Performance & Scalability — caching, Node.js processes, worker threads, horizontal scaling, memory management.
14. Observability & Monitoring — structured logs, health checks, metrics, tracing, alerting.
15. Development & Deployment — Git, environments, Docker, CI/CD, deployment, graceful shutdown.
16. AI Development Guidelines — project context, coding rules, code generation, architecture validation, AI code review.
It also includes framework-specific guidance, example structures, an AGENTS.md instruction file, dependency guidance, initialization and production-readiness checklists, and Architecture Decision Record (ADR) guidance.
Quick start
1. Download and extract the ZIP.
2. Read [`AGENTS.md`](AGENTS.md) before using an AI coding assistant.
3. Read [`DOCUMENTATION-INDEX.md`](DOCUMENTATION-INDEX.md) to find the relevant standards.
4. Choose the architecture that fits your application. A modular monolith is often a sensible starting point unless independent deployment, scaling, ownership, or fault isolation justifies microservices.
5. Review the relevant security, database, API, testing, and deployment documents.
6. Adapt the guidance to your project and record important decisions as ADRs.
7. Use [`backend-initialization-checklist.md`](backend-initialization-checklist.md) when setting up a new project and [`production-readiness-checklist.md`](production-readiness-checklist.md) before release.
Using this with AI coding assistants
Place or adapt AGENTS.md at the root of the project you want the assistant to work on. Keep the relevant standards available in the repository and ask the assistant to read the instructions and applicable documents before making changes.

Example instruction:
Before implementing this feature, read the project's AGENTS.md and the relevant backend engineering standards. Inspect the existing architecture first, follow established conventions, avoid unnecessary dependencies, add tests, and report the validation commands you ran.

AI-generated code still requires developer review, testing, and security validation. Markdown instructions provide context; they do not guarantee correct or secure output.
Suggested repository topics
backend · nodejs · expressjs · typescript · software-architecture · microservices · clean-architecture · solid-principles · backend-development · api-development · ai-coding · agents-md
Contributing
When adding or changing standards:
- Keep recommendations practical and explain trade-offs.
- Distinguish required, recommended, and optional tools.
- Avoid hardcoding package versions unless they have been verified.
- Include security, failure handling, and testing considerations.
- Update DOCUMENTATION-INDEX.md when adding new top-level documentation.
- Verify internal Markdown links before submitting changes.
Disclaimer
Technology versions, package maintenance status, pricing, and security recommendations change over time. Verify current documentation and advisories before adopting a dependency or deploying a design. This package is educational engineering guidance and should be reviewed against your organization's security, compliance, and operational requirements.
Build with standards. Keep architecture intentional. Use AI with context.
