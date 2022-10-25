# E-commerce Back End Starter Code

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description
Internet retail, also known as e-commerce, is the largest sector of the electronics industry, having generated an estimated US$29 trillion in 2017 (Source: United Nations Conference on Trade and Development). E-commerce platforms like Shopify and WooCommerce provide a suite of services to businesses of all sizes. Due to the prevalence of these platforms, developers should understand the fundamental architecture of e-commerce sites.

This application contains the back end requirements for an e-commerce site: Using a working Express.js API and configuring it to use Sequelize to interact with a MySQL database.
Because this application is not to be deployed, a walkthrough video that demonstrates its functionality and all of the following acceptance criteria being met is provided. A link to the video and a high quality README of the project are also provided.

## Table of Contents
* [Tools](#tools)
* [Mock Up](#Mock-Up)
* [Instructions](#Instructions)
* [User Story](#User-Story)
* [Acceptance Criteria](#Acceptance-Criteria)
* [Delivarables](#Delivarables)
* [Walkthrough Video](Walkthrough-Video)
* [Technical Acceptance Criteria](#Technical-Acceptance-Criteria)
* [Repository Quality](#Repository-Quality)
* [Application Quality](#Application-Quality)
* [Questions](#Questions)
* [Submission](#Submission)

### Tools
1. JavaScript
2. [MySQL2](https://www.npmjs.com/package/mysql2)
3. [Node.js](https://nodejs.org/en/)
4. [Express.js](https://www.npmjs.com/package/express)
5. [Dotenv](https://www.npmjs.com/package/dotenv)
6. [Sequelize](https://www.npmjs.com/package/sequelize)

### Mock Up
![Team Generator HTML Webpage Screenshot](./assets/images/13-orm-homework-demo-01.gif)
![Team Generator HTML Webpage Screenshot](./assets/images/13-orm-homework-demo-02.gif)
![Team Generator HTML Webpage Screenshot](./assets/images/13-orm-homework-demo-03.gif)

## Instructions
1. Clone the main project, then open the cloned file.
2. Make sure you are in the main project folder using the 'cd' command.
3. Open command prompt and run: npm install
4. Create a `.env` in the root directory
5. Create the following three variables in the `.env` file:
- `DB_NAME=ecommerce_db`
- `DB_USER=`[MySQL username]
- `DB_PW=`[MySQL password]
6. Open: `MySQL` CLI.
7. Run: `source db/schema.sql` to create the database.
8. Run: `npm run seeds` to seed the databse.
9. Run: `npm start`

### User Story
* AS A manager at an internet retail company
* I WANT a back end for my e-commerce website that uses the latest technologies 
* SO THAT my company can compete with other e-commerce companies

### Acceptance Criteria:
* GIVEN a functional Express.js API
* WHEN I add my database name, MySQL username, and MySQL password to an environment variable file THEN I am able to connect to a database using Sequelize
* WHEN I enter schema and seed commands
* THEN a development database is created and is seeded with test data
* WHEN I enter the command to invoke the application
* THEN my server is started and the Sequelize models are synced to the MySQL database
* WHEN I open API GET routes in Insomnia for categories, products, or tags
* THEN the data for each of these routes is displayed in a formatted JSON
* WHEN I test API POST, PUT, and DELETE routes in Insomnia
* THEN I am able to successfully create, update, and delete data in my database

### Delivarables
* Your GitHub repository containing your application code.

### Walkthrough Video
* A walkthrough video that demonstrates the functionality of the e-commerce back end must be submitted, and a link to the video should be included in your README file.
* The walkthrough video must show all of the technical acceptance criteria being met.
* The walkthrough video must demonstrate how to create the schema from the MySQL shell.
* The walkthrough video must demonstrate how to seed the database from the command line.
* The walkthrough video must demonstrate how to start the application’s server.
* The walkthrough video must demonstrate GET routes for all categories, all products, and all tags being tested in Insomnia.
* The walkthrough video must demonstrate GET routes for a single category, a single product, and a single tag being tested in Insomnia.
* The walkthrough video must demonstrate POST, PUT, and DELETE routes for categories, products, and tags being tested in Insomnia.
* Link: https://drive.google.com/file/d/1VWfxq9ttIDSe8ZCBoNG5IqamubsN-bw_/view

### Technical Acceptance Criteria
* Satisfies all of the preceding acceptance criteria plus the following:
* Uses the MySQL2 (https://www.npmjs.com/package/mysql) and Sequelize
(https://www.npmjs.com/package/sequelize) packages to connect to a MySQL database.
* Uses the dotenv package (https://www.npmjs.com/package/dotenv) to use environment variables to store sensitive data, like a user’s MySQL username, password, and database name.
* Syncs Sequelize models to a MySQL database on the server start.
* Includes column definitions for all four models outlined in the Challenge instructions. 
* Includes model associations outlined in the Challenge instructions.

### Repository Quality
* Repository has a unique name.
* Repository follows best practices for file structure and naming conventions.
* Repository follows best practices for class/id naming conventions, indentation, quality comments, etc.
* Repository contains multiple descriptive commit messages.
* Repository contains a high-quality README with description and a link to a walkthrough video.

### Application Quality
* The application user experience is intuitive and easy to navigate.

## Questions
Please send your questions and / or comments to **bslockhart** at bslockhart@uncg.edu, or contact me on [GitHub](https://github.com/bslockhart/Brians-E-Commerce-Back-End).

### Submission
* Date Submitted: October 26, 2022
* You are required to submit BOTH of the following for review: 
1. A walkthrough video demonstrating the functionality of the application and all of the acceptance criteria being met: https://drive.google.com/file/d/1VWfxq9ttIDSe8ZCBoNG5IqamubsN-bw_/view
2. The URL of the GitHub repository, with a unique name and a README describing the project: https://github.com/bslockhart/Brians-E-Commerce-Back-End