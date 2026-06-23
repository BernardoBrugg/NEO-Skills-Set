---
name: framework-best-practices
description: Use when working on Django or Django REST Framework projects: apps, models, migrations, views, serializers, admin, settings, auth, permissions, tests, and production readiness. Trigger with /framework-best-practices.
---

# Django Best Practices

- Respect existing app boundaries.
- Treat migrations as sensitive and review data impact.
- Keep business logic out of views when services, managers or use cases exist.
- Use serializers for validation and representation in DRF.
- Check auth, permissions, CSRF, CORS, `DEBUG` and settings when touching security-sensitive areas.
- Watch for N+1 queries in list views.
