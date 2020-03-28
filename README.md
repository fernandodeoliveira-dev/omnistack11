# ffernandodeoliveira-gmail.com
omnistack11

#################### CREATE NODE BACKEND APP (http://localhost:3333/) \n
$ npm init -y
#################### START
$ node index.js
#################### CREATE REACT APP FRONTEND (http://localhost:3000/)
$ yarn global remove create-react-app
#################### Params
-> Query Params: parâmetros nomeados enviados na rota após o "?" (filtros, paginação - request.query)
-> Route Params: parâmetros utilizados para identificar recursos (request.params)
-> Request Body (request.body)
####################
$ npm install nodemon
$ npm start
################## KNEX JS
$ npm install knex 
$ npm install sqlite3
$ npx knex init
$ npx knex migrate:make create_ongs
$ npx knex migrate:latest
$ npx knex migrate:rollback
$ npx knex migrate:make create_incidents
$ kill -9 $(lsof -t -i:3333)
$ npm install cors
