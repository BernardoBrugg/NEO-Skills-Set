# Instrucoes para Agentes - AI_RAG

Antes de trabalhar, leia este arquivo e depois consulte `.agents/skillset.md`.

## Prioridade

1. Respeite privacidade, fontes e contratos de dados.
2. Nao sobrescreva trabalho do usuario.
3. Separe prompt, retrieval, modelo, avaliacao e observabilidade.
4. Explique riscos antes de comandos destrutivos.
5. Teste qualidade, custo e regressao quando alterar comportamento.

## Skills padrao

- Use `/confidence-check` antes de implementar tarefas grandes ou arriscadas.
- Use `/project-skill-audit` para auditar quais skills o projeto precisa.
- Use `/github` para PRs, issues, CI e GitHub CLI.
- Use `/bmad-product-brief` para transformar ideias vagas em brief de produto.
- Use `/caveman` para resumos ultra curtos.
- Use `/caveman-compress` para comprimir arquivos de memoria.
- Use `/framework-best-practices` para decisoes do framework.

## Comandos sugeridos

Verifique o projeto antes. Comandos comuns:

```bash
pytest
npm test
python -m pytest
```

Use tambem scripts locais de avaliacao, ingestao e smoke test quando existirem.

## Padrao de entrega

Ao finalizar, diga o que mudou, quais arquivos principais foram tocados, quais avaliacoes foram executadas e riscos restantes.
