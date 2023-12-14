# MongoDB

1. SQL vs NoSQL
2. Entity Relationship Diagram (ERD)
   1. Create an ERD for a blogging platform with the following entities: Users, Posts, and Comments.
   2. Define relationships between entities. For example, a User can have multiple Posts, and a Post can have multiple Comments
3. What is MongoDB

   1. Key Features of MongoDB
   2. When to use MongoDB

4. What is MongoDB Atlas?
5. MongoDB Terminology

   - Database
   - Collection
   - Document
   - Field
   - Index
   - Query
   - Cursor
   - Aggregation
   - Replica Set
   - Sharding

6. Data Model and Data Types
7. Collection Methods

   1. `insert`
   2. `find`
   3. `update`
   4. `deleteOne and others`
   5. `bulkWrite and others`

8. Useful Concepts

   1. Documents and Collections
   2. MongoDB Query Language (MQL)
   3. Aggregation Framework
   4. Read / Write Concerns
   5. Cursors
   6. Retryable Reads / Writes

9. CRUD Operation
10. Mongoose

## Assignments

### Part 2: Database Implementation

1. **Database Setup:**

   - Install MongoDB on your local machine or use a cloud-based MongoDB service.
   - Create a new database for the blogging platform.

2. **Collection Creation:**

   - Implement the defined schema by creating the necessary collections (Users, Posts, Comments) in your MongoDB database.

3. **Data Population:**
   - Insert sample data into each collection to represent multiple users, posts, and comments.

### Part 3: CRUD Operations

1. **User Management:**

   - Implement CRUD operations for Users (Create, Read, Update, Delete).
   - Test your operations by adding, retrieving, updating, and deleting user records.

2. **Post Management:**

   - Implement CRUD operations for Posts.
   - Test the operations by creating, retrieving, updating, and deleting blog posts.

3. **Comment Management:**
   - Implement CRUD operations for Comments.
   - Test the operations by adding, retrieving, updating, and deleting comments.

### Part 4: Querying and Indexing

1. **Querying:**

   - Write queries to retrieve:
     - All posts by a specific user.
     - All comments on a specific post.
     - Users who have made comments.

2. **Indexing:**
   - Identify fields that would benefit from indexing in your collections.
   - Implement indexing on those fields and measure the impact on query performance.
