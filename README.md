## migrate
``` bash
 npx sequelize-cli migration:create --name name_of_your_migration            
 npx sequelize-cli db:migrate            
```
 ## seed 
 ``` bash           
 npx sequelize-cli seed:generate --name user            
 npx sequelize-cli db:seed --seed 20221007043120-users.js            
 npx sequelize-cli db:seed:all
 ```
## Installation

```bash
$ npm install
```

## Running the app

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
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
