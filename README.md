# E-Commerce-Back-End

Backend application for an E-Commerce Site, built with MySQL, Sequelize, and Express. 

The database includes tables for products, categories and tags with routes for creating, updating, and deleting within the database. 

After Installation, we can manipulate the database tables using Insomnia to fetch all, fetch by id, create new, update and delete records within the database tables.




## Installation
The user should clone the repository from GitHub. 

     git clone https://github.com/GEEZEE91/E-Commerce-Back-End.git

To connect to the database run and enter password. 

    mysql -u root -p 

Source the schema.sql.

    source db/schema.sql
  
Exit my sql

Install dependencies

    npm i
  
To seed the file run

    npm run seed
 
After installations is completed, run the app with below in terminal

    npm start

  

 ## Usage


-   This application uses the <kbd>MySQL2</kbd> and <kbd>Sequelize</kbd> package that connects the <kbd>ExpressJS API</kbd> to a <kbd>MySQL</kbd> database.


-   This project creates a new database on the local MySQL server then injects data into it. Data can be manipulated with the use of Insomnia.


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
