---
name: framework-best-practices
description: Use when working on Next.js projects: App Router, Server Components, Client Components, route handlers, server actions, metadata, caching, auth, tests, and production readiness. Trigger with /framework-best-practices.
---

# Next.js Best Practices

- Identify whether code runs on server or client before editing.
- Use `use client` only for browser APIs, client hooks, event handlers, or client-only libraries.
- Fetch data on the server when possible.
- Validate input in route handlers and server actions.
- Treat `NEXT_PUBLIC_` env vars as public.
- Be explicit about cache, revalidation and dynamic rendering changes.
- Handle loading, error and not-found states where needed.
