<h1 align="center">
  <img src=".github/logo.svg" alt="Be The Hero">
</h1>

<h3 align="center">
  Be The Hero - Conecte sua ONG com pessoas que desejam lhe ajudar.
</h3>

<p align="center">
  <a href="#%EF%B8%8F-projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-semana-omnistack-110">Semana OmniStack 11.0</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-instalação-execução-e-desenvolvimento">Instalação, execução e desenvolvimento</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-como-contribuir">Como contribuir</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-licença">Licença</a>
</p>

<p id="insomniaButton" align="center">
  <a href="https://insomnia.rest/run/?label=Be%20The%20Hero&uri=https%3A%2F%2Fraw.githubusercontent.com%2FEliasGcf%2Fbe-the-hero%2Fmaster%2FInsomnia.json" target="_blank"><img src="https://insomnia.rest/images/run.svg" alt="Run in Insomnia"></a>
</p>

## 🦸‍♀️ Projeto

Com essa aplicação, e por meio do front-end web, as ONGs podem informar sobre seus casos, necessidades e o valor necessário para solucionar o problema.

A partir dessas informações, e por meio do front-end mobile, pessoas comuns, ou seja, toda a sociedade pode contruibir com um determinado caso e ser o herói de dia para aquela ONG.

É visado por meio da interação entre ONG e comunidade: A ampliação da área de atuação da ONG, o aumento da velocidade e eficácia na resolução dos problemas.

<details><summary>Layout do Projeto</summary>
  <img src=".github/layout.gif" alt="Layout GIF">
</details>

## 🚀 Tecnologias

Esta aplicação foi desenolvida com as tecnologias abaixo:

- [Node.js](https://nodejs.org/en/)
- [ReactJS](https://reactjs.org/)
- [React Native](https://reactnative.dev/)
- [Expo](https://expo.io/)
- [Express](https://expressjs.com/pt-br/)
- [PostgreSQL](https://www.postgresql.org/)
- [Sequelize](https://sequelize.org/)
- [Nodemon](https://nodemon.io/)
- [Sucrase](https://github.com/alangpierce/sucrase)
- [React Router DOM](https://reacttraining.com/react-router/)
- [React Navigation](https://reactnavigation.org/)
- [React Icons](https://react-icons.netlify.com/#/)
- [UnForm](https://unform.dev/) [💜](https://rocketseat.com.br/)
- [Styled Components](https://styled-components.com/)
- [Axios](https://github.com/axios/axios)
- [Eslint](https://eslint.org/)
- [Prettier](https://prettier.io/)
- [EditorConfig](https://editorconfig.org/)

## ![Alt LogoRocketseat](.github/logo-rocketseat.svg) Semana OmniStack 11.0

A [Semana OmniStack](https://rocketseat.com.br/week/inscricao/11.0) é um evento 100% online e gratuita, onde a [Rocketseat](https://github.com/rocketseat) junto com seu CTO [Diego Fernandes](https://github.com/diego3g) e mais toda a comunidade, desenvolvem uma aplicação completa, desde o banco de dados, back-end, até o front-end web e mobile, tudo isso utilizando a stack JavaScript, ou seja, Node.js no back-end, ReactJS para web e React Native para mobile.

## 💻 Instalação, execução e desenvolvimento

Faça um clone desse repositório.

### Pré-requisitos

- [Node.js](https://nodejs.org/en/)
- [PostgreSQL](https://www.postgresql.org/)
- [Yarn](https://yarnpkg.com/) ou [npm](https://www.npmjs.com/)
- [Expo](https://expo.io/)

### Backend

- A partir da raiz do projeto, entre na pasta rodando `cd server`;
- Rode `yarn` para instalar sua dependências;
- Rode `cp .env.example .env` e preencha o arquivo `.env` com SUAS variáveis ambiente;
- Caso não tenha criado o banco de dados rode `yarn sequelize db:create`;
- Rode `yarn sequelize db:migrate` para executar as migrations;
- Importe o arquivo `Insomnia.json` no Insomnia ou clique no botão [Run in Insomnia](#insomniaButton)`;

### Web

_ps: Antes de executar, lembre-se de iniciar o backend deste projeto_

- A partir da raiz do projeto, entre na pasta do frontend web rodando `cd web`;
- Rode `yarn` para instalar as dependências;
- Rode `yarn start` para iniciar o client web;

### Mobile

_ps: Antes de executar, lembre-se de iniciar o backend deste projeto_

- A partir da raiz do projeto, entre na pasta do frontend web rodando `cd mobile`;
- Rode `yarn` para instalar as dependências;
- Rode `yarn start` ou `expo start` para iniciar o bundle com o expo;
- Caso vá utilizar emulador, basta clicar na opção `Run on ...`;
- Caso vá utilizar seu smartphone, com o app do expo escanei o QRCODE;

## 🤔 Como contribuir

- Faça um fork desse repositório;
- Cria uma branch com a sua feature: `git checkout -b minha-feature`;
- Faça commit das suas alterações: `git commit -m 'feat: Minha nova feature'`;
- Faça push para a sua branch: `git push origin minha-feature`;

## 📝 Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](https://github.com/EliasGcf/be-the-hero/blob/master/LICENSE) para mais detalhes.

---

Feito com 💜 by [LucasOliveiraS](https://www.linkedin.com/in/eliasgcf/)
