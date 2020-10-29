<h1 align="center">
  <br>
  <a href="https://github.com/carloshilner/happy-app/"><img src="https://raw.githubusercontent.com/carloshilner/happy-app/master/web/src/images/logo.svg" alt="Happy-app " width="200"></a>
  <br>
  Happy-app 
  <br>
</h1>
<p>
  
  <a href="web/LICENSE" target="_blank">
    <img alt="Documentation" src="https://img.shields.io/badge/documentation-yes-brightgreen.svg" />
  </a>
  <a href="web/LICENSE" target="_blank">
    <img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-yellow.svg" />
  </a>
  
</p>

> Happy - Visit orphanages and change many children's day.

### 🏠 [Homepage](https://github.com/carloshilner/happy-app)

## Installing Frontend

```sh
yarn --cwd ./web install
```

## Frontend Usage

```sh
yarn --cwd ./web start
```

## Run tests in Frontend

```sh
yarn --cwd ./web test
```

## Installing Backend

```sh
yarn --cwd ./backend install
```
## Running Database migration

```sh
yarn --cwd ./backend migration:run
```

## Starting Server Backend

```sh
yarn --cwd ./backend dev
```
## Installing Mobile

```sh
yarn --cwd ./mobile install
```

## Starting Mobile

```sh
yarn --cwd ./mobile start

🗺 Mapbox

Siga as instruções para usar o mapbox no lugar do openstreetmap.

    Em "https://account.mapbox.com/", copie seu token.
    Na raiz do projeto web crie um arquivo chamado ".env"
    Dentro desse arquivo, digite "REACT_APP_MAPBOX_TOKEN =" e cole seu token logo depois.
    Entre no arquivo "OrphanagesMap.tsx", descomente o trecho de código correspondente as linhas 34, 35 e 36.
    No mesmo arquivo, comente a linha 32.

Se você fez tudo corretamente, estás usando a API do mapbox com seu Token na página do mapa. 
