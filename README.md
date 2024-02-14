# MarketplaceMastery
ORM E-Commerce Engine

## Overview
MarketplaceMastery is engineered as a robust back-end solution for e-commerce platforms, catering to the nuanced needs of the electronics industry. Leveraging the power of ORM with Sequelize, this application orchestrates an efficient and secure interaction between an Express.js API and a MySQL database.

[Walkthrough Video](https://drive.google.com/file/d/1HlFalIzb6l-crpbG-MyXuaICGD2egOF_/view)

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Database Schema](#database-schema)
- [Associations](#associations)
- [Environmental Variables](#environmental-variables)
- [Technical Stack](#technical-stack)
- [Contributions](#contributions)
- [License](#license)

## Features
- Sequelize Integration: Establish a seamless connection to MySQL databases.
- Environment Variable Configuration: Safeguard sensitive information using .env configurations.
- RESTful API Routes: Facilitate CRUD operations through clean and intuitive API endpoints.
- Data Modeling: Structure your e-commerce data with precision using Sequelize models.
- Insomnia Compatibility: Test API routes effortlessly with Insomnia for consistent data management.

## Installation
- Clone the repository to your local environment.
- Install the required npm packages by running npm install.
- Configure your MySQL database settings in an .env file.
- Initialize the database with schema and seed commands.
- Invoke the application using npm start.

## Usage
Utilize tools like Insomnia to interact with the API:

- GET: Retrieve data for categories, products, or tags.
- POST: Create new entries in your database.
- PUT: Update existing records.
- DELETE: Remove entries from your database.

## Database Schema
The schema is designed with four main models:

- Category: Primary entity for product classification.
- Product: Core entity representing items for sale.
- Tag: Descriptor entity for products.
- ProductTag: Associative entity bridging Products and Tags.

## Associations
- Category-Product: One-to-many relationship allowing for a variety of products within a single category.
- Product-Tag: Many-to-many relationship enabling products to carry multiple tags and vice versa.

## Environment Variables
Store your configuration in .env:

- DB_NAME: Name of your MySQL database.
- DB_USER: Your MySQL username.
- DB_PASSWORD: Your MySQL password.
Walkthrough Video

[Walkthrough Video](https://drive.google.com/file/d/1HlFalIzb6l-crpbG-MyXuaICGD2egOF_/view)

View the walkthrough video demonstrating the functionality and setup process of MarketplaceMastery.

## Technical Stack
- Node.js: JavaScript runtime for the backend.
- Express.js: Web application framework for Node.js.
- MySQL2: MySQL client for Node.js.
- Sequelize: Promise-based ORM for Node.js.
- dotenv: Module to load environment variables from .env.

## Contributions
Contributions are welcome. Please ensure that your code adheres to the project's coding standards and submit a pull request for review.

## License
MarketplaceMastery is released under the MIT License.


