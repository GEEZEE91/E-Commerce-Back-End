# E-Commerce-Back-End

Backend application for an E-Commerce Site, built with MySQL, Sequelize, and Express. The database includes tables for products, categories and tags with routes for creating, updating, and deleting within the database. All restful operations are tested with Insomnia.

## Installation
The user should clone the repository from GitHub. 

To connect to the database run and enter password. 

    mysql -u root -p 

Source the schema.sql.

    source db/schema.sql
  
Exit my sql

Install dependencies

    npm i
  
To seed the file run

    npm run seed
  
  

 ## Usage

After installations is completed, run the app with below in terminal

       npm start


## Resources
-   [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
-   [NodeJS](https://nodejs.org/)
-   Node Packages:
    -   [MySQL2](https://www.npmjs.com/package/mysql2)
    -   [Sequelize](https://www.npmjs.com/package/sequelize)
    -   [dotenv](https://www.npmjs.com/package/dotenv)
    -   [express](https://www.npmjs.com/package/express)

## License 
This project is license under MIT
  ![Github license](http://img.shields.io/badge/license-MIT-blue.svg)
