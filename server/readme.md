# Server Node.js para Frontend Angular

Este server entrega um backend funcional para o frontend Angular.
Permite os usuarios utilizarem o CRUD (Create, Read, Update, Delete) nos produtos.
O server utiliza Express e interage com um JSON para gerenciar os produtos

## Tabela de Conteúdos

- [Features](#features)
- [Início](#inicio)
  - [Pre requisitos](#pre-requisitos)
  - [Instalação](#instalacao)
- [Uso](#uso)
- [Licença](#licença)

## Features

- **Express Server:** The server is built with Express, providing a robust and scalable backend.
- **CRUD Operations:** Supports Create, Read, Update, and Delete operations on product data.
- **JSON Data Storage:** Products are stored and manipulated within a JSON file instead of a traditional database.

## Inicio

### Pre-requisitos

Antes ded iniciar, voce tem que instalar o seguinte:

- [Node.js](https://nodejs.org/) and [npm](https://www.npmjs.com/)

### Instalacao

1. Instale as dependencias:
   ```bash
   npm install
   ```

## Uso

1. Inicie o server:
   ```bash
   npm start
   ```
2. O server estara funcionando no http://localhost:3000/.

3. O frontend Angular ira interagir com os endpoints da API para performar o CRUD nos produtos.

## Licença

Este projeto usa a licença MIT
