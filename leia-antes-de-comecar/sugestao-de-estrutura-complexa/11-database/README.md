📁 11-database
Estudos, exemplos e práticas com Bancos de Dados

Esta pasta reúne todo o conteúdo relacionado ao universo de bancos de dados, incluindo modelos, consultas, comandos, práticas, comparações, experimentos e ambientes de teste.

Aqui ficarão:

materiais de estudo

scripts SQL

exemplos práticos

ambientes Docker

testes com bancos reais

modelos conceituais, lógicos e físicos

É uma pasta voltada tanto para estudo quanto para referência futura.

🎯 Objetivo

Centralizar tudo sobre bancos de dados em um único local

Criar exemplos reais para consultas SQL

Organizar modelos e diagramas

Ter ambientes configuráveis para testes

Comparar diferentes bancos (SQL e NoSQL)

Servir como base para estudos avançados (ORM, otimização, índices…)

📁 Estrutura das Pastas

11-database/
├── sql/
├── nosql/
├── orm/
├── modeling/
├── docker/
└── tools/

A seguir, o detalhamento:


📂 sql/

Tudo relacionado a bancos relacionais:

PostgreSQL

MySQL

MariaDB

SQLite

SQL Server (se desejar futuramente)

Conteúdo esperado:

scripts .sql

exemplos de DDL (CREATE TABLE)

exemplos de DML (SELECT, INSERT…)

exercícios

joins, subqueries, views, triggers

funções e stored procedures

Exemplo de estrutura interna:

sql/
├── postgresql/
├── mysql/
└── sqlite/

📂 nosql/

Tudo relacionado a bancos não-relacionais, incluindo:

MongoDB

Redis

Firebase / Firestore

Cassandra (futuro, talvez)

Conteúdo sugerido:

comandos básicos

coleções de exemplo

scripts JSON

consultas com agregação

comparação com SQL

Estrutura sugerida:

nosql/
├── mongodb/
├── redis/
└── firestore/

📂 orm/

Estudos e exemplos com ORMs utilizados em projetos web:

Prisma

Sequelize

TypeORM

Mongoose (para Mongo)

Conteúdo:

arquivos de modelo

exemplos de migrações

comparações de sintaxe

padrões de pastas

scripts de seed

estudos sobre relacionamentos

📂 modeling/

Área dedicada à modelagem de dados:

modelos conceituais (DER)

modelos lógicos

normalização

diagramas

regras de negócio

relacionamento entre tabelas

Conteúdo comum:

arquivos .md

imagens ou diagramas

PDFs exportados

notas de estudo

📂 docker/

Ambientes prontos para rodar bancos de dados localmente.

Exemplo:

docker/
├── postgres/
│   ├── docker-compose.yml
│   └── init.sql
├── mysql/
└── mongo/

Isso permite:

subir bancos em segundos

testar consultas

criar ambientes isolados

estudar sem instalar nada na máquina

📂 tools/

Ferramentas e utilitários úteis:

DBeaver

Beekeeper Studio

pgAdmin

DataGrip

scripts de conexão

cheatsheets

Também podem existir:

configurações de clientes CLI

notas sobre backup e restore

templates de conexão Node.js

🧱 Padrão de Organização

Cada subpasta segue:

subpasta/
├── README.md
├── exemplos/
└── templates/


Isso garante consistência e facilidade de expansão.

🚀 Expansões Futuras

Esta pasta permite evoluir para:

benchmarks entre bancos

estudos sobre índices e otimização

replicação e sharding

backups e restore automatizados

versionamento de schema com ORM

✔️ Podemos continuar assim:

Se quiser, eu posso gerar agora:

🔧 1. docker-compose.yml completo para PostgreSQL
🔧 2. Templates SQL de CRUD completos
🔧 3. Um README para a subpasta sql/postgresql
🔧 4. Um guia sobre normalização (1FN, 2FN, 3FN)

Basta pedir!