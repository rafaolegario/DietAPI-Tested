# DietAPI-Tested - User & Meals Management

Este projeto é uma API construída com **Fastify**, **Knex.js** e **SQLite**, com funcionalidades para registro e login de usuários, além de gerenciamento de refeições (CRUD). A aplicação oferece rotas de criação, listagem, atualização e exclusão de refeições, sendo que a autenticação é realizada através de cookies de sessão.

## Tecnologias Utilizadas

- **Fastify**: Framework web rápido e de baixo overhead para Node.js.
- **Knex.js**: Construtor de consultas SQL para Node.js.
- **SQLite**: Banco de dados SQL leve e baseado em arquivos.
- **Vitest**: Framework de testes unitários para testar as rotas da API.
- **Supertest**: Biblioteca para realizar requisições HTTP e testar a API.

## Pré-requisitos

Antes de rodar o projeto, você precisa ter o Node.js instalado. Você pode verificar a instalação do Node.js com o seguinte comando:

```bash
node -v
```
Instalar dependências
Clone o repositório e instale as dependências do projeto:

```
bash git clone <URL_DO_REPOSITORIO> cd <DIRETORIO_DO_PROJETO>

npm install
```
**Variáveis de Ambiente:**

Crie um arquivo .env na raiz do projeto com a seguintes variável:

```
DATABASE_URL= your db path

NODE_ENV = "development" | "prodution" | "test"
```

**Para rodar a aplicação, execute o seguinte comando:**

```
bash
npm run dev
```
Isso irá iniciar a API no http://localhost:3333.


**Licença
Este projeto está licenciado sob a Licença MIT - veja o arquivo LICENSE para mais detalhes.**

