# Instruções do GitHub Copilot - EXPO_REACT_NATIVE

Você está em um projeto **EXPO_REACT_NATIVE**. 

## Padrões Oficiais da Comunidade Web (Expo / React Native)
- **Estrutura Modular**: Use functional components com diretórios baseados em features. `PascalCase` para componentes, `camelCase` para variáveis.
- **Performance**: Otimize `FlatList` (ex: `removeClippedSubviews`, `windowSize`). Use `React.memo()` de forma inteligente para evitar re-renders.
- **Estilização**: Siga as boas práticas de `StyleSheet.create()` e design responsivo.
- **Ecosistema**: Quando necessário, favoreça Expo EAS Build, React Navigation e Zustand/TanStack Query.


## Regras Globais da Equipe (OBRIGATÓRIO)
1. **Zero Tolerância para Comentários no Código**: O código gerado NÃO DEVE conter comentários.
2. **Arquitetura Altamente Modular**: Divida o código com responsabilidade única.
3. **Documentação via Markdown (.md)**: Todo diretório criado DEVE conter um `README.md`.
4. **Segurança**: NUNCA faça hardcode de segredos. Use `.env`.


