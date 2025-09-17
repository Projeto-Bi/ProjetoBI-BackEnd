# ⚙️ Projeto Banca de Jornal - Repositório do Back-end

Este repositório contém o servidor e a API responsável por todas as regras de negócio e comunicação com o banco de dados do sistema.

## 📖 Tabela de Conteúdos

- [Arquitetura e Tecnologias](#-arquitetura-e-tecnologias)
- [Pré-requisitos](#-pré-requisitos)
- [Configuração do Ambiente](#-configuração-do-ambiente)
- [Como Executar a Aplicação](#-como-executar-a-aplicação)
- [Endpoints da API](#-endpoints-da-api)
- [Como Executar os Testes](#-como-executar-os-testes)
- [Variáveis de Ambiente](#-variáveis-de-ambiente)

## 🏗️ Arquitetura e Tecnologias

- **Linguagem:** (Ex: Node.js, Python, Java)
- **Framework:** (Ex: Express, Django, Spring Boot)
- **Banco de Dados:** (Ex: PostgreSQL, MongoDB)
- **Arquitetura:** (Ex: Monolítica, Microsserviços)
- **Autenticação:** (Ex: JWT - JSON Web Tokens)

## ✅ Pré-requisitos

- [Nome da Tecnologia, ex: Node.js] (versão X.X.X)
- [Nome da Tecnologia, ex: Docker] (opcional)

## ⚙️ Configuração do Ambiente

1.  **Clone o repositório:** `git clone ...`
2.  **Acesse a pasta do projeto:** `cd nome-do-repo-backend`
3.  **Instale as dependências:**
    ```bash
    npm install
    ```
4.  **Configure as variáveis de ambiente:**
    - Copie o arquivo `.env.example` para um novo arquivo chamado `.env`.
    - Preencha as variáveis no arquivo `.env` com suas configurações locais (banco de dados, segredos, etc.).

## 🚀 Como Executar a Aplicação

Para iniciar o servidor em modo de desenvolvimento (com hot-reload):
```bash
npm run dev
```
O servidor estará disponível em `http://localhost:8080`.

## 🔗 Endpoints da API

A documentação completa da API está disponível via Swagger/OpenAPI. Após iniciar o servidor, acesse:

**[http://localhost:8080/api-docs](http://localhost:8080/api-docs)**

**Recursos Principais:**
- `GET /produtos`: Lista todos os produtos.
- `POST /vendas`: Registra uma nova venda.
- `GET /relatorios/financeiro`: Retorna o relatório financeiro.

## 🧪 Como Executar os Testes

Para rodar todos os testes (unitários e de integração):
```bash
npm test
```

## 🔑 Variáveis de Ambiente

As seguintes variáveis são necessárias no arquivo `.env`:

- `PORT`: Porta em que o servidor irá rodar.
- `DATABASE_URL`: URL de conexão com o banco de dados.
- `JWT_SECRET`: Segredo para a geração de tokens de autenticação.
