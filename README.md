E-Commerce Back End
===================

Description
-----------

This project is a back-end API for an e-commerce platform built using Express.js and Sequelize. The motivation behind building this project was to better understand the architecture and database relationships that power real-world e-commerce sites. It provides a way to manage products, categories, and tags efficiently through RESTful CRUD operations. The API allows users to create, update, and delete products and associated metadata, ensuring proper relations between products, categories, and tags.

-   **Motivation:** To dive deeper into building and managing complex data models with Sequelize and PostgreSQL.
-   **Why build this project?** To simulate how e-commerce sites manage their inventory and relationships between product categories, products, and tags.
-   **Problem solved:** It provides a foundation for developers to build out scalable e-commerce platforms with a back-end API capable of handling real-time data requests.
-   **What did I learn?** How to configure Sequelize with PostgreSQL, define models, set up associations, and create RESTful APIs.

Table of Contents
-----------------

-   [Installation](#installation)
-   [Usage](#usage)
-   [Credits](#credits)
-   [License](#license)
-   [Features](#features)
-   [How to Contribute](#how-to-contribute)

Installation
------------

To install and set up this project, follow these steps:

1.  Clone the repository:

    ```bash
    `git clone https://github.com/your-username/ecommerce-backend.git`
2.  Navigate to the project directory:
    ```bash
    `cd ecommerce-backend`
3.  Install the necessary dependencies:
    ```bash
    `npm install`
4.  Set up the PostgreSQL database:

    -   Make sure PostgreSQL is installed and running on your machine.
    -   Run the schema file located in the `db/schema.sql` directory to create your database.
    -   Create a `.env` file in the root of the project and add your PostgreSQL credentials:

        `DB_NAME='ecommerce_db'
        DB_USER='your_username'
        DB_PASSWORD='your_password'
        DB_HOST='localhost'
        DB_PORT=5432`

5.  Seed the database with initial data:
    ```bash
    `npm run seed`
6.  Start the application:
    ```bash
    `npm start`
Usage
-----

Once the server is running, you can interact with the API using tools like Insomnia or Postman.

Here are some example routes:

-   **GET All Categories:** `/api/categories`
-   **GET All Products:** `/api/products`
-   **GET All Tags:** `/api/tags`
-   **POST New Product:** `/api/products`
-   **PUT Update Category:** `/api/categories/:id`
-   **DELETE Product:** `/api/products/:id`

Back End Demo:


![alt text](./assets/Untitled%20Video%20August%2022,%202024%203_38%20PM.gif)

Credits
-------

-   **Developer:** [Sam Kachergius](https://github.com/ogchromebook)
-   **Frameworks:** Express.js, Sequelize
-   **Database:** PostgreSQL
-   **Third-party packages:**
    -   [dotenv](https://www.npmjs.com/package/dotenv)
    -   [pg](https://www.npmjs.com/package/pg)
-   **Starter Code Provided By EDx Bootcamp**

License
-------

**MIT**

Features
--------

-   View all categories, products, and tags
-   Add new products and categories
-   Update and delete existing products
-   Relational database with product, category, and tag associations

How to Contribute
-----------------

If you'd like to contribute to this project, please follow these steps:

1.  Fork the repository
2.  Create a new feature branch:

    ```bash
    `git checkout -b feature-branch`
    ```
3.  Make your changes and test them thoroughly.
4.  Submit a pull request and describe the changes made.

For contribution guidelines, check out the [Contributor Covenant](https://www.contributor-covenant.org/).