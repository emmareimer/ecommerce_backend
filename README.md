# ecommerce_backend
A command line program to organize products for an e commerce store

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Tests](#tests)
- [Questions](#questions)
- [Sources](#sources)

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

## Usage
Users can use an app, such as Insomnia, mySQL workbench, TablesPlus, etc. or mySQL queries in the command line to update the database with products, categoreis, and tags. 

Product belongs to Category, and Category has many Product models, as a category can have multiple products but a product can only belong to one category.

Product belongs to many Tag models, and Tag belongs to many Product models. Allow products to have multiple tags and tags to have many products by using the ProductTag through model.

The following video shows the functionality of the program:
[Link to Video](https://drive.google.com/file/d/1k17pnJk1FzgqdDTu4jTtshsE4RH3HkeG/view)

## Tests
For testing, make sure to run command `npm start seed` to seed the test data in to the database.

## Questions?

Contact Info:

Github profile: emmareimer

Email: emma@beinproximity.com

## Sources, Libraries, and Languages
Nodejs, Javascript, MySQL, Sequelize

