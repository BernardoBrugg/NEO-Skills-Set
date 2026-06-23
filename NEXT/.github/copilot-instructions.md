# Instruções do GitHub Copilot - NEXT

Você está em um projeto **NEXT**. 

## Padrões Oficiais da Comunidade Web (Next.js)
- **App Router & React 19**: Priorize o App Router, Server Actions e padrões do React 19. Evite sintaxe depreciada do Pages Router.
- **Nomenclatura**: Use `kebab-case` para diretórios e arquivos (ex: `user-profile.tsx`).
- **Padrão de Componente**: Favoreça functional components, named exports e o padrão RORO (Receive Object, Return Object).
- **TypeScript Strict**: Use `interfaces`. Evite `any` (use `unknown` se necessário).
- **Tratamento de Erros**: Priorize guard clauses e early returns.


## Regras Globais da Equipe (OBRIGATÓRIO)
1. **Zero Tolerância para Comentários no Código**: O código gerado NÃO DEVE conter comentários.
2. **Arquitetura Altamente Modular**: Divida o código com responsabilidade única.
3. **Documentação via Markdown (.md)**: Todo diretório criado DEVE conter um `README.md`.
4. **Segurança**: NUNCA faça hardcode de segredos. Use `.env`.


