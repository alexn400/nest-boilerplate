<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo_text.svg" width="320" alt="Nest Logo" /></a>
</p>

## NestJS Boilerplate

[Nest](https://github.com/nestjs/nest) framework TypeScript starter repository.

## Features

⭐ Linting with prettier + eslint + lint-staged
⭐ Yarn
⭐ Swagger docs
⭐ TypeORM
⭐ Postgres DB with docker

## Installation

```bash
$ yarn install
$ cp .env.example .env
```

## Database (development)

```bash
# start the database
$ docker-compose up -d

# run migrations
$ npm run typeorm migration:run
```

## Running the app

```bash

# development
$ yarn dev

# production
$ yarn start
```

## Test

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```

## Support

Nest is an MIT-licensed open source project. It can grow thanks to the sponsors and support by the amazing backers. If you'd like to join them, please [read more here](https://docs.nestjs.com/support).

## Stay in touch

- Author - [Kamil Myśliwiec](https://kamilmysliwiec.com)
- Website - [https://nestjs.com](https://nestjs.com/)
- Twitter - [@nestframework](https://twitter.com/nestframework)

## License

Nest is [MIT licensed](LICENSE).

### :star2: Stargazers

[![Stargazers repo roster for @leosuncin/nest-auth-example](https://reporoster.com/stars/leosuncin/nest-auth-example)](https://github.com/leosuncin/nest-auth-example/stargazers)

### :fork_and_knife: Forkers

[![Forkers repo roster for @leosuncin/nest-auth-example](https://reporoster.com/forks/leosuncin/nest-auth-example)](https://github.com/leosuncin/nest-auth-example/network/members)
