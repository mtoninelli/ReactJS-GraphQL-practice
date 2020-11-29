## React, TypeScript, GraphQL

```
https://www.youtube.com/watch?v=I6ypD7qv3Z8
```

init project `npm init -y`
add ts `yarn add -D @types/node typescript`
add ts `yarn add -D ts-node`
listen to any change in the file and re running it `yarn add -D nodemon`
TERMINAL 1: `yarn watch` recompile for every change in TS file
TERMINAL 2: `yarn dev` recompile for every change in JS dist folder

install mikro db connector
`yarn add @mikro-orm/cli @mikro-orm/core @mikro-orm/migrations @mikro-orm/postgresql pg`
`yarn add reflect-metadata`
... `npx mikro-orm migration:create`

install: express server, apollo for connecting express qith graphql easily, graphql and type-graphql for schema
`yarn add express apollo-server-express graphql type-graphql`

type for express as dependency `yarn add -D @types/express`
