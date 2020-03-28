omnistack11 <br />

## CREATE NODE BACKEND APP (http://localhost:3333/) <br />
$ npm init -y <br />
## START <br />
$ node index.js <br />
## CREATE REACT APP FRONTEND (http://localhost:3000/) <br />
$ yarn global remove create-react-app <br />
## Params <br />
-> Query Params: parâmetros nomeados enviados na rota após o "?" (filtros, paginação - request.query) <br />
-> Route Params: parâmetros utilizados para identificar recursos (request.params) <br />
-> Request Body (request.body) <br />
## Node <br />
$ npm install nodemon <br />
$ npm start <br />
## KNEX JS <br />
$ npm install knex <br />
$ npm install sqlite3 <br />
$ npx knex init <br />
$ npx knex migrate:make create_ongs <br />
$ npx knex migrate:latest <br />
$ npx knex migrate:rollback <br />
$ npx knex migrate:make create_incidents <br />
$ kill -9 $(lsof -t -i:3333) <br />
$ npm install cors <br />
