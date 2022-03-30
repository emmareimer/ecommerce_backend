# ecommerce_backend
A command line program to organize products for an e commerce store

## Description
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies

## Acceptance Criteria
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database

## Installation
1. Clone repo
2. Command `npm i`
3. Command `npm i sequelize`
4. Command `npm i mysql2`
5. Add env file with 
        DB_USER=''
        DB_PW=''
        DB_NAME='ecommerce_db'
6. log in to mySQL using command `mysql -u root -p`
7. Enter password
8. Command `SOURCE db/schema.sql`
9. Command `USE db ecommerce_db`

