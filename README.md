Employee Management System

This project demonstrates how to develop a full-stack CRUD (Create, Read, Update, Delete) application using React for the frontend and Spring Boot for the backend. The application manages employee data, providing functionalities to add, view, update, and delete employee records.

Project Structure

The project is divided into two main folders:
springboot-backend: Contains the Spring Boot application that provides RESTful APIs for managing employee data.
react-frontend: Contains the React application that consumes the APIs and provides a user interface for interacting with the employee data.

Prerequisites

Before running the applications, ensure you have the following installed:
Java Development Kit (JDK) 8 or higher
Node.js (which includes npm)
MySQL database

Getting Started

Backend (Spring Boot Application)
Configure Database:
Update the application.properties file in the springboot-backend directory with your MySQL database credentials.
Build and Run:
Navigate to the springboot-backend directory.
Use Maven to build the application:
mvn clean install
Run the application:
mvn spring-boot:run
The backend server will start at http://localhost:8080.

Frontend (React Application)

Install Dependencies:
Navigate to the react-frontend directory.
Install the required npm packages:
npm install
Run the Application:
Start the React application:
npm start
The frontend application will run at http://localhost:3000.


