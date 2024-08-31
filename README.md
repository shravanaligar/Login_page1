# Login and Welcome Page Project

## Overview
This project implements a simple user authentication system with a login page and a welcome page. It is built using Java Servlets, JSP, and JDBC for MySQL database connectivity. The project is designed to demonstrate the integration of front-end and back-end technologies in a web application.

## Features
- **User Authentication:** Allows users to log in with a username and password.
- **Welcome Page:** Displays a personalized welcome message after successful login.
- **Database Connectivity:** Utilizes MySQL Workbench for user data storage and retrieval.
- **Session Management:** Maintains user sessions to prevent unauthorized access to the welcome page.

## Technologies Used
- **Java Servlets**
- **JSP (JavaServer Pages)**
- **JDBC (Java Database Connectivity)**
- **MySQL Workbench**
- **Apache Tomcat (for deployment)**
- **Eclipse IDE (or any preferred Java IDE)**

## Project Structure
```plaintext
src/
│
├── com.example.servlet
│   ├── LoginServlet.java
│   └── WelcomeServlet.java
│
├── com.example.util
│   └── DatabaseConnection.java
│
web/
│
├── login.jsp
└── welcome.jsp
**IMP: Add JAR file.**
