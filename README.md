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

Step 3: run "run start" to start the backend server

Step 4: cd into `frontend`

Step 5: run "npm install" to install the dependencies

Step 6: run "run start" to start the frontend application


# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.
