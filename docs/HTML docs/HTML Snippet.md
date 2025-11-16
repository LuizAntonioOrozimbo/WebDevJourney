Aqui vai um snippet completo de HTML pronto para ser adicionado ao VS Code — ele cria um modelo básico de página com um cabeçalho contendo Curso, Professor, Data, Aluno e Aula, tudo bem organizado e comentado.

🧩 Snippet HTML — “modelo-aula”
Passo 1️⃣ — Crie o arquivo de snippets no VSCode

No VS Code, abra o Command Palette (Ctrl + Shift + P ou Cmd + Shift + P no Mac).

Pesquise por “Configure User Snippets”.

Escolha html.json (ou um arquivo global).

Passo 2️⃣ — Cole o snippet abaixo:
{
  "Modelo de Aula HTML": {
    "prefix": "modelo-aula",
    "body": [
      "<!DOCTYPE html>",
      "<html lang=\"pt-BR\">",
      "<head>",
      "  <meta charset=\"UTF-8\">",
      "  <meta name=\"viewport\" content=\"width=device-width, initial-scale=1.0\">",
      "  <title>${1:Título da Página}</title>",
      "  <style>",
      "    body {",
      "      font-family: Arial, sans-serif;",
      "      margin: 20px;",
      "      background-color: #f8f9fa;",
      "      color: #333;",
      "    }",
      "    header {",
      "      background-color: #0077cc;",
      "      color: white;",
      "      padding: 20px;",
      "      border-radius: 10px;",
      "      margin-bottom: 20px;",
      "    }",
      "    header h1 { margin: 0; }",
      "    .info {",
      "      display: grid;",
      "      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));",
      "      gap: 10px;",
      "      margin-top: 10px;",
      "    }",
      "    .info div {",
      "      background: rgba(255, 255, 255, 0.15);",
      "      padding: 10px;",
      "      border-radius: 6px;",
      "    }",
      "    main {",
      "      padding: 10px;",
      "    }",
      "  </style>",
      "</head>",
      "<body>",
      "  <header>",
      "    <h1>${2:Curso: Desenvolvimento Web}</h1>",
      "    <div class=\"info\">",
      "      <div><strong>Professor:</strong> ${3:Nome do Professor}</div>",
      "      <div><strong>Data:</strong> ${4:__/__/____}</div>",
      "      <div><strong>Aluno:</strong> ${5:Seu Nome}</div>",
      "      <div><strong>Aula:</strong> ${6:Aula 01 - Introdução}</div>",
      "    </div>",
      "  </header>",
      "  <main>",
      "    <h2>${7:Título do Conteúdo}</h2>",
      "    <p>${8:Escreva aqui o conteúdo da aula...}</p>",
      "  </main>",
      "</body>",
      "</html>"
    ],
    "description": "Modelo básico de HTML com cabeçalho (Curso, Professor, Data, Aluno, Aula)"
  }
}

✅ Como usar

Depois de salvar o snippet:

Crie um novo arquivo .html.

Digite modelo-aula e pressione Tab.

O VSCode vai gerar automaticamente a estrutura com campos editáveis (Curso, Professor, etc.).

Quer que eu adicione também o logo do curso no cabeçalho (com um espaço para imagem)? Isso deixaria o modelo mais completo e visual.