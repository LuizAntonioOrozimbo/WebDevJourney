# 📁 07-tools
Coleção de Ferramentas, Configurações e Utilitários para Desenvolvimento

Este diretório reúne ferramentas essenciais, configurações reutilizáveis e utilitários que ajudam a padronizar e acelerar o workflow de desenvolvimento ao longo de toda a jornada WebDevJourney.

# 🎯 Objetivo

Centralizar instalações, configurações e guias de ferramentas comuns

Padronizar ambientes entre projetos (JS, Node, React etc.)

Servir como referência rápida para setups importantes

Reaproveitar configurações sem precisar refazer do zero

# 📁 Estrutura das Pastas

07-tools/
├── git/
├── node-npm/
├── vscode/
├── browsers/
├── linters-formatters/
├── build-tools/
└── testing/

A seguir, o propósito de cada uma:

# 📂 git/

Configurações e utilidades para Git.

**Conteúdo sugerido:**

+ .gitignore global

+ padrões de commits (Conventional Commits)

+ guia de branches (Git Flow, Trunk Based, etc.)

+ aliases úteis

+ snippets para README.md com comandos Git

# 📂 node-npm/

Tudo relacionado ao ambiente Node.js.

**Inclui:**

+ instruções de instalação

+ como configurar npm, npx, nvm

+ package.json templates

+ scripts úteis pré-prontos

+ pacotes recomendados para cada tipo de projeto

# 📂 vscode/

Configurações, extensões e setups do VS Code.

**Exemplos:**

+ lista de extensões essenciais

+ arquivo settings.json modelo

+ keybindings personalizados

+ temas recomendados

+ atalhos produtivos

# 📂 browsers/

Ferramentas e configurações de browsers usados no desenvolvimento.

**Inclui:**

+ dicas do DevTools (Chrome, Edge, Firefox)

+ configurações para testes locais

+ emular dispositivos

+ limpar cache, storage, service workers

# 📂 linters-formatters/

Configurações compartilháveis para:

**+ ESLint**

**+ Prettier**

**+ Stylelint**

**+ EditorConfig**

Ex:
eslint.config.js base para JS e React
.prettierrc padronizado
.editorconfig universal

# 📂 build-tools/

Guia e presets de ferramentas de build e automação:

+ Vite

+ Webpack

+ Parcel

+ Babel

+ Rollup

Aqui você poderá armazenar:

+ templates minimalistas

+ configuração inicial pronta para copiar/colar

+ documentação curta para cada ferramenta

# 📂 testing/

Ferramentas de testes que você vier a estudar:

+ Jest

+ Vitest

+ Cypress

+ Playwright

+ Testing Library

Com:

+ configs básicas

+ comandos essenciais

+ templates de testes


# 🧱 Padrão de Organização

Cada pasta terá:

README.md       ← explicação + links + guia rápido
modelos/        ← arquivos base usáveis em projetos
exemplos/       ← exemplos reais


🚀 Expansões Futuras

Você poderá adicionar:

**+** pasta para Docker

**+** pasta para GitHub Actions

**+** pasta para CI/CD

**+** pasta para bancos de dados

**+** pasta para Postman/Insomnia

# 📝 Observação

A pasta 07-tools complementa as demais partes do repositório.
Aqui ficam as ferramentas — não os projetos, não os exercícios, e não as anotações.

Se quiser, posso:

✅ Criar as subpastas na ordem correta
✅ Gerar um README para cada subpasta também
✅ Criar arquivos modelo como .editorconfig, .gitignore, settings.json etc.