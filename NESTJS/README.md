# NESTJS - Skill Set para Agentes

Use esta pasta em APIs Node.js com NestJS. Ela deixa o agente com skills reais para economizar tokens, auditar o projeto, lidar com GitHub, checar confiança antes de implementar e seguir boas práticas de NestJS.

## Como usar

1. Copie todos os arquivos desta pasta para a raiz do seu projeto.
2. Confirme que os arquivos ocultos (ex: `.cursorrules`), `AGENTS.md` e a pasta `.agents/` ficaram na raiz.
3. Pronto! IAs modernas (Cursor, Windsurf, Copilot) detectam e seguem as regras automaticamente.

## Como chamar uma skill

Se o agente aceitar comandos por barra, escreva `/nome-da-skill` no começo do pedido.

Exemplos:

- `/confidence-check veja se ja temos contexto para implementar esta tela.`
- `/caveman resumir o estado do projeto em poucas linhas.`
- `/framework-best-practices revise este módulo, service ou controller NestJS.`
- `/threejs crie uma cena 3D simples com React Three Fiber.`

Se o agente nao aceitar `/`, escreva: `Use a skill confidence-check`.

## Skills disponíveis

### Core para Codex e agentes de código

| Skill | Para que serve | Quando usar |
|---|---|---|
| `/confidence-check` | Verifica se o agente tem contexto suficiente antes de implementar. | Antes de tarefas grandes, refatores ou bugs confusos. |
| `/project-skill-audit` | Audita o projeto e sugere skills úteis. | Ao configurar o projeto ou melhorar o kit de agentes. |
| `/terminal-skills` | Ajuda a buscar e instalar skills públicas. | Quando faltar uma skill específica. |
| `/github` | Ajuda com PRs, issues, CI e GitHub CLI. | Quando o projeto usa GitHub. |
| `/bmad-product-brief` | Transforma ideia vaga em brief de produto. | Antes de criar uma feature grande. |
| `/framework-best-practices` | Aplica boas práticas deste framework. | Antes de editar código NestJS. |

### Economia de tokens com CAVEMAN

| Skill | Para que serve | Quando usar |
|---|---|---|
| `/caveman` | Responde curto e reduz tokens. | Para status, resumos e triagem. |
| `/caveman-compress` | Comprime arquivos longos de memória/instruções. | Para reduzir `AGENTS.md`, planos e notas. |
| `/caveman-review` | Gera review curto e acionável. | Para revisar diffs sem texto demais. |
| `/caveman-commit` | Gera mensagem de commit curta. | Antes de commitar. |
| `/caveman-help` | Explica como usar CAVEMAN. | Quando nao souber qual comando CAVEMAN usar. |
| `/caveman-stats` | Ajuda a medir economia/uso do CAVEMAN. | Para acompanhar compressão e tokens. |
| `/cavecrew` | Orienta uso de subagentes com saída comprimida. | Quando houver investigação/review delegável. |

### Skills específicas desta pasta

| Skill | Para que serve | Quando usar |
|---|---|---|
| `/nestjs` | Ensina padrões de módulos, controllers, services, DTOs, pipes e guards. | Ao criar ou revisar APIs NestJS. |
| `/webauthn` | Ajuda a implementar login sem senha com passkeys. | Para autenticação com biometria, Touch ID, Face ID ou chaves FIDO2. |

## Cuidados

- Leia `.agents/sources.md` para ver origem, licença e commit das skills importadas.
- Não rode comandos destrutivos sem confirmação.
- Ajuste os comandos de teste em `AGENTS.md` conforme seu projeto.
