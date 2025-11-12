🧩 1️⃣ — Abrir o gerenciador de snippets do VS Code

Abra o VS Code.

No menu superior, vá em:
Arquivo → Preferências → Snippets do Usuário
(ou em inglês: File → Preferences → User Snippets)

Escolha “JavaScript” (ou “New Global Snippets file” se quiser usar em qualquer linguagem).

Isso vai abrir um arquivo JSON, algo como:

javascript.json

🧾 2️⃣ — Adicionar seu snippet personalizado

Dentro desse arquivo, adicione o seguinte bloco (pode ser logo abaixo das chaves {} principais):

{
  "Cabecalho JS": {
    "prefix": "cabecalho",
    "body": [
      "/* ===========================================================",
      "   📘 Aula: ${1:Título da Aula}",
      "   📅 Data: ${2:dd/mm/aaaa}",
      "   🧑‍💻 Autor: ${3:Seu Nome}",
      "   📝 Descrição:",
      "      ${4:Breve resumo do conteúdo}",
      "",
      "   💡 Observação:",
      "      ${5:Dica ou observação opcional}",
      "   =========================================================== */",
      "",
      ""
    ],
    "description": "Modelo de cabeçalho para aulas de JavaScript"
  }
}

⚙️ 3️⃣ — Como usar o snippet

Crie um novo arquivo .js.

Digite o prefixo:

cabecalho


Pressione Enter ou Tab.
➡️ O cabeçalho completo aparecerá, com campos editáveis (os ${1:}, ${2:} etc.) onde você pode digitar facilmente o título, data, autor, etc.

💡 Dica extra:

Se quiser criar versões diferentes (ex: um cabeçalho para projetos práticos e outro para exercícios rápidos), posso montar variações com ícones e cores diferentes para você.

Quer que eu crie também uma versão “simples e curta” do cabeçalho — ideal para arquivos menores ou exercícios rápidos?