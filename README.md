## :rocket: GoStack 11 Rocketseat

Desafio da criação de uma aplicação mobile utilizando os conceitos do React Native aprendidos. Este projeto também conta com testes automatizados para cobrir os requisitos funcionais implementados.

## Aplicação mobile construído utilizando:

- [ReactNative](https://reactnative.dev/)

- [Axios](https://www.npmjs.com/package/axios)

- [Jest](https://jestjs.io/)

- [React Testing Library](https://testing-library.com/docs/react-testing-library/intro)

- [Axios Mock Adapter](https://www.npmjs.com/package/axios-mock-adapter)

## Funcionalidades

A aplicação mobile deve utilizar o backend construído previamente [github repositório](https://github.com/brvictorsa/desafio-conceitos-nodejs) e os requisitos são descritos abaixo:

* **Listar os repositórios da sua API**: Deve ser capaz de criar uma lista de todos os repositórios que estão cadastrados na sua API com os campos title, techs e número de curtidas seguindo o padrão *${repository.likes} curtidas*, apenas alterando o número para ser dinâmico.

* **Curtir um repositório listado da API**: Deve ser capaz de curtir um item na sua API através de um botão com o texto *Curtir* e deve atualizar o número de likes na listagem no mobile.

## Pré-requisito 

> O projeto [backend](https://github.com/brvictorsa/desafio-conceitos-nodejs) deve estar rodando previamente seguindo os passos descritos no arquivo README.md.

## Instalar e executar o projeto: 

O projeto mobile foi executado no emulador do Android Studio. Caso, queira executar em outro emulador ou no dispositivo físico, deve ser reconfigurada a *baseURL* no arquivo *src/services/api.js*. 

*Obs: se executado em outro ambiente os passos abaixo podem divergir conforme a plataforma utilizada*

1. Clonar o projeto para seu local de trabalho (via HTTPS).

2. Ter o React Native instalado.

```
yarn global add react-native-cli
```

2. Executar o comando *yarn* no terminal para baixar as dependências do projeto.
```js
yarn //or npm install
```

3. Executar o emulador do Android Studio. [Mais detalhes](https://react-native.rocketseat.dev/android/linux). 

4. Executar o Metro bundler para gerar os arquivos.
```js
yarn start //or npm react-native start
```

4. Executar o projeto no emulador do Android.
```js
yarn android //or react-native run-android
```

3. Executar os testes do backend utilizando o *jest* e o *react testing library*.
```js
yarn test  //or npm run test
```

## :memo: Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE.md) para mais detalhes.

---

Victor Santos - vSA 2020