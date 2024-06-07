# TodoList-Strapi

## Description

- it is a backend application which provide web service using strapi, it has a CRUD operations for todos and specify relations between todos and users

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [API Documentation](#api-documentation)
- [License](#license)

## Installation

1. Clone the repository: git clone https://github.com/HodaRoushdy/todoList-strapi-backend.git
2. Install dependencies: npm install

## Usage

1. Start the server: npm run develop
2. Open your browser and visit http://localhost:1337

## API Documentation

- GET API on http://localhost:1337/api/todos => retrieve all todos related to specific user using token
- GET API on http://localhost:1337/api/todos/id=> retrieve only specific todo related to specific user
- GET API on http://localhost:1337/api/users/me?populate=todos => retrieve all user data includes todos
- GET API on http://localhost:1337/api/users/id=> retrieve specific user
- POST API on http://localhost:1337/api/todos => enable user to add new todo
- POST API on http://localhost:1337/api/auth/local => enable user to login
- POST API on http://localhost:1337/api/auth/local/register => enable user register
- PUT API on http://localhost:1337/api/todos/id => enable user to update specific todo
- DELETE API on http://localhost:1337/api/todos/id => enable user to delete specific todo

## License
- Huda Roushdy
