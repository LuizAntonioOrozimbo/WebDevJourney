# 📁 08-configs
**Modelos de Configurações Globais e Arquivos Padrão**

Esta pasta reúne arquivos de configuração reutilizáveis, úteis em vários tipos de projetos (HTML, CSS, JavaScript, React, Node, etc.).
O objetivo é manter um conjunto centralizado de padrões, facilitando:

+ a criação de novos projetos,

+ a padronização do estilo de código,

+ a consistência entre todos os diretórios do WebDevJourney.

# 🎯 Objetivo

+ Armazenar configurações padrão para ferramentas comuns.

+ Criar uma base que pode ser copiada direto para projetos.

+ Evitar retrabalho ao iniciar um novo repositório.

+ Garantir uniformidade entre pastas e projetos.

# 📁 Estrutura das Pastas

08-configs/
├── editorconfig/
├── prettier/
├── eslint/
├── gitignore/
├── vscode/
└── others/

A seguir, a descrição de cada pasta:

# 📂 editorconfig/

Arquivos .editorconfig que definem regras universais de edição:

+ tipo de indentação

+ tamanho do tab

+ charset

+ remoção de linhas finais

+ padronização entre IDEs e editores

**Arquivo principal:**

base.editorconfig


📂 prettier/

Configurações para formatação automática com Prettier:

+ preferências de aspas

+ trailing commas

+ largura máxima de linha

+ regras de formatação para JS, TS, JSON, Markdown e CSS

**Arquivo principal:**
prettierrc.json


# 📂 eslint/

Templates para ESLint voltados para:

+ JavaScript puro

+ React

+ Node.js

+ ambientes mistos (JS + Browser + Node)

**Arquivos possíveis:**

+ eslint.config.js

+ eslint.react.js

+ eslint.node.js
<hr>

# 📂 gitignore/

Modelos .gitignore adequados a:

+ projetos front-end

+ Node.js

+ React

+ ambientes com build (Vite, Webpack etc.)

+ Windows + Mac + Linux

**Arquivo principal:**
default.gitignore
___


# 📂 vscode/

Configurações específicas para o VS Code:

+ settings.json (padrões globais)

+ extensions.json (plugins recomendados)

+ keybindings.json (atalhos úteis)

Aqui você também poderá guardar:

+ temas recomendados

+ snippets globais

+ configurações para formatação ao salvar


# 📂 others/

Configurações genéricas:

+ arquivos .env.example

+ configurações de projetos com Webpack/Vite

+ templates de jsconfig.json e tsconfig.json

+ padrões de estutura para testes

+ configs para Jest, Vitest e Cypress


# 🧱 Padrão de Organização

Cada subpasta seguirá este padrão:

subpasta/  
├── README.md      ← explicação + instruções de uso
├── modelos/       ← configs prontas para copiar/colar
└── exemplos/      ← variações reais utilizadas em projetos
---

# 🚀 Expansões Futuras

Você poderá incluir:

+ Configurações para Docker

+ Configurações para GitHub Actions

+ Configurações para CI/CD

+ Configs para SASS, PostCSS ou Tailwind


# 📝 Observação

A diferença entre 07-tools e 08-configs é:

+ 07-tools → Explica e organiza ferramentas

+ 08-configs → Guarda arquivos de configuração prontos para usar

Trabalham juntos, mas com finalidades diferentes.

Se quiser, posso agora:

👉 Criar as subpastas automaticamente
👉 Criar todos os READMEs internos também
👉 Gerar arquivos reais (como .editorconfig, .prettierrc, .gitignore etc.)

É só pedir.