---
name: framework-best-practices
description: Use when working on AI, RAG, LLM, embedding, chatbot, agent, prompt, retrieval, evaluation, guardrail, observability, or model-integration projects. Trigger with /framework-best-practices.
---

# AI/RAG Best Practices

- Separate ingestion, chunking, embeddings, retrieval, reranking, prompt assembly and generation.
- Version important prompts and model settings.
- Test retrieval before blaming generation.
- Track source, date and version for documents when possible.
- Do not send sensitive data to external models without permission.
- Treat prompt injection from retrieved documents as a real threat.
- Evaluate quality, cost and latency after changes.
