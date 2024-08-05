# Task Management System

## Description
A Task Management System where users can sign up, log in, and manage their tasks. The application features user authentication, task creation, viewing, updating, and soft-deleting tasks. The frontend is built with React, the backend with Node.js, and PostgreSQL is used for storing user and task data. JWT is used for session management, and passwords are hashed before storing them in the database.

## Features
- **User Authentication**:
  - Sign up and Login pages.
  - JWT for session management.
  - Hashed passwords for security.

- **Task Management**:
  - Create Task: Users can create new tasks.
  - View Tasks: Users can view all their tasks.
  - Update Task: Users can edit their tasks.
  - Delete Task: Users can soft delete tasks.

## Technologies Used
- **Frontend**: React
- **Backend**: Node.js, Express.js
- **Database**: PostgreSQL
- **Authentication**: JWT, bcryptjs
- **Environment Variables**: dotenv


## Usage

1. Start the backend server:
    ```sh
    cd backend
    node server.js
    ```

2. Start the frontend server:
    ```sh
    cd frontend
    cd practice
    npm run dev
    ```

3. Open your browser and navigate to `http://localhost:3000`.



