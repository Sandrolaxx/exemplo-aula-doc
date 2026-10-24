# Visão geral

A arquitetura do projeto donafrost é essencialmente arquitetura de microserviços onde temos 3 principais serviços no back-end, sendo eles:

gerenciamento de produtos

gerenciamento de usuários

marketplace

Temos também os consumidores desses serviços:

front-end web

aplicativo do entregador

Micro: Gerenciamento de Produtos

Aplicação criada com framework Quarkus, que realiza o gerenciamento de produtos, possui uma base de dados PostgreSQL.

Instalar depedências:

```
npm install
# or
yarn install
```

Executar o projeto:

```
npm run dev
# or
yarn dev
```