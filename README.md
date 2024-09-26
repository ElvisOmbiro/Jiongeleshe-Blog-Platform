# Blog Platform

## Overview

This Blog Platform is built using Node.js and Express, with MongoDB as the database. It provides features for user authentication, allowing users to log in, create, edit, and delete posts. The platform utilizes JSON Web Tokens (JWT) for secure user sessions and offers a flexible and dynamic interface for managing blog content.

## Project Architecture

The project is structured into four main directories under the `server` directory:

- **config**: Contains configuration files such as `db.js` for database connection settings.
- **helpers**: Includes utility functions like `routeHelpers.js` to assist with routing and middleware logic.
- **models**: Defines the data models for the application, including `post.js` and `user.js`, which outline the structure of the data stored in MongoDB.
- **routes**: Manages the application routing, with `admin.js` handling admin-specific routes and `main.js` dealing with the public-facing routes.

Clone the repository

Install dependencies: Make sure you have Node.js and npm installed. Then run npm install

Connect to MongoDB: Ensure you have a MongoDB database set up. You can use MongoDB Atlas for a cloud-based solution.


