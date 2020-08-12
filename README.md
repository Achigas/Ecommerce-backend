# E-Commerce Backend
> This application organizes products by category with added product tags!

## Table of contents
* [General info](#general-info)
* [User Story](#user_story)
* [Video Walkthrough](#video_walkthrough)
* [Licenses](#licenses)
* [Code](#code)
* [Setup](#setup)
* [Inspiration](#inspiration)
* [Contact](#contact)

## General info
The user can use the back-end to create, read, update, or delete products, categories, and tags. This program would best be used with a front-end for an ecommerce website. This is using ORM.

## User Story
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

## Video Walkthrough 
[Alex Chigas -- Ecommerce Walkthrough]()

## Setup
* Clone GitHub repository 
* run npm install
* run npm i sequelize
* run npm i express
* run npm i dotenv
    * Create an .env file to add your mysql database, username, and password. 

* Run 'npm start' to enter the application.
    * User will need Insomnia Core to access the routes

## Code
* JavaScript
* Node.js
* mySQL
* Express.js

* sequelize - database access
* dotenv - helps to maintain user privacy

## Licenses
* MIT license
* ISC

## Inspiration
UCLA week 13 Challenge. 

## Contact
Application created by Alex Chigas with starter code from UCLA extension. 