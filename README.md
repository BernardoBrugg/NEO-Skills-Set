# Skill Sets para Agentes por Framework

Este repositorio entrega pastas prontas para copiar e colar em projetos reais. Cada pasta contem regras, skills reais importadas de repositorios publicos, boas praticas do framework e instrucoes em portugues para pessoas leigas.

## Passo a Passo: Como usar na sua máquina

Para que os seus projetos fiquem com a inteligência artificial configurada com as regras da equipe, siga este passo a passo:

1. **Clone este repositório** em algum lugar do seu computador:
   ```bash
   git clone https://github.com/BernardoBrugg/NEO-Skills-Set.git
   ```
2. **Abra o repositório** e escolha a pasta correspondente ao framework do seu projeto atual (ex: se vai programar em Next.js, entre na pasta `NEXT`).
3. **Copie todo o conteúdo** (incluindo as pastas e arquivos ocultos como `.cursorrules` e `.agents`) que está *dentro* dessa pasta específica.
4. **Cole tudo na raiz do seu projeto real**.
5. **Pronto! Como cada IA lê estas regras automaticamente:**
   - **Cursor**: Lê automaticamente o arquivo `.cursorrules` na raiz. Não precisa de prompt inicial.
   - **Windsurf**: Lê automaticamente o arquivo `.windsurfrules`.
   - **VS Code (GitHub Copilot)**: Lê o arquivo `.github/copilot-instructions.md`.
   - **Claude Code CLI**: É recomendado o prompt inicial: `Leia AGENTS.md e .agents/workspace-rules.md`.
   - **Antigravity / Codex / Outros**: Vasculham a raiz e detectam o `.cursorrules` ou `AGENTS.md`. No primeiro prompt, diga: *Leia AGENTS.md antes de começar*.

Com isso feito, os agentes já seguirão estritamente a arquitetura, regras de zero comentários e acionarão as skills necessárias do seu framework.

## Qual pasta escolher

- `VITE`: apps React criados com Vite.
- `NEXT`: apps Next.js.
- `FASTAPI`: APIs Python com FastAPI.
- `DJANGO`: projetos Django ou Django REST Framework.
- `NODE_EXPRESS`: APIs Node.js com Express.
- `NESTJS`: APIs Node.js com NestJS.
- `EXPO_REACT_NATIVE`: apps mobile com Expo/React Native.
- `AI_RAG`: projetos de IA, RAG, embeddings, chatbots e pipelines LLM.

## O que vem em cada pasta

- `README.md`: guia para leigos.
- `AGENTS.md`: instrucoes principais para agentes como Codex.
- `CLAUDE.md`: instrucoes para Claude Code.
- `.agents/workspace-rules.md`: regras detalhadas do workspace.
- `.agents/skillset.md`: indice das skills.
- `.agents/sources.md`: fontes e licencas.
- `.agents/skills/`: skills no formato `.agents/skills/<nome>/SKILL.md`.
Todos os skills utilizaveis ficam no mesmo lugar dentro de cada template: `.agents/skills/<nome-da-skill>/SKILL.md`.

## SUPERPOWERS oficial incluido

O pacote oficial `obra/Superpowers` esta incluido em todos os templates:

- Repo: https://github.com/obra/Superpowers
- Licenca: MIT
- Commit usado: `896224c4b1879920ab573417e68fd51d2ccc9072`
- Skills oficiais copiadas para `.agents/skills/`
- As skills ficam diretamente em `.agents/skills/`

## Taste Skill incluido nos frontends

Os templates `VITE`, `NEXT` e `EXPO_REACT_NATIVE` incluem `Leonxlnx/taste-skill`:

- Repo: https://github.com/Leonxlnx/taste-skill
- Licenca: MIT
- Commit usado: `06d6028b5c623016c59ce8536f578e5a1127b499`
- Skills copiadas diretamente para `.agents/skills/`

## Chamando skills com /

Depois de copiar uma pasta para seu projeto, peça ao agente para ler `AGENTS.md`.

Se o agente aceitar comandos por barra, use:

- `/confidence-check` para checar se o agente tem contexto antes de implementar.
- `/using-superpowers` para ativar o fluxo oficial do `obra/Superpowers`.
- `/design-taste-frontend` para frontend anti-slop nos templates frontend.
- `/gpt-taste` para regras frontend mais rígidas em GPT/Codex.
- `/image-to-code` para gerar/analisar referência visual antes de codar.
- `/brainstorming` para transformar ideia vaga em especificacao.
- `/writing-plans` para criar plano de implementacao.
- `/subagent-driven-development` para dividir execucao entre subagentes.
- `/test-driven-development` para RED-GREEN-REFACTOR.
- `/verification-before-completion` para validar antes de encerrar.
- `/project-skill-audit` para auditar quais skills o projeto precisa.
- `/terminal-skills` para buscar mais skills publicas.
- `/caveman` para resposta curta e economia de tokens.
- `/caveman-compress caminho/do/arquivo.md` para comprimir arquivos de memoria.
- `/caveman-review` para revisao curta.
- `/github` para PRs, issues e CI com GitHub CLI.
- `/framework-best-practices` para boas praticas do framework escolhido.

Se o agente nao aceitar `/`, escreva: `Use a skill confidence-check`.

## Como combinar templates

Use apenas uma pasta como base. Se o projeto tiver mais de uma stack, copie a pasta principal e depois traga manualmente apenas as skills especificas da segunda stack. Exemplo: em um monorepo Next + FastAPI, comece por `NEXT` e crie uma skill extra em `.agents/skills/backend-fastapi/SKILL.md`.

## Aviso rapido

Este kit combina templates proprios com skills importadas de repositorios publicos permissivos. Leia `LICENSES.md` e os arquivos `.agents/sources.md` antes de redistribuir ou vender este material.
