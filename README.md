# Workflow Front-End

- Bootstrap v4.0.0
- Gulp

## Requisitos:
- Node.js https://nodejs.org
- Gulp 

## Gulp
- Para instalar o gulp, abra o terminal e digite o comando abaixo:

```
npm install gulp -g

```

## Estrutura de Pastas

```
nome-projeto/
  README.md
  node_modules/
  package.json
  .gitignore
  app/
    index.html
    css/
    scss/
    fonts/
    images/
    js/
  dist/
    css/
    fonts/
    images/
    js/
    index.html 

```

O projeto deve ser desenvolvido na pasta <b>app</b> sendo a pasta <b>dist</b> composta pelos arquivos gerados pelo Gulp estes serão enviados para produção(publicação).

## Instalação
Apos clonar o projeto acesse a pasta do projeto pelo terminal e digite o comando abaixo para instalar as dependencias.

```
npm install 

```

## Executando o projeto
Para que o gulp fique escutando todas alterações do projeto, acesse a pasta do projeto no terminal e digite o comando abaixo:

```
gulp watch

```











