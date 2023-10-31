# RH Manager Application

## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [Getting Started](#getting-started)
   - [Prerequisites](#prerequisites)
   - [Installation](#installation)
4. [Usage](#usage)
5. [Configuration](#configuration)
6. [Contributing](#contributing)
7. [License](#license)

## 1. Introduction

Welcome to the RH Manager Application, a Human Resources management system built using Angular for the frontend and Spring Boot for the backend. This application is designed to streamline and simplify HR-related tasks such as employee management, leave requests, and more.

## 2. Features

- **Employee Management**: Easily add, update, or remove employee records.
- **User Authentication**: Secure login and role-based access control.

## 3. Getting Started

### Prerequisites

Before you begin, ensure you have met the following requirements:

- **Angular CLI**: You will need Angular CLI to run the frontend. Install it using `npm install -g @angular/cli`.

- **Java**: Make sure you have Java 8 or higher installed on your system for the Spring Boot backend.

- **Maven**: You will need Apache Maven to build and run the Spring Boot backend. Install it from [Maven's official website](https://maven.apache.org/download.cgi).

- **Database**: The application uses a database to store employee and leave data. Ensure you have a compatible database (e.g., MySQL, PostgreSQL) installed and properly configured.

### Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/yourusername/rh-manager.git
   cd rh-manager
   ```

2. **Frontend Setup**:

   ```bash
   cd frontend
   npm install
   ```

3. **Backend Setup**:

   ```bash
   cd backend
   mvn install
   ```

## 4. Usage

1. **Run the Backend**:

   ```bash
   cd backend
   mvn spring-boot:run
   ```

2. **Run the Frontend**:

   ```bash
   cd frontend
   ng serve
   ```

3. Open your web browser and go to `http://localhost:4200` to access the RH Manager Application.

## 5. Configuration

- **Database Configuration**: Update the database connection details in the `application.properties` file located in the backend project.

- **Authentication**: Configure user roles and permissions in the `SecurityConfig.java` file in the backend project.

## 6. Contributing

We welcome contributions to the RH Manager Application. To contribute, follow these steps:

1. Fork the repository.

2. Create a new branch for your feature or bug fix:

   ```bash
   git checkout -b feature/your-feature-name
   ```

3. Make your changes and commit them with clear messages.

4. Push your changes to your fork:

   ```bash
   git push origin feature/your-feature-name
   ```

5. Create a pull request to the main repository's `main` branch.

## 7. License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Thank you for using the RH Manager Application! If you have any questions or need assistance, please don't hesitate to reach out to us.
