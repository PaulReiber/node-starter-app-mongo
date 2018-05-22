## node-starter-app-mysql

Reiber Labs Node.js webapp template

Derived from https://github.com/varunon9/node-starter-app-mongo - rework in progress

Based on following libraries and frameworks:
1. Express.js
2. Ejs template engine
3. mongoose
4. jQuery
5. Semantic UI
6. JsonWebToken for authentication

### Folder Structure

1. **bin**: It contains the main file 'www' which starts node server
2. **config**: All the configurable parameters and credentials
3. **data**: json data
4. **logs**: logs dumps here
5. **middlewares**: All the middlewares defined here
6. **models**: Sequelize models (database schema)
7. **modules**: Independent modules used throughout the app are defined here
8. **public**: All the static resources (js, css, images)
9. **routes**: All the routes
10. **services**: These act as middlemen between routes and database. All the database operations are made here.
11. **views**: Contains HTML and .ejs files used for rendering to frontend

### How to install

1. `git clone https://github.com/PaulReiber/node-starter-app-mongo.git`
2. `cd node-starter-app-mongo`
3. `npm install`
4. `cd public`
5. `bower install`
6. create database 'nodeStarterAppMongo' in mongo... `create database nodeStarterAppMongo`
7. come back to project directory `cd ..`
8. start app `nodemon bin/www` or `node bin/www`
9. visit localhost:4000 in browser
