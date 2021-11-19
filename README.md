# 13. Object-Relational Mapping (ORM) Challenge: E-commerce Back End

### TODO

* [x] Data Models
    * [x] Category
        * [x] id
            * [x] Integer
            * [x] Doesn't allow null values
            * [x] Set as primary key
            * [x] Uses auto increment
        * [x] category_name
            * [x] String
            * [x] Doesn't allow null values
    * [x] Product
        * [x] id
            * [x] Integer
            * [x] Doesn't allow null values
            * [x] Set as primary key
            * [x] Uses auto increment
        * [x] product_name
            * [x] String
            * [x] Doesn't allow null values
        * [x] price
            * [x] Decimal
            * [x] Doesn't allow null values
            * [x]Validates that the value is a decimal
        * [x] stock
            * [x] Integer
            * [x] Doesn't allow null values
            * [x] Set a default value of 10
            * [x] Validates that the value is numeric
        * [x] category_id
            * [x] Integer
            * [x] References the category model's id
    * [x] Tag
        * [x] id
            * [x] Integer
            * [x] Doesn't allow null values
            * [x] Set as primary key
            * [x] Uses auto increment
        * [x] tag_name
            * [x] String
    * [x] ProdcutTag
        * [x] id
            * [x] Integer
            * [x] Doesn't allow null values
            * [x] Set as primary key
            * [x] Uses auto increment
        * [x] product_id
            * [x] Integer
            * [x] References the product model's id
        * [x] tag_id
            * [x] Integer
            * [x] References the tag model's id

<!--
// Product belongs to Category, as a category can have multiple products but a product can only belong to one category.
// Category has many Product models.
// Product belongs to many Tag models. Using the ProductTag through model, allow products to have multiple tags and tags to have many products.
// Tag belongs to many Product models.
-->

* [x] Associations
    * [x] Product belongsTo Category
    * [x] Categories have many Products
    * [x] Products belongToMany Tags (through ProductTag)
    * [x] Tags belongToMany Products (through ProductTag)

* [] Routes
    * [] Category
    * [] Product
    * [] Tag
    * [] ProdcutTag



















![Code badge](https://img.shields.io/github/languages/top/warrenp11/ecommerce-backend) 
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

## Table of Contents
* [Description](#description)
* [Installation](#installation)
* [Usage](#usage)
* [Tests](#tests)
* [Credits](#credits)
* [Project Insight](#project-insight)
* [Questions](#questions)
* [License](#license)

## Description
This application was designed as a homework assignment for Rutgers Coding Boot Camp.

Our challenge was to build the back end for an e-commerce site, taking a working Express.js API and configure it to use Sequelize to interact with a MySQL database.

Starter code was provided for this application.

        USER STORY
        AS A manager at an internet retail company
        I WANT a back end for my e-commerce website that uses the latest technologies
        SO THAT my company can compete with other e-commerce companies

        ACCEPTANCE CRITERIA
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

## Credits
[Dotenv](https://www.npmjs.com/package/dotenv)

[Express](https://www.npmjs.com/package/express)

[Insomnia Core](https://insomnia.rest/)

[MySQL](https://www.npmjs.com/package/mysql2)

[Sequelize](https://www.npmjs.com/package/sequelize)


## Questions
If you have any questions about this project contact me directly at warrenp11@gmail.com. 
  
Visit this project's repository at https://www.github.com/warrenp11/ecommerce-backend

View more of my projects at https://www.github.com/warrenp11


## License
Licensed under the [MIT](./LICENSE.txt/) license.