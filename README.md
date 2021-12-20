# RVT E-Commerce Backend
> This application organizes products by category with added product tags!

## Table of contents
- [RVT E-Commerce Backend](#rvt-e-commerce-backend)
  - [Table of contents](#table-of-contents)
  - [General info](#general-info)
  - [User Story](#user-story)
  - [Screenshot](#screenshot)
  - [Video Walkthrough](#video-walkthrough)
  - [Setup](#setup)
  - [Code](#code)
  - [Licenses](#licenses)
  - [Developer(s)](#developers)

## General info
The application provides the back-end database functionality for an e-commerce website. It allows the user to create, read, update, or delete products, categories, and tags. This program would best be used with a front-end for an ecommerce website. This is using Object Relational Mapping (ORM).

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

## Screenshot
![E-Commerce Backend Screenshot](./images/rvt_employee_tracker_main.png)

## Video Walkthrough 
[Raman TV -- Ecommerce Walkthrough](https://www.youtube.com/watch?v=bb4UYMW24zc)

## Setup
* Clone GitHub repository (https://github.com/ramantv/rvt_ecommerce_backend)
* run these commands in order:
1. npm i
2. Create an .env file to add your mysql database, username, and password. 
3. Run 'npm start' to enter the application.
    * User will need to use Insomnia Core or POstman to access the routes

## Code
* JavaScript
* Node.js
* mySQL
* Express.js
* sequelize - database access
* dotenv - externalize the database connection environment variables

## Licenses
![MIT](https://img.shields.io/static/v1?label=License&message=MIT&color=BLUE) 
![ISC](https://img.shields.io/static/v1?label=License&message=ISC&color=BLUE) 

## Developer(s)
* [Raman TV.](https://github.com/ramantv)
 
