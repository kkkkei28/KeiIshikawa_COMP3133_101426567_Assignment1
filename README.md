# 📋 COMP 3133 - Assignment 1 (Employee Management System)

## 👤 **Student Information**
- **Name:** Kei Ishikawa
- **Student ID:** 101426567
- **Course:** COMP 3133 - Full Stack Development II

---

## 🚀 **Project Overview**
This project is an **Employee Management System** backend application built using:
- **Node.js**
- **Express**
- **GraphQL (Apollo Server)**
- **MongoDB (MongoDB Atlas)**

The project implements GraphQL APIs to handle employee management operations, including user signup, login, employee CRUD operations, and search functionalities.

---

## 📦 **Project Structure**
```
├── models/
│   ├── User.js
│   └── Employee.js
├── graphql/
│   ├── schema.js
│   └── resolvers.js
├── validators/
│   └── validation.js
├── .env
├── server.js
├── package.json
└── README.md
```

---

## ⚙️ **Setup Instructions**

1. **Clone the repository:**
```bash
git clone https://github.com/yourusername/KeiIshikawa_COMP3133_101426567_Assignment1.git
cd KeiIshikawa_COMP3133_101426567_Assignment1
```

2. **Install dependencies:**
```bash
npm install
```

3. **Configure environment variables:**
Create a `.env` file in the root directory:
```env
MONGODB_URI=your_mongodb_atlas_connection_string
PORT=4000
JWT_SECRET=your_jwt_secret_key
```

4. **Run the server:**
```bash
node server.js
```

5. **Access GraphQL Playground:**
```
http://localhost:4000/graphql
```

---

## 📋 **GraphQL APIs Implemented**

### **Mutation:**
1. `signup` - User registration
2. `login` - User authentication
3. `addEmployee` - Add new employee
4. `updateEmployee` - Update employee by ID
5. `deleteEmployee` - Delete employee by ID

### **Query:**
6. `getAllEmployees` - Retrieve all employees
7. `searchEmployeeByEid` - Search employee by ID
8. `searchEmployeeByDesignationOrDepartment` - Search employees by designation or department

---

## ✅ **Validation Implemented**
- **express-validator** is used to validate user inputs.
- Validation for required fields, email format, password length, ID format, etc.

---

## 🧪 **Testing**
- **GraphiQL** was used for manual API testing.
- **Postman** was used to verify API endpoints and validate error handling.
- All test results with screenshots are attached in the submission document.

---

## 📚 **Technologies Used**
- **Node.js**
- **Express**
- **GraphQL (Apollo Server)**
- **MongoDB Atlas**
- **Mongoose**
- **JWT (JSON Web Tokens)**
- **bcryptjs** (for password hashing)
- **express-validator** (for validation)

---

## 🔗 **GitHub Repository**
[GitHub Repository Link](https://github.com/yourusername/KeiIshikawa_COMP3133_101426567_Assignment1)

---

## 🗂️ **Sample User for Login Testing**
- **Username:** validuser
- **Email:** validuser@example.com
- **Password:** password123

Use this sample user for testing the login API in GraphiQL or Postman.

---

## 🚀 **Author**
**Kei Ishikawa** - COMP 3133 Assignment 1 Submission