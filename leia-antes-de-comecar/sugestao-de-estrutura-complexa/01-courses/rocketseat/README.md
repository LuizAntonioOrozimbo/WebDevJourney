# 📄 README.md — Pasta rocketseat/

Local sugerido:

WebDevJourney/01-courses/rocketseat/README.md

Conteúdo em Markdown puro:

# Rocketseat

Este diretório armazena todos os estudos, anotações, desafios, projetos e materiais desenvolvidos nos cursos, trilhas e eventos da **Rocketseat**.

A Rocketseat é focada em ensinar tecnologias modernas para desenvolvimento web e mobile, com forte ênfase em **JavaScript, React, Node.js e React Native**.

---

## 🚀 Sobre a Rocketseat

A Rocketseat oferece diversos formatos de conteúdo:

- **Trilhas e formações** (Discover, Ignite, Explorer)
- **Cursos gratuitos**
- **Aulas avulsas**
- **Workshops**
- **NLW — Next Level Week**
- **Maratonas e desafios**

Cada um desses conteúdos pode (e deve) ser organizado separadamente.

---

## 📁 Estrutura sugerida

ocketseat/
├── discover/
├── explorer/
├── ignite/
├── nlw/
├── workshops/
└── outros/


Você pode expandir ou ajustar conforme os cursos que fizer.

---

## 📦 Estrutura interna por curso/trilha

Cada trilha ou curso deve ter sua própria pasta contendo:

nome-da-trilha-ou-curso/
├── aulas/
├── desafios/
├── projetos/
├── anotações/
└── README.md


Por exemplo:

rocketseat/
└── ignite/
└── reactjs-2025/
├── aulas/
├── desafios/
├── projetos/
├── anotações/
└── README.md


---

## 📝 O que colocar no README interno

Cada subcurso/trilha deve ter seu próprio README com:

- Nome da trilha/curso
- Link oficial
- Instrutor
- Tecnologias estudadas
- Conteúdo abordado
- Desafios feitos
- Progresso
- Observações ou aprendizados importantes

Exemplo:

```markdown
# Ignite — Trilha ReactJS

Instrutor: Diego Fernandes  
Link: https://app.rocketseat.com.br/

## Conteúdo
- Hooks avançados
- Context API
- Styled Components
- Testes automatizados
- Performance e otimizações

## Progresso
🔵🔵⚪⚪⚪ 40% concluído


## ✔️ Dicas de organização

+ O Ignite e o Explorer usam versões diferentes de projetos → sempre separar por ano ou edição.

+ O NLW é sempre dividido por tema e stack (Node, React, Mobile).

+ Caso participe de vários NLWs, organize assim:


nlw/
├── nlw-2024-connect/
├── nlw-2024-expert/
└── nlw-2025-esports/


+ Para projetos grandes, mova versões finalizadas para:

03-my-projects/production/


Se quiser, eu também posso:

🔹 Criar um modelo oficial da Rocketseat com todas as trilhas
🔹 Criar uma estrutura completa por dentro de cada trilha
🔹 Gerar READMEs internos automáticos
🔹 Criar arquivos iniciais para projetos (React, Node, etc.)