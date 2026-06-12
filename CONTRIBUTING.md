# Guia de Contribuição - PortfolioHUB

Para manter a rastreabilidade e a governança de código do projeto, todas as alterações devem seguir a especificação de **Conventional Commits**.

## Padrão de Commits:
- `feat: ...` para novas seções ou funcionalidades. (Ex: `feat: adiciona tag de seguranca defensiva no layout`)
- `fix: ...` para correção de bugs ou problemas visuais. (Ex: `fix: corrige quebra de layout mobile`)
- `docs: ...` para documentação (README, portfólio textorizado).
- `style: ...` para ajustes estéticos que não alteram lógica (CSS puro, formatação).

## Fluxo de Trabalho (GitFlow Simplificado):
1. Crie uma branch a partir da `develop`: `git checkout -b feature/nome-da-mudanca`
2. Faça seus commits seguindo o padrão.
3. Abra um Pull Request para a branch `develop`.