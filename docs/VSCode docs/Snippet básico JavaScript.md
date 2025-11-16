Aqui está o snippet completo para o VSCode, pronto para copiar e colar no seu javascript.json (ou no global snippets se preferir):

📌 Snippet: Cabeçalho para Aulas de JavaScript
```json
{
  "Cabecalho Aula JS": {
    "prefix": "cabecalhoAulaJS",
    "scope": "javascript, javascriptreact",
    "description": "Insere o cabeçalho padrão das aulas de JavaScript",
    "body": [
      "/* =========================================================",
      "   Curso: JavaScript Essentials",
      "   Aula: ${1:Título da Aula}",
      "   Professor: Luiz Antonio Rodrigues de Oliveira",
      "   Data: ${2:__/__/____}",
      "",
      "   Descrição:",
      "   ${3:Breve descrição do que será abordado na aula.}",
      "",
      "   Observações:",
      "   - Este arquivo faz parte da biblioteca de estudos.",
      "   - Todos os códigos seguem o padrão estabelecido.",
      "========================================================= */",
      "",
      "$0"
    ]
  }
}
```

📌 Onde colocar?

1. Abra o VSCode

1. Pressione Ctrl+Shift+P

1. Digite “Snippets: Configure User Snippets”

1. Escolha javascript.json (ou New Global Snippet File)

1. Cole o código acima

1. Salve!

Agora, sempre que no VSCode você digitar:
*<span style="color:yellow;">cabecalhoAulaJS</span>*  
e pressionar TAB, o cabeçalho completo será inserido automaticamente.

Se você quiser, posso criar também:

✅ Snippet para console.log <!-- Quebra de linha com dois espaços no fim da linha -->  
✅ Snippet para estrutura básica de funções <!-- Quebra de linha com uma (\) ao final da linha -->\
✅ Snippet para comentários rápidos  
✅ Snippet HTML personalizado

Só pedir!