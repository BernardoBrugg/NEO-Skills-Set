---
name: framework-best-practices
description: Use when working on NestJS projects: modules, controllers, providers, services, DTOs, pipes, guards, interceptors, filters, auth, tests, and production readiness. Trigger with /framework-best-practices.
---

# NestJS Best Practices

- Respect module boundaries and dependency injection.
- Controllers handle transport; services handle business logic.
- Use DTOs and pipes for validation when the project follows that pattern.
- Use guards for authorization and interceptors/filters for cross-cutting behavior.
- Register providers in the correct module.
- Avoid manual class instantiation when DI should own lifecycle.
