# Star Wars API

Star-Wars-API é uma API RESTfull o qual disponibiliza dados dos filmes do Star Wars

<img src='./img/stormtrooper.jpg' height="200">

> API do trabalho consome o servico <https://swapi.co/>

## Conteúdo

- Instalação
- Modo de uso

## Instalação

### Requisitos

- [NodeJS](https://nodejs.org/pt-br/)
- [Yarn](https://yarnpkg.com/pt-BR/)

### Primeiros passos - Clone

Clone o repositório em sua máquina local usando `https://github.com/CaioSilvaSilva/star-wars-api-k8s.git`

### Configuração

Dentro da pasta raiz do projeto execute o seguinte comando para baixar as dependencias:

```
yarn
```

## Modo de uso

Após isso digite o seguinte comando:

```
yarn start
```

Após isso, o projeto estará rodando no endereço [http://localhost:9000](http://localhost:9000).

- Para listar as informações de todos os filmes, acesse: [http://localhost:9000/films](http://localhost:9000/films).
- Para listar as informações de um filme específico, acesse informando o id do filme: [http://localhost:9000/films/1](http://localhost:9000/films/1)