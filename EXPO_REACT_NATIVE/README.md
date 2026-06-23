# EXPO_REACT_NATIVE - Skill Set para Agentes

Use esta pasta em apps mobile com Expo e React Native. Ela deixa o agente com skills reais para economizar tokens, auditar o projeto, lidar com GitHub, checar confiança antes de implementar e seguir boas práticas de Expo/React Native.

## Como usar

1. Copie todos os arquivos desta pasta para a raiz do seu projeto.
2. Confirme que os arquivos ocultos (ex: `.cursorrules`), `AGENTS.md` e a pasta `.agents/` ficaram na raiz.
3. Pronto! IAs modernas (Cursor, Windsurf, Copilot) detectam e seguem as regras automaticamente.

## Como chamar uma skill

Se o agente aceitar comandos por barra, escreva `/nome-da-skill` no começo do pedido.

Exemplos:

- `/confidence-check veja se ja temos contexto para implementar esta tela.`
- `/caveman resumir o estado do projeto em poucas linhas.`
- `/framework-best-practices revise esta tela Expo/React Native.`
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
| `/framework-best-practices` | Aplica boas práticas deste framework. | Antes de editar código Expo/React Native. |

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

### Frontend Taste Skill

| Skill | Para que serve | Quando usar |
|---|---|---|
| `/design-taste-frontend` | Evita UI generica e melhora layout, tipografia, spacing e direção visual. | Telas mobile com foco visual, portfolios e redesigns. |
| `/gpt-taste` | Variante mais rígida para Codex/GPT, com mais variação visual e motion. | Quando o resultado estiver com cara de template. |
| `/image-to-code` | Gera/analisar referência visual antes de implementar. | Interfaces visualmente importantes. |
| `/redesign-existing-projects` | Audita UI existente e melhora sem quebrar funcionalidade. | Apps já existentes. |
| `/imagegen-frontend-mobile` | Gera referências visuais de telas mobile. | Antes de implementar telas complexas. |
| `/brandkit` | Gera direção de marca e identidade visual. | Apps novos ou redesigns com marca fraca. |

### Skills específicas desta pasta

| Skill | Para que serve | Quando usar |
|---|---|---|
| `/framework-best-practices` | Ajuda com telas, navegação, estado, assets, permissões e performance mobile. | Antes de alterar telas ou config Expo. |

## Cuidados

- Leia `.agents/sources.md` para ver origem, licença e commit das skills importadas.
- Não rode comandos destrutivos sem confirmação.
- Ajuste os comandos de teste em `AGENTS.md` conforme seu projeto.
