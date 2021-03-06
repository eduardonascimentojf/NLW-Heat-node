<h1 align='center'>NLW Heat - Node.js</h1>

## Tecnologias

- [TypeScript](https://www.typescriptlang.org/)
- [Express](https://expressjs.com/pt-br/)
- [Prisma](https://www.prisma.io/)
- [MySql](https://mysql.com)
- [JSON Web Token](https://jwt.io/)
- [Socket.IO](https://socket.io/)

## Instalação e Inicialização

> Faça uma copia do arquivo `.env.example` para `.env` e o preencha;

- Instale as dependências com

```sh
yarn install
```

- Executa as migrations com

```sh
yarn prisma migrate dev
```

- Inicie o servidor com

```sh
yarn dev
```

## Rotas

`http://localhost:4000`

- GET
  - /github
  - /signin/callback
  - /messages/last3
  - /profile
- POST

  - /authenticate
  - /messages

 </br>

Abrir no navegador: [localhost:4000](http://localhost:4000):
