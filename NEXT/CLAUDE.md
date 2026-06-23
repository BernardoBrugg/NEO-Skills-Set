# Claude Code - NEXT

Leia `AGENTS.md` primeiro. Para tarefas complexas, use `/confidence-check` primeiro e depois escolha a skill adequada em `.agents/skillset.md`.

## Uso recomendado

- Use subagents para revisao, pesquisa, testes ou auditoria quando a tarefa for grande.
- Mantenha contexto curto: leia rotas, componentes e configs especificas.
- Antes de editar, identifique se o arquivo roda no servidor ou cliente.
- Antes de terminar, rode os comandos disponiveis de lint, test ou build.

## Prompt inicial sugerido

`Leia AGENTS.md e .agents/skillset.md. Depois implemente a tarefa seguindo as regras do workspace.`
