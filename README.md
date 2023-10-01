# Objective: Develop a backend system for managing books in a library.

# System Requirements:

1. Database: You must use a NoSQL database for this assignment.

2. Backend Framework: Choose between NestJS or FastAPI (Python) for backend development.
   
3. Submission: The solution must be submitted as a publicly available GitHub repository.
   
4. Bonus: Containerize your application using Docker to ensure it can be run locally without any setup issues.

   
# System Features:

NOTE: It is okay if you are not able to implement all the features listed here, that is actually intended with the idea being that you are able to implement the maximum pointers in the allotted time.

1. User Registration & Authentication
   
○ Register a new user with details like name, email, password.

○ Authenticate users for login.

○ Bonus: Implement JWT or similar authentication.

2. Book Management
   
○ Add new books with details like ISBN, title, author, published year, quantity.

○ Update book details.

○ Delete books.

○ List all available books.

3. Borrowing & Returning Books
   
○ Users can borrow a book.

○ Users can return a book.

○ A user should not be able to borrow more than 3 books at a time.

○ Implement a system to keep track of borrowed books and their return dates.

4. Search Functionality
   
○ Users should be able to search for a book by its title, author, or ISBN.

5. Algorithmic Challenge: Recommendation System
   
○ Recommend books to users based on the books they've previously borrowed.

○ Implement a simple recommendation system based on genres or authors.

○ Note: A complex machine learning model is not required. A heuristic-based
recommendation system would suffice.

6. RESTful API Implementation

○ Expose the functionalities as RESTful endpoints.

○ Implement API documentation using tools like Swagger.


# Optional Enhancements:

1. Logging: Implement logging to track activities within the system.
   
2. Rate Limiting: Implement rate limiting on the API.
   
3. Pagination: Implement pagination for listing books.
   
4. Tests: Write unit and integration tests for key functionalities.


# Steps to run

Step 1: cd into `backend`

Step 2: run "npm install" to install the dependencies

Step 3: rename the `.env.sample` file to `.env`

Step 4: now run "npm start"
