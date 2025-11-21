Aqui vai um VSCode snippet completo, NÃO minimalista, já com estrutura de pastas + README + arquivos padrão para criar automaticamente uma aula/exercício/projeto no formato que definimos.

Esse snippet cria:

/nome-da-aula/
│── index.html
│── style.css
│── app.js
│── README.md
│── assets/
│── snippets/
│── notes/


Perfeito para cursos (CFB, Udemy, Guanabara), projetos de estudo, exercícios e qualquer aula.

# ✅ VSCode Snippet – Criar Estrutura Completa de Aula/Projeto
### 📌 Instruções

1. No VSCode, abra:
    **File → Preferences → User Snippets**

2. Escolha **New Global Snippets file** (ou selecione um existente).

3. Crie/cole o conteúdo abaixo.

4. Use no editor digitando:
**👉 aulaestrutura**
…e pressione **TAB.**


# 🧩 Snippet Completo

{
  "Criar Estrutura Completa de Aula/Projeto": {
    "prefix": "aulaestrutura",
    "body": [
      "${1:nome-aula}/",
      "\tREADME.md",
      "\tindex.html",
      "\tstyle.css",
      "\tapp.js",
      "\tassets/",
      "\tsnippets/",
      "\tnotes/",
      "",
      "----- Conteúdo sugerido para os arquivos criados -----",
      "",
      "# Arquivo: ${1:nome-aula}/README.md",
      "",
      "# ${1:nome-aula}",
      "",
      "📝 Descrição:",
      "- ${2:Descreva aqui o que esta aula/projeto aborda.}",
      "",
      "## 🎯 Objetivo",
      "- ${3:Explique o objetivo principal do exercício ou projeto.}",
      "",
      "## 📂 Estrutura",
      "- **index.html** → HTML principal",
      "- **style.css** → Estilos",
      "- **app.js** → Script JS principal",
      "- **assets/** → Imagens, vídeos, arquivos estáticos",
      "- **snippets/** → Códigos auxiliares",
      "- **notes/** → Anotações adicionais",
      "",
      "## ▶️ Como executar",
      "Abra o arquivo *index.html* no navegador ou utilize uma extensão como Live Server.",
      "",
      "------------------------------",
      "",
      "# Arquivo: index.html",
      "",
      "<!DOCTYPE html>",
      "<html lang=\"pt-BR\">",
      "<head>",
      "    <meta charset=\"UTF-8\" />",
      "    <meta name=\"viewport\" content=\"width=device-width, initial-scale=1.0\" />",
      "    <title>${1:nome-aula}</title>",
      "    <link rel=\"stylesheet\" href=\"style.css\" />",
      "</head>",
      "<body>",
      "    <h1>${1:nome-aula}</h1>",
      "    <script src=\"app.js\"></script>",
      "</body>",
      "</html>",
      "",
      "------------------------------",
      "",
      "# Arquivo: style.css",
      "",
      "body {",
      "    font-family: Arial, sans-serif;",
      "    background: #f4f4f4;",
      "    padding: 20px;",
      "}",
      "",
      "------------------------------",
      "",
      "# Arquivo: app.js",
      "",
      "console.log(\"${1:nome-aula} carregado com sucesso!\");"
    ],
    "description": "Cria automaticamente a estrutura completa para uma nova aula/exercício/projeto"
  }
}

🌙 Pronto, Luiz!

Agora é só:

digitar aulaestrutura

apertar TAB

e o VSCode cria tudo automático

Esse snippet é didático, organizado e ótimo para estudar a estrutura.

Se quiser, posso futuramente adicionar:

✅ snippet para múltiplas aulas
✅ snippet para projetos maiores
✅ snippet para JavaScript modular
✅ snippet para React, Node ou Typescript
