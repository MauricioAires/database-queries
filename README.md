<h1 align="center">
    <img src="./github/assets/cover.png">
</h1>

### Sobre o projeto

Nesse repositório, você realizará consultas no banco de dados com o TypeORM de três maneiras:

- Usando o ORM
- Usando Query Builder
- Usando Raw Query

Isso irá te ajudar a entender e exercitar os diferentes tipos de consultas que podemos fazer.

### Tecnologias

- [TypeScript](https://www.typescriptlang.org/docs/)
- [PostgreSQL](https://www.postgresql.org/docs/)
- [Typeorm](https://typeorm.io/)

### Instalação

```sh
yarn
```

### Comandos

Container com o banco Postgres

```bash
$ docker run --name ignite-challenge-database-queries -e POSTGRES_DB=queries_challenge -e POSTGRES_PASSWORD=docker -p 5432:5432 -d postgres
```

Criar uma entity utilizando a CLI

```bash
$ npx typeorm entity:create Genres
```

### Contribuição

Contribuições são bem-vindas! Para contribuir, basta abrir uma issue ou pull request neste repositório.

### Autor

Feito por Mauricio Aires 👋🏽
