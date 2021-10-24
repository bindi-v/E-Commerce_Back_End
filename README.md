# E-Commerce_Back_End

## Task

Internet retail, also known as **e-commerce**, is the largest sector of the electronics industry, generating an estimated $29 trillion in 2019. E-commerce platforms like Shopify and WooCommerce provide a suite of services to businesses of all sizes. Due to their prevalence, understanding the fundamental architecture of these platforms will benefit us as a full-stack web developer.

Our task is to build the back end for an e-commerce site by modifying starter code. We configure a working Express.js API to use Sequelize to interact with a MySQL database.

## User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```
## Description

 ![License](https://img.shields.io/badge/License-MIT-yellow)

 Object-Relational Mapping (ORM)

```md
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
```

## Mock-Up

The following animation shows the application's GET routes to return all categories, all products, and all tags being tested in Insomnia Core:

![In Insomnia Core, the user tests “GET tags,” “GET Categories,” and “GET All Products.”.](./Assets/orm-demo-01.gif)

The following animation shows the application's GET routes to return a single category, a single product, and a single tag being tested in Insomnia Core:

![In Insomnia Core, the user tests “GET tag by id,” “GET Category by ID,” and “GET One Product.”](./Assets/orm-demo-02.gif)

The following animation shows the application's POST, PUT, and DELETE routes for categories being tested in Insomnia Core:

![In Insomnia Core, the user tests “DELETE Category by ID,” “CREATE Category,” and “UPDATE Category.”](./Assets/orm-demo-03.gif)


## Table Of Contents

- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Contribution](#contribution)
- [Contact](#contact)
    
## Installation 

The following necessary dependencies must be installed to run the application.
  Node.js, MYSQL, Express.js API, Sequelize, Insomnia Core

## Usage

 You can Invoked this application with node server.js command in terminal

## License

This project is licensed under
 MIT
For more about the license, check this link

[License](https://opensource.org/licenses/MIT)

## Contribution

We have given a starter code from Boot Camp

## Contact

* GitHub : [bindi-v](https://github.com/bindi-v)
* Email : bindi.vaghela@gmail.com
    
## Questions

If you have any questions, please reach out to my Github.

### Walk through Video:

* [A walk through video](https://watch.screencastify.com/v/ZttwRICZt7Uf7WB3RSMP)

* [If above link not work, try this link](https://drive.google.com/file/d/1Kdrdl2i9kIXo_pGV8VJ74DX56BBxA3sU/view)


### Repository

* [The URL of the GitHub repository](https://github.com/bindi-v/E-Commerce_Back_End)