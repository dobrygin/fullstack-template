# fullstack-template
My template for creating the awesome web apps.

## Stack
All the technologies used in this project.

### Frontend
##### Frameworks
- [React](https://reactjs.org/) — Awesome front-end framework.
- [Theme UI](https://theme-ui.com/home) — Design framework.
##### Bundle build tools
- [Webpack](https://webpack.js.org/)
##### Technologies
- [Typescript](https://www.typescriptlang.org/)
##### Testing and linter
- [Jest](https://jestjs.io/) — JavaScript Testing framework.
- [Eslint](https://github.com/typescript-eslint/typescript-eslint) — Linter.

### Backend
- [Express](https://expressjs.com/) — App's logic. API endpoint.
- [Redis](https://redis.io/) — Pub-sub system.

### Devops
- [Docker](https://docker.com) — Сontainerization.
- [Nginx](https://nginx.org/) — Powerful HTTP-server. Reverse proxy.


## Usage
### Run development build
Front-end and back-end starts with hot reloading and NODE_ENV=development
#### Just run development build
```shell script
docker-compose -f docker-compose.dev.yml up -d
```
#### Rebuild containers
```shell script
docker-compose -f docker-compose.dev.yml up -d --build
```
#### Force recreate containers
```shell script
docker-compose -f docker-compose.dev.yml up -d --force-recreate
```
#### Rebuild and force recreate containers
```shell script
docker-compose -f docker-compose.dev.yml up -d --build --force-recreate
```
