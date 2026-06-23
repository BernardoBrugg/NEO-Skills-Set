# Instrucoes para Agentes - DJANGO

Antes de trabalhar, leia este arquivo e depois consulte `.agents/skillset.md`.

## Prioridade

1. Respeite apps, models e settings existentes.
2. Nao sobrescreva trabalho do usuario.
3. Trate migrations como mudancas sensiveis.
4. Explique riscos antes de comandos destrutivos.
5. Teste comportamento alterado.

## Skills padrao

- Use `/confidence-check` antes de implementar tarefas grandes ou arriscadas.
- Use `/project-skill-audit` para auditar quais skills o projeto precisa.
- Use `/github` para PRs, issues, CI e GitHub CLI.
- Use `/bmad-product-brief` para transformar ideias vagas em brief de produto.
- Use `/caveman` para resumos ultra curtos.
- Use `/caveman-compress` para comprimir arquivos de memoria.
- Use `/framework-best-practices` para decisoes do framework.

## Comandos sugeridos

Verifique `manage.py`, `pyproject.toml`, `requirements.txt` ou `Makefile` antes. Comandos comuns:

```bash
python manage.py check
python manage.py test
ruff check .
```

## Padrao de entrega

Ao finalizar, diga o que mudou, quais arquivos principais foram tocados e quais testes foram executados. Se nao conseguiu testar, diga o motivo.
