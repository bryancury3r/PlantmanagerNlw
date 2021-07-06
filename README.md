# Plantmanager

<h1 align="center">
    <img alt="PlantManager" src="" height="200px" />
    <br>Next Level Week #5 - Trilha React Native<br/>
    TypeScript | Expo | React Native
</h1>

<p align="center">
    <img alt="Made by Rocketseat" src="https://img.shields.io/badge/made%20by-Rocketseat-%237519C1?style=flat-square"><br/>
</p>    

<p align="center">
    <a href="#bookmark-sobre-o-projeto">Sobre</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
    <a href="#rocket-tecnologias-utilizadas">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
    <a href="#boom-como-executar">Como Executar</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
    <a href="#memo-licença">Licença</a>
</p>

[![NPM](https://img.shields.io/npm/l/react)](https://github.com/bryancury3r/PlantmanagerNlw/blob/main/LICENSE)

## :bookmark: Sobre o Projeto

O **PlantManager** é uma aplicação Mobile que tem como intuito cadastrar plantas e notificar ao seu usuário quando ele deve regar uma determinada planta que o mesmo cadastrou. Exibindo a quantidade de água necessária para a sua rega, quantas regas diárias ou semanais, entre outras.

Projeto idealizado exclusivamente para o cuidado de plantas.

## Layout mobile

![Mobile 1](https://github.com/bryancury3r/PlantmanagerNlw/blob/main/images/mobile1.png) ![Mobile 2](https://github.com/bryancury3r/PlantmanagerNlw/blob/main/images/Screenshot%20from%202021-07-06%2020-26-37.png) ![Mobile 3](https://github.com/bryancury3r/PlantmanagerNlw/blob/main/images/mobile2.png) ![Mobile 4](https://github.com/bryancury3r/PlantmanagerNlw/blob/main/images/mobile5.png)


Essa aplicação foi realizada durante a **Next Level Week #5**, projeto da [Rocketseat](https://rocketseat.com.br/).

## :rocket: Tecnologias Utilizadas

- [Axios](https://axios-http.com/)
- [date-fns](https://date-fns.org/)
- [Expo](https://expo.io/)
- [json-server](https://github.com/typicode/json-server)
- [Lottie](https://lottiefiles.com/)
- [NPM](https://www.npmjs.com/)
- [ReactJS](https://reactjs.org/)
- [React Native](https://reactnative.dev/)
- [React Navigation](https://reactnavigation.org/)
- [Typescript](https://www.typescriptlang.org/)

## 💡 Como Executar

- ### **Pré-requisitos**

  - É **necessário** possuir o **[Node.js](https://nodejs.org/en/)** instalado no computador.
  - É **necessário** possuir o **[Git](https://git-scm.com/)** instalado e configurado no computador.
  - É **essencial** possuir o **[Expo](https://expo.io/)** e o **[json-server](https://github.com/typicode/json-server)** instalados no computador.
  - Por fim, é **preciso** ter um gerenciador de pacotes seja o **[Yarn](https://yarnpkg.com/)** ou **[NPM](https://www.npmjs.com/)**.

1. Faça um clone do repositório:

```sh
  $ git clone https://github.com/bryancury3r/PlantmanagerNlw.git
```

2. Executando a Aplicação:

```sh
  # Instalando as dependências do projeto.
  $ npm install # ou yarn install
  # Inicie a aplicação mobile
  $ expo start # npm run start ou yarn start
```

3. Executando fake API com json-server:

```sh
  # No terminal
  $ json-server ./src/services/server.json --host YOUR_IP --port YOUR_PORT --delay 750
```

## :memo: Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

<sup>Projeto desenvolvido com a tutoria de [Rodrigo Gonçalves](https://github.com/rodrigorgtic), da [Rocketseat](https://rocketseat.com.br/).</sup>
