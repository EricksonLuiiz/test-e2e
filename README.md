
# API de Autenticação - Estudo de Testes E2E

<p align="center">
  <h2 align="center">🔒 API de Testes End-to-End</h2>
</p>

## 📋 Sobre

API HTTP desenvolvida em Node.js para demonstrar implementação de testes end-to-end, com sistema de autenticação simples e rotas.

## 🛠️ Tecnologias

- Node.js
- Mocha
- Supertest
- Assert

## ✨ Funcionalidades

- Autenticação de usuários
- Página de contato
- Tratamento de rotas 404

## 🔍 Rotas Disponíveis

| Rota |  Método | Descrição |
|------|---------|-----------|
| `/contact` | GET | Página de contato |
| `/login` | POST | Autenticação |

## 🚀 Como Executar

1. Clone o repositório
2. Instale as dependências:
```bash
npm install
```
## 📡 Exemplo de Requisiição e Teste
```curl -i -X POST --data '{"username": "EricksonDelfino","password": "e2e"}' localhost:8000/login```
```npm run test:cov``` 

## 📚 Documentação dos Testes
Os testes cobrem:

- Status HTTP
- Conteúdo das respostas
- Autenticação
- Tratamento de erros
