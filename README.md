# E-Commerce-Back-End
## _Take control of your Store_

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

Have an organized database of your products.

- Organize your products by ID, categories, by product and tags.
- ✨Look how the database is related with all the other tags.

## Features

- You can search by product, tag, categorie and ID.
- Update any product searching it by ID or other tag.
- Add as many as you want products by any tag.
- Delete products searching them by his categorie, id and name (product).
- This is a command line app!

## Tech

This app was made with:

- [JavaScript](https://developer.mozilla.org/es/docs/Web/JavaScript)
- [Node JS](https://nodejs.org/en/)
- [Express](https://expressjs.com/)
- [MySQL](https://www.mysql.com/)

## Installation

You need to install previously the following dependencies to run it:
- Node JS
- Express JS
- MySQL
- Insomnia (to see the results).

IMPORTANT: Before running the app, edit the ".env" file with your USER (root) and PASSWORD (your password on MySQL) to continue correctly with the deployment.

After that, follow the next steps:
-Inside the main folder run the terminal and type: npm install (to install all dependencies).
-Then run MySQL with the next command: mysql -u root -p
-Type your password to run MySQL.
-Next, type SOURCE db/schema.sql; to create de DB (after that you can see the database typing SHOW DATABASES;)
-Without closing this terminal, open another one in the main folder to run the DB with the command "npm run seed"
-Use "node server.js" to run the server

## Screenshots


## License

MIT

**Educational Software**
