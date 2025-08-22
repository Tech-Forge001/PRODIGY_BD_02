# PRODIGY_BD_02

# 🚀 Task 02 - Node.js User API

This repository contains the implementation of **Task 02**, which demonstrates building a simple REST API using **Node.js**, **Express.js**, and **MongoDB (Mongoose)**.  

---

## 📂 Project Structure
node_tutorial/
│── app.js
│── package.json
│── .gitignore
│── .env.example
│── /models
│ └── user.js
│── /routes
│ └── userRoutes.js


---

## 🛠️ Installation & Setup

### 1️⃣ Clone the Repository
git clone <your-repo-url>
cd node_tutorial
2️⃣ Install Dependencies
npm install
3️⃣ Environment Variables
Create a .env file in the project root (do not commit this file) and add:
MONGO_URI=your_mongodb_connection_string
An example is provided in .env.example.

4️⃣ Run the Application
node app.js
Server will start at:
👉 http://localhost:3000

📌 API Endpoints
User Routes (/users)
POST /users → Create a new user

GET /users → Get all users

GET /users/:id → Get a user by ID

PUT /users/:id → Update a user by ID

DELETE /users/:id → Delete a user by ID

📬 Sample Postman Requests
1️⃣ Create User
POST http://localhost:3000/users
Body (JSON):
{
  "name": "Aastha",
  "email": "aastha@example.com",
  "age": "19"
}
2️⃣ Get All Users
GET http://localhost:3000/users

3️⃣ Get Single User by ID
GET http://localhost:3000/users/<user_id_here>

4️⃣ Update User
PUT http://localhost:3000/users/<user_id_here>
Body (JSON):
{
  "name": "Aastha Pathak",
  "email": "aasthapathak@example.com"
}
5️⃣ Delete User
DELETE http://localhost:3000/users/<user_id_here>

🧰 Technologies Used

Node.js
Express.js
MongoDB & Mongoose
dotenv

->MongoDB connection is handled in app.js file


✅ Task 02 completed with full CRUD implementation, MongoDB integration, and Postman testing support.

