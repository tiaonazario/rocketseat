# Anotações

## Processos de criação do projeto

````powershell
  npm create vite@latest
````

Logo após criar o nome do projeto e escolher o tipo de template

## Instalando pacotes

````powershell
  npm i tailwindcss postcss autoprefixer -D
````

### Para o vite se integrar com o tailwindcss

````powershell
  npx tailwindcss init -p
````

### Links

- [graphcms](https://graphcms.com)

### Intalar o Apolo para fazer requisições e o graphql

````powershell
  npm i @apollo/client graphql
````

### Intalar o date-fns para trabalhar com datas

````powershell
  npm i date-fns
````

### Intalar vime, biblioteca para vídeo

````powershell
  npm i @vime/core @vime/react --force
````

Esse --force é para forçar a intalação, porque essa biblioteca não suporta a versão do react 18, isso até então.

### Trabalhando com rotas

````node
npm i react-router-dom
````

### Trabalanho com classes

````node
npm i classnames
````

### trabalhando com GraphQL

[GraphQL Code generator](graphql-code-generator.com)

````node
npm i @graphql-codegen/typescript @graphql-codegen/typescript-operations @graphql-codegen/typescript-react-apollo -D
````

````node
npm i @graphql-codegen/cli -D
````
