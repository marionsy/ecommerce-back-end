# E-commerce Back End

## Description

  This is a back-end application featuring an Express.js API that uses Sequelize to interact with a MySQL database

  ## Installation

   * `npm install` to install required npm packages
      * Sequelize, dotenv
   *  Install Node.js to run the application
   *  Install MYSQL to view and seed data

  ## Usage

   * The user must source the database first by logging into MYSQL and entering `SOURCE schema.sql`.
   * The user must enter the database name, MySQL username and password to the .env file.
   * The user will then enter `npm run seed` to seed the data.
   * Then the user will initialize the app by entering `node server.js` and Sequelize models will sync to the database.
   * Users will be able to enter GET routes for categories, products, and tags, as well as a GET route for returning a single item from each model.
   * Users will also be able to test POST, PUT and DELETE routes for categories, products and tags.
  
  
  ## Video Demo

  

  ## Features
  
   * Javascript
   * Node.js
   * npm
   * Express.js
   * MYSQL
   * Sequelize
   * dotenv
