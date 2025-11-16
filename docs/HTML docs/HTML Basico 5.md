qui está a versão completa e evoluída, com tudo funcionando direto no navegador:

✅ NOVOS RECURSOS IMPLEMENTADOS

✔ Botão “Salvar Anotações” – guarda o texto no localStorage

✔ Botão “Limpar Anotações”

✔ Botão “Baixar em TXT” – exporta suas anotações

✔ Modo Claro / Escuro com alternância suave

✔ Campo de anotações editável

✔ Mantive tudo organizado e limpo

✅ HTML COMPLETO (copie e cole)

OBS: Sem markdown — HTML puro pronto pra uso ⬇

<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Modelo de Aula - Desenvolvimento Web</title>

  <style>
    :root {
      --cor-bg: #f4f6f8;
      --cor-texto: #333;
      --cor-header: #0077cc;
      --cor-header-borda: #005fa3;
      --cor-anotacao-linha: #dfe3e8;
      --cor-card-bg: white;
    }

    body.dark {
      --cor-bg: #1c1c1c;
      --cor-texto: #eee;
      --cor-header: #333;
      --cor-header-borda: #555;
      --cor-anotacao-linha: #444;
      --cor-card-bg: #2c2c2c;
    }

    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: var(--cor-bg);
      color: var(--cor-texto);
      transition: background 0.25s, color 0.25s;
    }

    header {
      background-color: var(--cor-header);
      color: white;
      padding: 20px;
      display: flex;
      flex-direction: column;
      align-items: center;
      text-align: center;
      border-bottom: 5px solid var(--cor-header-borda);
    }

    header img {
      width: 120px;
      height: auto;
      margin-bottom: 10px;
    }

    header h1 {
      margin: 5px 0;
      font-size: 1.8em;
    }

    .info {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
      gap: 10px;
      margin-top: 10px;
      width: 100%;
      max-width: 800px;
    }

    .info div {
      background-color: rgba(255, 255, 255, 0.15);
      padding: 10px;
      border-radius: 6px;
      font-size: 0.95em;
    }

    main {
      padding: 20px;
      max-width: 900px;
      margin: 0 auto;
      background-color: var(--cor-card-bg);
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      border-radius: 10px;
      margin-top: 20px;
      transition: background 0.25s;
    }

    footer {
      text-align: center;
      padding: 10px;
      color: #666;
      font-size: 0.9em;
      margin-top: 20px;
    }

    /* Área de anotações */
    .anotacoes {
      max-width: 900px;
      margin: 30px auto;
      background: repeating-linear-gradient(
        var(--cor-card-bg),
        var(--cor-card-bg) 28px,
        var(--cor-anotacao-linha) 29px,
        var(--cor-anotacao-linha) 30px
      );
      border: 2px solid #ccc;
      border-radius: 10px;
      padding: 20px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      transition: background 0.25s;
    }

    .anotacoes h2 {
      text-align: center;
      color: var(--cor-header);
      margin-top: 0;
      margin-bottom: 15px;
    }

    .bloco-editavel {
      min-height: 250px;
      white-space: pre-wrap;
      font-family: 'Courier New', monospace;
      font-size: 1em;
      line-height: 30px;
      outline: none;
    }

    /* Botões */
    .botoes {
      margin-top: 15px;
      text-align: center;
    }

    button {
      background: var(--cor-header);
      border: none;
      color: white;
      padding: 10px 18px;
      margin: 5px;
      border-radius: 6px;
      cursor: pointer;
      transition: 0.2s;
      font-size: 0.95em;
    }

    button:hover {
      background: var(--cor-header-borda);
    }

    @media (max-width: 600px) {
      header h1 { font-size: 1.4em; }
      .info { grid-template-columns: 1fr; }
      .anotacoes { padding: 10px; }
    }
  </style>
</head>

<body>
  <header>
    <img src="logo.png" alt="Logo do Curso">
    <h1>Curso: Desenvolvimento Web</h1>
    <div class="info">
      <div><strong>Professor:</strong> João da Silva</div>
      <div><strong>Data:</strong> 14/11/2025</div>
      <div><strong>Aluno:</strong> Maria Souza</div>
      <div><strong>Aula:</strong> Aula 01 - Introdução ao HTML</div>
    </div>
  </header>

  <main>
    <h2>Título do Conteúdo</h2>
    <p>
      Este é o conteúdo da aula. Aqui você pode adicionar textos, imagens, exemplos de código e o que mais desejar.
    </p>
  </main>

  <section class="anotacoes">
    <h2>📝 Anotações do Aluno</h2>

    <div class="bloco-editavel" contenteditable="true" id="campoAnotacoes">
      Clique aqui e comece a digitar suas anotações...
    </div>

    <div class="botoes">
      <button onclick="salvar()">Salvar Anotações</button>
      <button onclick="limpar()">Limpar</button>
      <button onclick="baixar()">Baixar TXT</button>
      <button onclick="modoEscuro()">Modo Claro / Escuro</button>
    </div>
  </section>

  <footer>
    <p>© 2025 - Nome da Instituição</p>
  </footer>

  <script>
    const campo = document.getElementById("campoAnotacoes");

    // Carregar anotações salvas
    window.onload = () => {
      const salvo = localStorage.getItem("anotacoes");
      if (salvo) campo.innerText = salvo;
    };

    function salvar() {
      localStorage.setItem("anotacoes", campo.innerText);
      alert("Anotações salvas!");
    }

    function limpar() {
      if (confirm("Tem certeza que deseja limpar as anotações?")) {
        campo.innerText = "";
        localStorage.removeItem("anotacoes");
      }
    }

    function baixar() {
      const texto = campo.innerText;
      const blob = new Blob([texto], { type: "text/plain" });

      const link = document.createElement("a");
      link.href = URL.createObjectURL(blob);
      link.download = "anotacoes.txt";
      link.click();
    }

    function modoEscuro() {
      document.body.classList.toggle("dark");
    }
  </script>

</body>
</html>

✔ Tudo funcionando direto no navegador!
Agora você tem:

Área de anotações editável

Salvar / Limpar / Baixar TXT

Modo claro/escuro

Layout bonito e profissional

Se quiser, posso adicionar:

🔶 Impressão em PDF (com layout especial sem cores)
🔶 Salvar automaticamente enquanto digita
🔶 Anotações em abas (Aula 1, Aula 2, Aula 3…)
🔶 Tema personalizado da instituição
🔶 Versão com fontes Google mais modernas