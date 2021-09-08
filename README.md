<div align="center">
  <br />
  <img src=".github/sequelize.png" width="200" alt="sequelize" />
  <br />
<p>
    <img src="https://img.shields.io/badge/made%20by-Carlos%20DanielS3-2D325E?labelColor=F0DB4F&style=for-the-badge&logo=visual-studio-code&logoColor=2D325E" alt="Made by Carlos Daniel">
    <img alt="Top Language" src="https://img.shields.io/github/languages/top/CarlosDanielS3/ORM-with-Sequelize?color=2D325E&labelColor=F0DB4F&style=for-the-badge&logo=javascript&logoColor=2D325E">
    <a href="https://github.com/CarlosDanielS3/Typescript/commits/main">
      <img alt="Last Commits" src="https://img.shields.io/github/last-commit/CarlosDanielS3/Typescript?color=2D325E&labelColor=F0DB4F&style=for-the-badge&logo=github&logoColor=2D325E">
    </a>
<a href="https://github.com/CarlosDanielS3/Typescript/issues"><img alt="Top Language" src="https://img.shields.io/github/issues-raw/CarlosDanielS3/Typescript?color=2D325E&labelColor=F0DB4F&style=for-the-badge&logo=github&logoColor=2D325E"></a>
  </p>
</div>

## 🗂 Table of Contents
- [🗂 Table of Contents](#-table-of-contents)
- [📑 About](#-about)
- [💻 Technologies](#-technologies)
- [✨ Installation](#-installation)
- [🔥 Running](#-running)
  
## 📑 About

## This is a Javascript project created in order to learn the main features and advantages of ORM with Sequelize. Creating this application i could learn about:
## Branch V1
* Create a new project from scratch with Sequelize;
* Make restrictions on the project;
* Up a basic local server with Express and Nodemon;
* Install MySQL and how to access via terminal.
* Create a new database and connect it to the application.

* Create terminal migration files and templates
* What are migrations with ORMs and what they are
* Perform migrations to create database tables
* Popular tables via seed files

* How the MVC model works
* What is a control layer and what it is for
* Creating a controller
* How to Use Sequelize Methods to Query the Database
* Separating responsibility from routes to have an organized application
* How to create a route to the People template
* Call a People controller method via the route with the HTTP GET verb

* Use other Sequel methods for CRUD operations
* Sending data via HTTP request parameters
* Send data via HTTP request body
* Create routes for each operation
* Associate routes to each method of the People controller

* Interpret the database diagram
* Identify the types of relationship requested in the project
* Join Sequelize Method Tables
* Reference associated tables
* Migrate associated tables
* Associated Popular Tables

* Add new drivers;
* Work with more than one model on the same controller;
* Send data via parameters and request bodies;
* Use this data to find information in the bank;
* Generate JSON-type data structures with useful user information.

## Branch V2
* Update Sequelize Version
* Add "Paranoid" option to make the deletion smooth
* Create migrations to add columns to tables
* Create deletedAt column to use soft delete feature
* Restore deleted records via soft delete using .restore()

* Set a default template scope (defaultScope)
* Define other additional scopes as needed by the project
* Using an additional scope with the .findAll() method
* Validate input data using Sequelize's own validators
* Refine and customize field validations using functions and pure JS

* What are membership scopes
* How to define a new membership scope
* Use own methods/mixins on associated tables
* Add a search filter via query parameters
* Use Operators to Do Data Operations
* Return results filtered through operators
* Filter and enumerate records with "finders" methods
* Sort the results with the "order" option
* Group records with "group"
* Passing SQL commands into Sequelize with Sequelize.literal()

* Create methods to update more than one table
* Add transactions to bank operations via Sequelize
* Interpret versioning warnings and make corrections
* Create a service layer
* Transfer the controller's database interface to the service
* Update code in controller to access services
* Create specific services that inherit methods from the main class
* Organize services by creating an entry point (index.js)
* Create specific methods for a service/template
* Passing parameters from controllers to services
* Connect services to each other
* Refactor the application to separate controllers and services



## ✨ Installation
Open a terminal and run the following commands:

```PowerShell
# To copy this repository
git clone https://github.com/CarlosDanielS3/ORM-with-Sequelize.git

# To move to project directory
cd ORM-with-Sequelize

# To install the dependencies
yarn
```
## 🔥 Running
You can run the application in development mode with the command:

```Powershell
#Run the Server
yarn start
```
