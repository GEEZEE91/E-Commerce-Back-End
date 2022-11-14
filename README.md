# E-Commerce-Back-End

Backend application for an E-Commerce Site, built with MySQL, Sequelize, and Express. The database includes tables for products, categories and tags with routes for creating, updating, and deleting within the database. All restful operations are tested with Insomnia.

## Installation
The user should clone the repository from GitHub. 

To connect to the database run and enter password. 

    mysql -u root -p 

Source the schema.sql.

    source db/schema.sql
  
Exit my sql

Run

    npm i
  
To seed the file run

    npm run seed
  
  
Finally to run the application

    npm start
