# Instrucoes para Agentes - NODE_EXPRESS

Antes de trabalhar, leia este arquivo e depois consulte `.agents/skillset.md`.

## Prioridade

1. Respeite a estrutura atual de rotas, services e middlewares.
2. Nao sobrescreva trabalho do usuario.
3. Valide input e trate erros de forma consistente.
4. Explique riscos antes de comandos destrutivos.
5. Teste endpoints alterados.

## Skills padrao

- Use `/confidence-check` antes de implementar tarefas grandes ou arriscadas.
- Use `/project-skill-audit` para auditar quais skills o projeto precisa.
- Use `/github` para PRs, issues, CI e GitHub CLI.
- Use `/bmad-product-brief` para transformar ideias vagas em brief de produto.
- Use `/caveman` para resumos ultra curtos.
- Use `/caveman-compress` para comprimir arquivos de memoria.
- Use `/framework-best-practices` para decisoes do framework.

## Comandos sugeridos

Verifique `package.json` antes. Comandos comuns:

```bash
npm run lint
npm test
npm run build
```

## Padrao de entrega

Ao finalizar, diga o que mudou, quais arquivos principais foram tocados e quais testes foram executados. Se nao conseguiu testar, diga o motivo.
