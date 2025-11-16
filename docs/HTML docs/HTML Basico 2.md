Aqui está a versão em HTML completa, pronta para abrir direto no navegador.
Esse modelo já mostra o cabeçalho com o logo, curso, professor, data, aluno e aula, além de uma área principal para o conteúdo da aula e um rodapé simples.

Você pode copiar e colar esse código num arquivo, por exemplo:
modelo-aula.html → e abrir no navegador.

<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Modelo de Aula - Desenvolvimento Web</title>

  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: #f4f6f8;
      color: #333;
    }

    header {
      background-color: #0077cc;
      color: white;
      padding: 20px;
      display: flex;
      flex-direction: column;
      align-items: center;
      text-align: center;
      border-bottom: 5px solid #005fa3;
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
      background-color: white;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      border-radius: 10px;
      margin-top: 20px;
    }

    footer {
      text-align: center;
      padding: 10px;
      color: #666;
      font-size: 0.9em;
      margin-top: 20px;
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 1.4em;
      }
      .info {
        grid-template-columns: 1fr;
      }
    }
  </style>
</head>

<body>
  <header>
    <img src="logo.png" alt="Logo do Curso">
    <h1>Curso: Desenvolvimento Web</h1>
    <div class="info">
      <div><strong>Professor:</strong> João da Silva</div>
      <div><strong>Data:</strong> 13/11/2025</div>
      <div><strong>Aluno:</strong> Maria Souza</div>
      <div><strong>Aula:</strong> Aula 01 - Introdução ao HTML</div>
    </div>
  </header>

  <main>
    <h2>Título do Conteúdo</h2>
    <p>
      Este é o conteúdo da aula. Aqui você pode adicionar textos, imagens, exemplos de código e o que mais desejar.  
      O layout é responsivo e se adapta bem a telas pequenas, como tablets e celulares.
    </p>
  </main>

  <footer>
    <p>© 2025 - Nome da Instituição</p>
  </footer>
</body>
</html>


💡 Dica:

Substitua logo.png por uma imagem real do logo do seu curso (deixe o arquivo na mesma pasta do HTML).

Você pode personalizar as cores do cabeçalho (#0077cc) e da borda inferior (#005fa3) conforme o estilo da instituição.

Quer que eu adicione um espaço no final da página para anotações (tipo um bloco com linhas ou área para o aluno preencher)? Isso deixaria o modelo ainda mais útil para aulas