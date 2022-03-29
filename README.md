# E-Commerce

[Link to video](https://watch.screencastify.com/v/eQM7Agh6eIP47A4M9TAm)

## Installation

- Clone the repositroy
- Install dependencies with the command "npm i sequelize, express, dotenv, and mysql2"
- Add login credentials into the .env file, with the database name of "ecommerce_db"

## Usage
- Log into your MySQL command line using the command "mysql -u "your username" -p", enter your password when prompted, then run the command "source db/schema.sql".
- Navigate to the root directory and type "npm run seed", this will seed all of your tables you just created.
- Now start the server with "npm start" in the console.

## User Story
- As a manager at an internet retail company,
 I want a back end for my e-commerce website that uses the latest technologies,
 so that my company can compete with other e-commerce companies.

## Acceptance criteria
- Gives a functional Express.js API
- When I add my database name, MySQL username, and MySQL password to an environment variable file, then I am able to connect to a database using Sequelize.
- When I enter schema and seed commands, then a development database is created and is seeded with test data.
- When I enter the command to invoke the application, then my server is started and the Sequelize models are synced to the MySQL database.
- When I open API GET routes in Insomnia for categories, products, or tags, then the data for each of these routes is displayed in a formatted JSON.
- When I test API POST, PUT, and DELETE routes in Insomnia, then I am able to successfully create, update, and delete data in my database.
