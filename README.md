# Module 13 | ORM | E-Commerce Back End

## Finished Product

### [🔗Project Link](https://github.com/TylerFruik/E-Commerce-Back-End) 
DESCRIPTION
This program handles the database for E-Commerse allowing the user to make Get, Put, Post, and Delete requests.

This project was developed using the following skills: 
JS, NodeJS, ORM, SQL, Sequelize, Insomnia, REST APIs

All code is neatly commented for clarity's sake.

All code refactored manually by Tyler Fruik.

### Use Instructions:
1) Clone/download the repository
2) Create a ".env" file in the directory and fill in the following information:
```
DB_NAME='ecommerce_db'
DB_USER=''
DB_PW=''
```
! Be sure to put your mysql information in the USER and PW fields !
3) Run "mysql -u root -p"
4) Run source db/schema.sql
5) Quit out of mysql
6) Run "node server.js"
7) Make REST API calls using Insomnia as shown in the video below



### The following is a video of the final product:
https://youtu.be/SGj2krrZs7A

## Assignment Information

### User Story
```
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

### Acceptance Criteria
```
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete data in my database
```
