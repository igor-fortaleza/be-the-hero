# Plataforma de Incidentes para ONGs

Este projeto foi desenvolvido em 2020 junto ao curso da 11ª edição da Semana OmniStack de ReactJS e JavaScript com Express. O objetivo é fornecer uma plataforma robusta que permite a ONGs gerenciar e visualizar incidentes e casos, facilitando a organização e o acesso à informação.

<p align="center">
  <img src="./docs/tela_inicial.png" alt="Tela Principal">
</p>

## Funcionalidades

- **Cadastro de ONGs**: Permite que organizações não governamentais se cadastrem na plataforma para gerenciar seus casos.
- **Login de Usuários**: Autenticação de usuários para acesso seguro.
- **Cadastro e Listagem de Casos**: ONGs podem cadastrar e listar incidentes, incluindo detalhes como descrição, data do incidente, e recursos necessários.
- **Visualização de Detalhes do Caso**: Usuários podem visualizar detalhes de cada caso individualmente.
- **Resposta aos Incidentes**: Facilita a comunicação entre a ONG e voluntários ou interessados em ajudar.

## Tecnologias Utilizadas

- **ReactJS**: Framework de desenvolvimento Web.
- **Express**: Framework para desenvolvimento de APIs.
- **Knex**: Framework para construção de SQL com facilidade e segurança. +Features

## Executando o Projeto

### Pré-requisitos

- **Node.js**
- **NPM** ou **Yarn**

### Execução

1. Clone o repositório

2. Intsale as dependencias dos Projetos:

- No diretório _/backend_ execute:

```bash
   yarn
   #ou
   npm install
```

- No diretório _/frontend_ execute:

```bash
   yarn
   #ou
   npm install
```

3. Execute o Backend e o Front-end da aplicação

- No diretório _/backend_ execute:

```bash
   yarn start
```

- No diretório _/frontend_ execute:

```bash
   yarn start
```

### Migrations

Se você tiver partindo de um novo banco Sqlite, você precisara rodar as migrations para o novo Banco de Dados. No **backend** execute:

```bash
  yarn knex migrate:latest
```
