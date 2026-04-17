# Backend-app-assignment

# Project Description
This is a simple backend project built using Express and Sequelize with MySQL.

# The project includes :
- User model
- Order model
- One-to-Many relationship
- Full CRUD operations for both models

# Technologies Used :
- Node.js
- Express.js
- Sequelize
- Sequelize CLI
- MySQL
- XAMPP to work with MySQL

# Models & Relationships :

Models :
- User : ( id, name, email)
- Order : (id, productName, amount, userId)
Relationships :
- One User has many Orders / One Order belongs to one User

## Setup Instructions
1- ( npm install ) to Install dependencies
2- create Database using MySQL named ( backend_app_db )
3- Run migrations ( npx sequelize-cli db:migrate )

To run the Project :
1- open terminal or  git bash
2- write ( npm run dev )

### Available APIs

### For Users :
- POST /users  to Create new user
- GET /users  to Get all users
- GET /users/:id  to Get user by id
- PUT /users/:id  to Update specific user information
- DELETE /users/:id  to Delete specific user

### For Orders :
- POST /orders  to Create a new order
- GET /orders  to Get all orders
- GET /orders/:id  to Get order by id
- PUT /orders/:id  to Update a specific order information
- DELETE /orders/:id  to Delete specific order








