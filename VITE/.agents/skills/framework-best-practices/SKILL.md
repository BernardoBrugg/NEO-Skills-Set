---
name: framework-best-practices
description: Use when working on Vite + React projects: components, hooks, routing, state, Vite config, env vars, accessibility, performance, tests, and production readiness. Trigger with /framework-best-practices.
---

# Vite + React Best Practices

- Read `package.json`, `vite.config.*`, routing setup, and nearby components before editing.
- Keep components focused and colocate component-specific files when the project already does that.
- Use local state for local UI, server-state tools for remote data, and global state only for shared app concerns.
- Preserve loading, error, empty and success states.
- Treat `VITE_` env vars as public.
- Validate with lint, tests or build when available.
