# 13. Object-Relational Mapping (ORM) Challenge: E-commerce Back End

![Code badge](https://img.shields.io/github/languages/top/warrenp11/ecommerce-backend) 
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

## Table of Contents
* [Description](#description)
* [Installation](#installation)
* [Usage](#usage)
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

## Installation
1. Copy one of the clone links from the GitHub [repository](https://www.github.com/warrenp11/ecommerce-backend)
    * HTTPS `https://github.com/warrenp11/ecommerce-backend.git`
    * SSH  `git@github.com:warrenp11/ecommerce-backend.git`

2. In a new Bash or Terminal Window, navigate to the directory where the repository will be added

3. Clone the repository with the following command:

           git clone <insert clone link here>

4. Open repository in preferred code editor

5. In the terminal, navigate to the root folder, and install the dependencies with the command:

           npm install

## Usage
When you're ready to run the application, from the root directory of the application enter the following commands into your command line:

           node seeds/index.js

           node server.js

[Click Here](https://watch.screencastify.com/) to see a video demonstration of the application in use

## Credits
[Dotenv](https://www.npmjs.com/package/dotenv)

[Express](https://www.npmjs.com/package/express)

[Insomnia Core](https://insomnia.rest/)

[MySQL](https://www.npmjs.com/package/mysql2)

[Sequelize](https://www.npmjs.com/package/sequelize)

## Project Insights
Thruthfully, imposter syndrome has been slowly creeping its way into my mind. I don't mean to come off as being too negative but it's the honest truth. There are days, some worse than others, where I wonder if I can ever be career ready and if I've chosen the right career change.

As we progress further into the course work and closer to graduation the more I need to remind myself how far I've come. 

This assignment came pretty natural to me compared to a few of the previous projects and weekly modules for class. I ran into a small bug when programming the tag-routes.js file that initially worried me, however, after a few minutes of debugging I was able to fix it.

## Questions
If you have any questions about this project contact me directly at warrenp11@gmail.com. 
  
Visit this project's repository at https://www.github.com/warrenp11/ecommerce-backend

View more of my projects at https://www.github.com/warrenp11

## License
Licensed under the [MIT](./LICENSE.txt/) license.