# NodeJS

1. What is NodeJS
2. Nodejs vs Browser
3. HTTP Methods, Headers, cookies
4. REST API
5. Installation and run nodejs from command line
6. npm
   1. installing packages locally
   2. installing packages globally
   3. Update and uninstall packages
   4. running script
7. Node.js Modules
   1. common js
   2. ESM
8. Building Web Servers with Node
9. Introduction to Express
10. Routes & Middleware

### Assignments

**Objective:** Build a simple RESTful API for a Task Management System using Node.js and MongoDB.

### Part 1: Project Setup

1. **Initialize a Node.js Project:**

   - Create a new Node.js project using `npm init`.

2. **Install Dependencies:**
   - Install the necessary dependencies, including Express for the web framework and Mongoose for MongoDB integration.

### Part 2: RESTful API Implementation

1. **Task Model:**

   - Define a Task model with properties like `title`, `description`, `dueDate`, and `completed`.

2. **RESTful Endpoints:**
   - Implement the following RESTful endpoints:
     - `GET /tasks`: Retrieve all tasks.
     - `GET /tasks/:id`: Retrieve a specific task by ID.
     - `POST /tasks`: Create a new task.
     - `PUT /tasks/:id`: Update a task by ID.
     - `DELETE /tasks/:id`: Delete a task by ID.

### Part 3: Route Setup

1. **Route Configuration:**
   - Set up Express routes to handle requests for the defined RESTful endpoints.
   - Organize your routes into a separate module.

### Part 4: Middleware Setup

1. **Logger Middleware:**

   - Create a middleware function that logs information about incoming requests (method, path, timestamp).

2. **Error Handling Middleware:**
   - Implement a global error handling middleware to catch and log errors.
   - Customize error responses for different scenarios (e.g., invalid input, not found).

### Part 5: MongoDB Integration

1. **Connect to MongoDB:**

   - Use Mongoose to connect to a MongoDB database.

2. **CRUD Operations:**

   - Implement functions to perform CRUD operations on the Task model using Mongoose.

3. **Integration Testing:**
   - Perform integration tests to ensure that your API works as expected.

### Part 7: Documentation

1. **API Documentation:**
   - Create simple documentation for your API, including the available endpoints and expected request/response formats.
