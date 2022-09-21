# E-commerce Back End

## Description

  This is a back-end application featuring an Express.js API that uses Sequelize to interact with a MySQL database

  ## Installation

   * `npm install` to install required npm packages
      * Sequelize, dotenv
   *  Install Node.js to run the application
   *  Install MYSQL to view data

  ## Usage

   * The user must source the database first by logging into MYSQL and entering `SOURCE schema.sql`.
   * The user must enter the database name, MySQL username and password to the .env file.
   * The user will then enter `npm run seed` to seed the data.
   * Then the user will initialize the app by entering `node server.js` and Sequelize models will sync to the database.
   * Users will be able to enter GET routes for categories, products, and tags, as well as a GET route for returning a single item from each model.
   * Users will also be able to test POST, PUT and DELETE routes for categories, products and tags.
  
  
  ## Video Demo
  
  This video demonstrates GET routes for returning all categories, products, and tags. It also shows the GET routes for returning a single category,      product, and tag. The video then shows POST, PUT, and DELETE routes for categories, products, and tags.

   https://user-images.githubusercontent.com/105673031/191561503-9773e647-9f65-4bb5-9e26-5336a7444430.mov


  ## Features
  
   * Javascript
   * Node.js
   * npm
   * Express.js
   * MYSQL
   * Sequelize
   * dotenv
