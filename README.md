<div align="center">
  <img src="src/assets/capa.png">
</div>

<br>

## 📋 Sobre

A aplicação GoRestaurant é do seguimento Delivery onde os clientes podem encomendar suas comidas. Possue função para salvar nos favoritos, foi criada no bootcamp GoStack como desafio 11 para praticar e fixar os conceitos aprendidos no decorrer dos estudos em **React Native** e consumo de uma Fake API.


## 🚀 Tecnologias Utilizadas

Foi desenvolvida usando as seguintes tecnologias:

### Front-end:

- [React Native](https://reactnative.dev/)
- [Axios](https://github.com/axios/axios)
- [Styled-components](https://styled-components.com)
- [TypeScript](https://www.typescriptlang.org)

### Back-end:

- [JSON Server](https://github.com/typicode/json-server)


## 📦 Como Baixar e Executar o Projeto Front-end

```bash

  # Para clonar o repositório para seu computador

  $ git clone https://github.com/eloilsondosanjos/Desafio11GoRestaurantMobile.git


  # Entrar na pasta do projeto

  $ cd Desafio11GoRestaurantMobile


  # Para instalar todas as dependências do projeto

  $ yarn


  # Para iniciar a aplicação execute

  $ yarn start

```

## 🚦 Importante:

Siga os passos a seguir para [Configurar Ambiente React Native](https://react-native.rocketseat.dev/)


## 📦 Como Executar o Projeto Back-end

```bash

  # Após instalar todas as dependências via yarn

  # Execute o comando a abaixo para iniciar a aplicação em http://localhost:3333/

  $ yarn json-server server.json -p 3333
  ```

## 🚦 Importante:

Caso venha a usar o dispositivo físico, verifique se o pc e o dispositivo estão na mesma rede e execute.

``` bash
$ yarn json-server --host IP_DA_SUA_MAQUINA server.json -p 3333

# Não esqueça de alterar a baseURL no arquivo em src/services/api.ts, para 'http://IP_DA_SUA_MAQUINA:3333'

```

## Licença:

MIT License

Desenvolvido por Eloilson Rocha
