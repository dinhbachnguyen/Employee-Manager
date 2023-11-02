# Employee Manager Application

## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [Getting Started](#getting-started)
   - [Prerequisites](#prerequisites)
   - [Installation](#installation)
4. [Usage](#usage)
5. [Configuration](#configuration)


## 1. Introduction

Welcome to the Employee Manager Application, a Human Resources management system built using Angular for the frontend and Spring Boot for the backend. This application is designed to streamline and simplify HR-related tasks such as employee management, leave requests, and more.

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
   git clone https://github.com/dinhbachnguyen/Employee-Manager.git
   cd Employee-Manager
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

3. Open your web browser and go to `http://localhost:4200` to access the Employee Manager Application.

## 5. Configuration

- **Database Configuration**: Update the database connection details in the '\back-end\src\main\resources\application.properties"' file located in the backend project.



