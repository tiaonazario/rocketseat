# Passos para elaboração do projeto

- Iniciar o projeto `npm init -y`
- instalar o express `npm install express`
- Criar arquivo server dentro da pasta src, mudar o main para server no package.json
- configurar inportação do express colocando "type": "module" no package.json, em sequencia mudar a extensão do server.js para server.mjs

## Instalar o gerenciador de rotas hoppscotch

## Instalar TypeScript

`npm i typescript -D`

execultar

`npx tsc --init`

# Back-end

## Entidades

### Game

- id
- title
- bannerUrl

### Ad

- id
- gameId
- name
- yearsPlaying
- discord
- weekDays
- hoursStart
- hourEnd
- useVoiceChannel
- createdAt

## Casos de uso

- Listagem de games com contagem de anúncios
- Criação de novo anúncio
- Listagem de anúncios por game
- Buscar discord pelo ID do anúncio


## Prisma

### Instalar o Prisma

```powershell
npm i prisma -D
```

### Ver a documentação

```powershell
npx prisma init -h
```

```powershell
npx prisma init --datasource-provider SQLite
```

### Criar migrações

```powershell
npx prisma migrate dev
```

### Interface gráfica prisma

```powershell
npx prisma studio
```

### Prisma client

```powershell
npm i @prisma/client
```

### Cria os types para o prisma

> Cria no arquivo `.\node_modules\.prisma/client/index.d.ts`

```powershell
npx prisma generate
```

### Atualizar o scripts do package.json

```json
"dev": "tsnd --exit-child src/server.ts"
```

> Se não fizer isso o node não atualiza automaticamente

## Instalar Cors

> Biblioteca que proteje o back-end de um front-end que não queremos que acesse

```powershell
npm i cors
npm i @types/cors -D
```
