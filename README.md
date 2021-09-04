# ecommerce-backend

## Description

To support functionality and efficient data storage and handling to an ecommerce website, a backend must be designed to utilize database calls retrieving, storing, updating and deleting various tasks related to products, pricing, inventory and more.  

In this exercise students will design a demonstration ecommerce backend using the following technologies:

* [Node.js](https://nodejs.dev/)
* [Express](http://expressjs.com/)
* [MySQL](https://www.mysql.com/)
* [Sequelize](https://sequelize.org/master/)

## Requirements

* Students must create a suitable MySQL database and tables for the following ecommerce-related data:

	* Categories
	* Products
	* Tags
	* Product Tags
* Database calls must be made using ORM solution Sequelize
* Students will configure schema, models and seeing actions (seeds are provided)
* Students will configure routes for performing CRUD methods on database tables

## Installation

## Usage

##### Create and seed database; verify tables are created

![01_ecommerce-backend_create-and-seed-db](./assets/readme_assets/01_ecommerce-backend_create-and-seed-db.gif)

##### Verify seed data in each table

![02_ecommerce-backend_display-table-data](./assets/readme_assets/02_ecommerce-backend_display-table-data.gif)

##### Start server

![03_ecommerce-backend_start-server](./assets/readme_assets/03_ecommerce-backend_start-server.gif)

##### GET methods:  categories, tags and products

![04_ecommerce-backend_GET-tags-categories-products](./assets/readme_assets/04_ecommerce-backend_GET-tags-categories-products.gif)

* **GET by ID:  products**
  ![05_ecommerce-backend_GET-id-products](./assets/readme_assets/05_ecommerce-backend_GET-id-products.gif)

* **GET by ID:  tags**
  ![06_ecommerce-backend_GET-id-tags](./assets/readme_assets/06_ecommerce-backend_GET-id-tags.gif)

* **GET by ID:  categories**
  ![07_ecommerce-backend_GET-id-categories](./assets/readme_assets/07_ecommerce-backend_GET-id-categories.gif)
  
##### POST methods

* **POST by ID:  products**
    ![