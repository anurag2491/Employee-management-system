https://github.com/user-attachments/assets/f71da52d-07a7-4877-8809-d700de46d7a3


Employee Management System

This project demonstrates how to develop a full-stack CRUD (Create, Read, Update, Delete) application using React for the frontend and Spring Boot for the 
backend. The application manages employee data, providing functionalities to add, view, update, and delete employee records.





Project Structure

The project is divided into two main folders:

springboot-backend: Contains the Spring Boot application that provides RESTful APIs for managing employee data.

react-frontend: Contains the React application that consumes the APIs and provides a user interface for interacting with the employee data.






Technologies Used


Backend (Spring Boot Application)

1.Spring Boot - Framework for building Java-based RESTful services

2.Spring Data JPA - ORM framework for database interactions

3.MySQL - Relational database for storing employee data

4.Spring Boot DevTools - Provides auto-restart and live reload

5.Lombok - Reduces boilerplate code using annotations

6.Maven - Dependency management and build automation


Frontend (React Application)

1.React - JavaScript library for building UI components

2.React Router - Handles client-side navigation

3.Axios - HTTP client for making API calls

4.Bootstrap - CSS framework for responsive design

5.React Hooks - Manages component state and side effects





Features

1.Employee Management: Add, view, update, and delete employees

2.RESTful API: Backend exposes endpoints for CRUD operations

3.Database Integration: MySQL used for persistent storage

4.Responsive UI: Frontend designed using Bootstrap

5.Error Handling: Proper validations and error messages






Prerequisites

Before running the applications, ensure you have the following installed:

1.Java Development Kit (JDK) 8 or higher

2.Node.js (which includes npm)

3.MySQL database






Getting Started

Backend (Spring Boot Application)

1.Configure Database:

  Update the application.properties file in the springboot-backend directory with your MySQL database credentials.

2.Build and Run:

  Navigate to the springboot-backend directory.

3.Use Maven to build the application:

  mvn clean install

4.Run the application:

  mvn spring-boot:run

The backend server will start at http://localhost:8080.



Frontend (React Application)

1.Install Dependencies:

  Navigate to the react-frontend directory.

2.Install the required npm packages:

  npm install

3.Run the Application:

  Start the React application:
  
  npm start

The frontend application will run at http://localhost:3000.



![image](https://github.com/user-attachments/assets/e4a6d793-939f-4cdb-b740-ba499f34bc43)
![image](https://github.com/user-attachments/assets/75519498-3f9b-4581-9f0e-f5e0b0e39c1e)




Future Enhancements

1.Add authentication and authorization using JWT

2.Implement unit and integration testing

3.Deploy application to cloud services like AWS or Heroku






