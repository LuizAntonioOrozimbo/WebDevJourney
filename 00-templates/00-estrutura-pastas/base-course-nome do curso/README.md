# 🧩 MODELO COMPLETO — AULA / EXERCÍCIO / PROJETO

Use essa estrutura sempre que estiver registrando uma aula prática, um exercício ou um mini-projeto.

nome-do-curso/
└── 01-nome-da-aula-ou-exercicio/
    ├── README.md
    ├── index.html
    ├── style.css
    ├── script.js
    ├── assets/
    │   ├── imagens...
    │   └── icones...
    └── extras/

        ├── anotações.md

        └── versões-anteriores/

## 🧪 Aula/Exercício: Nome da Aula

## 🎯 Objetivo

Explique brevemente o propósito desta aula:

- qual conceito foi aprendido,
- qual problema foi resolvido,
- por que isso é importante.

Exemplo:
> Nesta aula aprendemos como utilizar `console.log()` para exibir mensagens e valores no console do navegador. Também entendemos como ligar um arquivo JavaScript a um HTML.
---

## 📂 Estrutura dos Arquivos

index.html → estrutura HTML da aula

style.css → estilos relacionados (opcional)

script.js → código JavaScript da aula

assets/ → imagens, logos e arquivos estáticos

extras/ → anotações ou versões antigas

---

## 🧠 Conceitos Aprendidos

Liste os pontos importantes aqui:

- Como funciona o `<script>` no HTML  
- Como conectar `script.js`  
- Como usar `console.log()`  
- Como o navegador executa JavaScript  
- Diferença entre DOM e console  
- Qualquer detalhe relevante da explicação  

---

## 🧑‍💻 Código Principal

### 📄 *index.html*

    ```html
        <!DOCTYPE html>
        <html lang="pt-BR">
        <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Aula 01</title>
        </head>
        <body>
        <h1>Teste de Console</h1>
        
        <script src="script.js"></script> 
        </body>
        </html>
    ```

### 📄 script.js

    ```js
        console.log("Olá, mundo!");
    ```

## 📝 Notas da Aula

- Detalhes que o professor comentou

- Coisas que você entendeu

- Dúvidas que surgirem

- Links importantes

## 🚀 Resultado

Descreva o que deveria acontecer:

Abrir o console do navegador (F12 → Console) e ver a mensagem **“Olá, mundo!”** impressa.

## 🔗 Material de Referência

- Link da aula (se for de YouTube/Curso)

- Documentação relacionada

---

## 🧩 **QUANDO USAR ESSA ESTRUTURA?**

Use sempre que for:

✔ Aula prática  
✔ Exercício da Udemy / CFB / Guanabara  
✔ Projeto curto  
✔ Teste de conceito  
✔ Experimento rápido  
✔ Mini-projeto de tutorial  
✔ Dúvida que você está explorando  

Não importa se é pequeno: **tudo que tem HTML/CSS/JS juntos fica na mesma pasta.**

---

## 🧩 **E QUANDO SEPARAR POR TECNOLOGIA?**

A separação por tecnologia deve existir apenas em:

### ✔ Documentação teórica → `/docs/...`

- HTML  
- CSS  
- JavaScript  
- Git  
- VSCode  
- React  
- etc.

### ✔ Snippets → `/snippets/...`

Blocos curtos, úteis e reaproveitáveis:

- funções prontas  
- animações CSS  
- regexes  
- helpers JS  
- trechos de HTML  
- exemplos comuns  

### ❌ Nunca separar arquivos práticos (HTML/JS/CSS) que pert

Porque isso quebra o contexto e dificulta rodar.

---
