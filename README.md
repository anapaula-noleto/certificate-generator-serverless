## ✨ Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- [Node.js](https://nodejs.org/en/)
- [Typescript](https://www.typescriptlang.org/)
- [Serverless Framework](serverless.com/)
- [Puppeteer](https://github.com/puppeteer/puppeteer)
- [Amazon Lambda](https://aws.amazon.com/pt/lambda/)

## 💻 Projeto

O projeto tem como responsabilidade gerar um certificado para um usuário e a possibilidade de pesquisar a validade de um certificado.

## 🚀 Como executar

- Clone o repositório e acesso o diretório

### Para rodar localmente

- Rode `npm` para instalar as dependências
- Rode `npm run dynamodb:install` para baixar o DynamoDB localmente
- Rode `npm run dynamo:start` para iniciar o banco de dados em ambiente local
- Rode, em outro terminal, o `npm run dev` para iniciar a aplicação em ambiente local

### Para fazer o deploy

- Configurar as credenciais do usuário
- Rode `npm run deploy` para subir o projeto para AWS Lambda
