# Good-Steward-Task-Management API

This project is the backend API for the **Good-Steward-Task-Management** application. It handles task data management, user authentication, and integrates with the frontend to provide a seamless full-stack experience.

## Technologies Used

- **Spring Boot (Java)**: A framework for building robust backend applications with Java, simplifying configuration and development.
- **MySQL**: A relational database used to store tasks and user data.

## API Endpoints

### Authentication

- **POST /auth/signup**: Register a new user.
- **POST /auth/login**: Login and start a session.
- **POST /auth/logout**: Logout the user and invalidate the session.

### Task Management

- **GET /tasks**: Retrieve a list of tasks for the authenticated user.
- **POST /tasks**: Create a new task.
- **PUT /tasks/:id**: Update an existing task.
- **DELETE /tasks/:id**: Delete a task.

## Project Overview

This API is designed to provide a robust backend for managing tasks and handling user authentication. It integrates with the frontend, where users can:

- **Create and manage tasks**: Tasks can be created, updated, and deleted.
- **User authentication**: Handles secure user login and session management using Spring Security.

## Full-Stack Principles

- **Authentication**: Integrated with Spring Security for handling user authentication and session management.
- **RESTful API**: Built using REST principles for scalability and simplicity.
