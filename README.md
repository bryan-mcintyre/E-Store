# E-Store

## Table of Contents
- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Future Development](#future-development)
- [Issues](#issues)
- [Credits](#credits)

## Description
This the back-end of an e-commerce website. This codebase encompasses Category, Product, Tag, and Product Tag models, as well as their associated api routes. Included in each route are methods for GET, POST, PUT, and DELETE.

## Installation
Download the code and update the .env file with your own credentials. To initialize the database: 'psql -U postgres' -> '\i db/schema.sql' -> '\q'. To seed database: 'npm run seed'. To initialize the server use either: 'node --watch server.js', 'npm run server', or 'node server.js'. This concludes the installation of the ecommerce backend.

## Usage
Once the backend is initialized, test that it is working via Insominia Core. To test the GET method, open a GET route to 'http://localhost:3001/api/categories' The GET method for products: '.../products' and tags: '.../tags'. To test the POST method open a post route using the same addresses and create a JSON body with 'category_name', 'product_name', or 'tag_name' to create a new category, product, or tag. To update the name of a category, product, or tag open a PUT route and follow the previous instructions. If you need to delete a category, product, or tag open a DELETE route to '.../{category, product, or tag}/:id and it will be deleted.

Video demonstration of GET, POST, PUT, and DELETE routes can be found here: 

## Future Development
Add front-end of application

## Issues
N/A

## Credits
Course curriculum including the solved module 13 mini-project.