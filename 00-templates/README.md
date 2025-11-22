# 📁 00-templates

Este diretório reúne **modelos prontos** para criação rápida de aulas, exercícios e projetos.  
O objetivo é padronizar e agilizar meu fluxo de estudo, evitando repetição manual e garantindo organização consistente.

Cada template serve como ponto de partida e pode ser copiado para qualquer pasta do repositório **WebDevJourney**.

Esta pasta reúne **templates reutilizáveis** de:

- Estruturas de pastas (folder-structures)
- Arquivos-base (README, index.html, app.js etc.)
- Modelos para cursos, aulas, exercícios e projetos
- Diagramas e visualizações de estrutura
- Arquivos auxiliares (como o HTML + CSS para desenhar árvores de diretórios)

O objetivo é garantir **padronização, clareza e rapidez** na criação de novos conteúdos.

---

## 📦 Estrutura dos Templates

Atualmente, os seguintes modelos estão disponíveis:

### 1. `aula/`

Modelo para aulas simples, contendo:

- `index.html`
- `app.js`
- `style.css`
- Pasta `assets/`
- Arquivo `notes.md` para anotações da aula

Ideal para acompanhar cursos (CFB Cursos, Curso em Vídeo, Udemy etc).

---

### 2. `exercicio/`

Modelo para exercícios práticos:

- `index.html`
- `script.js`
- `style.css`
- `assets/`
- `instructions.md` para enunciado e resolução

---

### 3. `projeto-basico/`

Modelo para pequenos projetos:

- Estrutura HTML + CSS + JS
- Pastas separadas (`css`, `js`, `assets`)
- `notes.md` para decisões e progresso

---

### 4. `projeto-completo/`

Template mais avançado:

- Estrutura estilo “mini aplicação”
- `src/` com subpastas
- `components/`
- `assets/` organizado
- Pasta `docs/` para documentação interna

---

## 🧭 Como Usar

1. Escolha o template desejado  
2. Copie a pasta para o local onde o projeto/aula/exercício será criado  
3. Renomeie conforme o conteúdo (ex: `aula-05-variaveis`, `exercicio-arrays`, `projeto-todo-list`)  
4. Preencha os arquivos conforme sua necessidade  
5. Ajuste ou expanda os templates conforme evoluir nos estudos  

---

## 📌 Filosofia da Pasta Templates

- Não é obrigatório usar todos os modelos  
- Você pode criar **novos templates** conforme precisar  
- O objetivo é ter algo **prático e claro**, não complicado  
- A pasta deve crescer junto com sua experiência

---

## 🌱 Expansões Futuras (sugestões)

- Template para projetos React  
- Template Node.js  
- Template com Vite  
- Template de documentação técnica  
- Template para estudo de APIs

---

## 📝 Observação Importante

Esses templates servem como base.  
Você é livre para ajustá-los totalmente conforme sua forma de estudar evoluir.

> “Templates são atalhos para a produtividade — mas sempre sob o seu controle.”

## README Parte 2

## 🧱 Estrutura atual

00-templates/
├── folder-structures/
│ ├── base-project/
│ ├── base-course/
│ ├── base-lessons/
│ ├── base-exercises/
│ └── tree-view/ ← contém o HTML + CSS de visualização
│
├── readme-templates/
│ ├── readme-course.md
│ ├── readme-lesson.md
│ ├── readme-project.md
│ └── readme-generic.md
│
└── misc/
└── modelos-diversos.md

Você poderá expandir esta estrutura conforme o avanço dos estudos.

---

## 🧩 Como usar

1. **Copie a estrutura desejada**  
   Exemplo: criar um novo curso  
   - Copiar `folder-structures/base-course/`
   - Renomeá-la para o nome do novo curso  

2. **Adapte o README correspondente**  
   Dentro de cada template existem campos como:  
   - Nome do curso  
   - Link da playlist  
   - Lista de aulas  
   - Objetivo do curso  

3. **Adicione novos templates sempre que achar útil**  
   Exemplos futuros:  
   - Template de APIs  
   - Template de mini-projetos  
   - Template de estudo de documentação oficial  

---

## 🎨 Visualização da Árvore (HTML + CSS)

Dentro de `00-templates/tree-view/` você encontrará:

- `tree-view.html` → arquivo principal para exibir árvores  
- `tree-view.css` → estilos  
- Um comentário indicando onde colar sua árvore gerada

A visualização permite ver qualquer estrutura de pastas com uma aparência limpa e organizada.

---

## 🎯 Objetivo desta pasta

Ser a **base padronizada** do repositório.  
Cada novo curso, aula, projeto ou experimento deve nascer daqui.

Mantendo tudo padronizado, você:

✔ ganha velocidade  
✔ mantém organização  
✔ cria consistência  
✔ facilita leitura e manutenção  
✔ deixa o repositório com “cara de profissional”

---

## 💡 Sugestão de boas práticas

- Sempre que criar algo novo, pergunte:  
  **“Isso merece virar um template?”**
- Separe templates por categorias  
- Versione mudanças significativas para comparar evoluções  

- Mantenha um changelog simples se necessário

---

## README Parte 3

## 💡 ✔️ Regra de ouro: HTML + CSS + JS que pertencem ao mesmo exercício devem ficar juntos

Separar assim…

/courses/CFB/html/exercicio01.html
/courses/CFB/javascript/exercicio01.js

… faria o aprendizado ficar **quebrado**, confuso e difícil de testar.

👉 **Nunca separe arquivos que “trabalham juntos” em pastas diferentes.**

## 🧠 Por quê?

Porque um exercício normalmente é um conjunto:

- um index.html

- um script.js

- um style.css (às vezes)

- imagens usadas

- e às vezes até outros módulos

Eles pertencem ao mesmo contexto, ao mesmo exercício.

Separar esses arquivos por tipo (HTML, JS, CSS) só faz sentido em **documentação**, não em **projetos reais**.

## 📁 ✔️ Como deve ser a estrutura correta dentro de um curso

Exemplo usando o **CFB Cursos**:

courses/
└── cfb/
    ├── aula01/
    │   ├── index.html
    │   ├── script.js
    │   └── style.css
    ├── aula02/
    │   ├── index.html
    │   └── script.js
    ├── aula03/
    │   ├── projeto-relógio/
    │   │   ├── index.html
    │   │   ├── app.js
    │   │   ├── style.css
    │   │   └── assets/
    │   └── anotacoes.md
    └── README.md

### Ou seja

👉 **Cada aula, exercício ou projeto fica completo na sua própria pasta**.
👉 Nada de deixar HTML em uma pasta e JS em outra.
👉 Tudo juntinho, igual projeto real.

## 🚀 Onde entram as outras pastas, então?

✔️ /docs

Serve para **explicações**, conceitos, textos, resumos, não código de exercícios.

✔️ /snippets

Para **códigos pequenos reutilizáveis**, independente de onde você estudou.

Exemplo:
snippets/javascript/array-manipulacoes.md
snippets/html/form-templates.md

✔️ /tutorials

Aqui você também agrupa tudo por fonte, e cada tutorial terá seus exercícios completos dentro dele.

## 🧭 Em resumo

❌ **Errado:**

- HTML em uma pasta

- JS em outra

- CSS em outra

✔️ **Certo:**

- Tudo que faz parte do exercício fica junto na mesma pasta do curso ou tutorial.

Isso te dá:

- organização realista

- facilidade de testar

- clareza absoluta

- zero confusão

- evolução muito mais natural

✦ *Esta pasta vai crescer junto com seu conhecimento.*

✦ *Este README, contém três partes para serem lidas, analizadas e depois unificadas, gerando um arquivo mais claro e conciso.*
