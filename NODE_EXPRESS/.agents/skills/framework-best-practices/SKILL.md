---
name: framework-best-practices
description: Use when working on Node.js + Express projects: routes, middlewares, services, validation, error handling, logging, auth, tests, and production readiness. Trigger with /framework-best-practices.
---

# Node.js + Express Best Practices

- Read app/server setup, route registration and middleware order before editing.
- Keep routes thin when services exist.
- Validate input at the API boundary.
- Use central error middleware when the project has one.
- Preserve response contracts and status-code conventions.
- Do not log credentials, tokens or sensitive payloads.
