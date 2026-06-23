# Instruções do GitHub Copilot - VITE

Você está em um projeto **VITE**. 

## Padrões Oficiais da Comunidade Web (React + Vite)
- **Contexto SPA**: Você está em um ambiente client-side (SPA) com Vite. Não aplique padrões de Server Components (Next.js).
- **TypeScript Strict**: Tipagem estrita. Jamais use `any`.
- **Regras de Hooks**: Siga estritamente as regras do React. Nunca manipule a DOM diretamente com `querySelector`.
- **Componentes**: Use functional components com named exports. Evite componentes de classe.
- **Otimização**: Não adicione `useMemo` ou `useCallback` de forma prematura a menos que justificável.


## Regras Globais da Equipe (OBRIGATÓRIO)
1. **Zero Tolerância para Comentários no Código**: O código gerado NÃO DEVE conter comentários.
2. **Arquitetura Altamente Modular**: Divida o código com responsabilidade única.
3. **Documentação via Markdown (.md)**: Todo diretório criado DEVE conter um `README.md`.
4. **Segurança**: NUNCA faça hardcode de segredos. Use `.env`.


