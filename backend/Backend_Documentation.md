# Backend Documentation

# 1. Project Overview

The backend of the Digital Subsidy and Grant Administration Platform
is developed using Spring Boot.

It provides REST APIs for managing beneficiaries, subsidy applications,
officer verification, admin approval, milestone-based disbursement,
and field inspection.

# 2. Technologies Used

- Java
- Spring Boot
- Spring Data JPA
- REST API
- MySQL
- Maven

# 3. Backend Structure

The backend follows a layered architecture:

- Controller Layer – Handles HTTP requests and API endpoints.
- Service Layer – Contains business logic.
- Repository Layer – Communicates with the database.
- Entity Layer – Represents database tables and application data.
- Configuration Layer – Contains application configuration.

# 4. Main Features

- Beneficiary registration and management
- Subsidy and grant application management
- Officer verification
- Admin approval
- Milestone-based subsidy disbursement
- Field inspection management
- Application status tracking
- Database management

# 5. REST API

The backend exposes REST APIs that allow the frontend to communicate
with the application server.

The APIs support operations such as:

- Create application
- View applications
- Update application status
- Verify applications
- Approve applications
- Manage subsidy disbursement
- Manage field inspections

# 6. Database

The application uses MySQL for storing application data.

The database stores information related to:

- Beneficiaries
- Applications
- Subsidies and grants
- Officers
- Approvals
- Disbursements
- Field inspections

# 7. Communication with Frontend

The React frontend communicates with the Spring Boot backend using
HTTP requests through REST APIs.

Data is exchanged mainly in JSON format.

# 8. Installation and Setup

## Prerequisites

- Java JDK
- Maven
- MySQL
- Git

### Steps

1. Clone the repository.
2. Open the backend folder.
3. Configure the MySQL database.
4. Update the database configuration in the application properties.
5. Install dependencies using Maven.
6. Run the Spring Boot application.

# 9. Running the Backend

Use the following command:

mvn spring-boot:run

After starting the server, the REST APIs can be accessed from the
frontend application.

## 10. Security and Validation

The backend validates incoming requests and application data before
processing them.

Appropriate authentication, authorization, and input validation can
be applied to protect application data and APIs.

## 11. Error Handling

The backend handles invalid requests and server-side errors and
returns appropriate HTTP status codes and error responses.

## 12. Conclusion

The Spring Boot backend provides a reliable REST API layer for the
Digital Subsidy and Grant Administration Platform and supports
communication between the frontend, business logic, and database.
