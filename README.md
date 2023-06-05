# E-commerce

This is the backend application for an e-commerce website. It provides API endpoints to manage categories, products, and tags stored in a database. The application is built with Node.js, Express.js, and Sequelize.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Demo](#Demo)

## Installation

1. Clone the repository to your local machine.
```
git clone https://github.com/Hiroro1989/E-commerce.git
```
2. Navigate to the project directory.
```
cd <saved-directory>
```

3. Install the dependencies.
```
npm install
```

4. Set up the database.

- Create a .env file
- Create a MySQL database using the provided SQL schema file (schema.sql).
- update the database connection details in the index.js file in the seeds.

## API Endpoints

### Categories

- **GET /api/categories**: Get all categories with associated products.
- **GET /api/categories/:id**: Get a single category by ID with associated products.
- **POST /api/categories**: Create a new category.
- **PUT /api/categories/:id**: Update a category by ID.
- **DELETE /api/categories/:id**: Delete a category by ID.

### Products

- **GET /api/products**: Get all products with associated category and tag data.
- **GET /api/products/:id**: Get a single product by ID with associated category and tag data.
- **POST /api/products**: Create a new product.
- **PUT /api/products/:id**: Update a product by ID.
- **DELETE /api/products/:id**: Delete a product by ID.

### Tags

- **GET /api/tags**: Get all tags with associated product data.
- **GET /api/tags/:id**: Get a single tag by ID with associated product data.
- **POST /api/tags**: Create a new tag.
- **PUT /api/tags/:id**: Update a tag by ID.
- **DELETE /api/tags/:id**: Delete a tag by ID.

## Demo

[Demo Video](https://drive.google.com/file/d/1GX-LYl4wIX9yAw-ySlN5Byw6MP1KLUfx/view)

[screenShot](./lib/1.png)
[screenShot](./lib/2.png)
[screenShot](./lib/3.png)
[screenShot](./lib/4.png)




