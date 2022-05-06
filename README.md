# **E-Commerce-Back End**
![Code % Badge](https://img.shields.io/github/languages/top/coderbennett/ecommerce-backend) [![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

## **Description**
This application is an example of the back end for an e-commerce site. Using Express.js, Sequelize and MySQL to manage a database of categories, products and product tags.

## **Table of Contents**
1. [Installation](#installation)
2. [Usage](#usage)
3. [Technologies](#technologies)
4. [Credits](#credits)
5. [License](#license)

## **Installation**
To install this app onto your own machine, you will need to start with an `npm install` while in the console/terminal while in the root directory.

Once you have completed your npm installation, you will want to source the schema to create the database yourself first.

To do this make sure to use the `source db/schema.sql` command while inside your MySQL monitor.

Once you have created the schema you will want to seed some starting data to the database (you could always create/post your own data to the database too). To insert the seed data already within the directory, simply use the `npm run seed` command.

You will also likely want to use [Insomnia](https://insomnia.rest/) to easily access the get, post, put and delete routes.

## **Usage**
The best way to use this app is with Insomnia and by using the [site on heroku](https://limitless-everglades-37581.herokuapp.com/api/categories/). 

However, you can always use the app manually with the files here on GitHub. If you are using the directory on your local machine this way, make sure to follow the [installation](#installation) guide above.

To start the app simply type `npm start` into the terminal/console while in the root directory. 

This will start the server at the port 3001. You will need to use Insomnia at this point forward. Please watch the walk-through video below to see everything you can do with this app.

[![Walkthrough video on Ecommerce Backend](https://img.youtube.com/vi/khyMNAN7Hz8/0.jpg)](https://www.youtube.com/watch?v=khyMNAN7Hz8)

There are api routes for categories, tags, and products. Each has a get, post, put and delete route. While using insomnia you should easily be able to access all categories, tags and products by visiting their root routes:
* http://localhost:3001/api/categories/ 
* http://localhost:3001/api/tags/ 
* http://localhost:3001/api/products/

*If you are trying to post a new product, category or tag you will also need to use the root route for that item.*

Beyond this, you can also view each particular category, tag or product by their ID, by typing in the ID after the root route.

You can also delete or update a category, tag or ID by accessing their ID right after the root route for that item.

## **Technologies**
The technologies used in this application are as follows:
* [Sequelize](https://sequelize.org/)
* [Node.js](https://nodejs.org/en/)
* [MySQL](https://www.mysql.com/)
* [Insomnia](https://insomnia.rest/)
* [Express.js](https://expressjs.com/)

## **Credits**
Many credits to Insomnia for making testing APIs much easier. This application would also not be possible without Node.js, Express.js and Sequelize. The application also uses MySQL to run the database. 

This application was built by [coderbennett](https://github.com/coderbennett).

## **License**
This application is under the Apache 2.0 license. Please view the [LICENSE](LICENSE.txt) document for more information.