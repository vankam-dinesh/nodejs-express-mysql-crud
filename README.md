Node.js Express MySQL CRUD API

A RESTful backend application built using Node.js, Express.js, and MySQL that performs basic CRUD (Create, Read, Update, Delete) operations.
This project demonstrates backend development concepts such as REST APIs, MVC architecture, and database integration.

📌 Features

Create, Read, Update, Delete (CRUD) operations

RESTful API design

MySQL database integration

Express routing and middleware

MVC folder structure

API testing using Postman

Error handling and validation

🛠 Tech Stack

Backend: Node.js, Express.js

Database: MySQL

Tools: Postman, Git

Architecture: MVC (Model–View–Controller)

📂 Project Structure
nodejs-express-mysql-crud/
 ├── app.js              # Entry point of the application
 ├── config/             # Database configuration
 ├── models/             # Database models
 ├── controllers/        # Business logic
 ├── routes/             # API routes
 └── package.json        # Project dependencies

🔗 API Endpoints
Method	Endpoint	Description
POST	/api/tutorials	Create a new record
GET	/api/tutorials	Get all records
GET	/api/tutorials/:id	Get record by ID
PUT	/api/tutorials/:id	Update a record
DELETE	/api/tutorials/:id	Delete a record
🗄 Database Schema (Example)
tutorials
- id
- title
- description
- published

⚙️ Installation & Setup

Clone the repository

git clone https://github.com/vankam-dinesh/nodejs-express-mysql-crud.git


Navigate to project directory

cd nodejs-express-mysql-crud


Install dependencies

npm install


Configure MySQL database
Update database credentials in the configuration file.

Start the server

npm start


Server will run on:

http://localhost:8080

🧪 Testing APIs

Use Postman to test API endpoints

Send HTTP requests (GET, POST, PUT, DELETE)

Verify responses and status codes

🎯 Learning Outcomes

Hands-on experience with Node.js backend development

Understanding REST API concepts

Working with MySQL databases

Implementing MVC architecture

API testing using Postman

🚀 Future Enhancements

JWT Authentication

Input validation

Pagination & filtering

Deployment to cloud platform

👨‍💻 Author

Dinesh Vankam
GitHub: https://github.com/vankam-dinesh
