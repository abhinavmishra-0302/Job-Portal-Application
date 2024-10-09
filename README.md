# Job Portal Application

Welcome to the Job Portal application! This project is designed to provide a comprehensive platform for job seekers and employers, leveraging a microservices architecture with Spring Boot.

## Project Overview

The Job Portal application consists of several microservices, each responsible for different functionalities within the platform. The microservices are developed using Spring Boot and are designed to work together to provide a seamless user experience.

### Microservices

1. **Authentication Service**: Handles user authentication and JWT-based authorization.
   - [Auth-Service](https://github.com/abhinavmishra-0302/Auth-Service.git)

2. **User Profile Service**: Manages user profiles for job seekers and employers.
   - [User-Profile-Service](https://github.com/abhinavmishra-0302/User-Profile-Service.git)

3. **Job Service**: Manages job listings and related operations.
   - [Job-Service](https://github.com/abhinavmishra-0302/Job-Service.git)

4. **Application Service**: Manages job applications and their statuses.
   - [Application-Service](https://github.com/abhinavmishra-0302/Application-Service.git)

5. **Notification Service**: Handles notifications for job seekers and employers.
   - [Notification-Service](https://github.com/abhinavmishra-0302/Notification-service.git)

## Tech Stack

- **Backend**: Spring Boot, Java
- **Database**: MySQL
- **Microservices Architecture**: Spring Boot, Maven, RabbitMQ
- **Security**: JWT (JSON Web Tokens)
- **Frontend (Future)**: Flutter (if applicable)
- **Other Tools**: Maven, Git

## Getting Started

To get started with the Job Portal application:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/abhinavmishra-0302/job-portal.git

2. **Navigate to Each Microservice Directory:**
   - For example: cd auth-service
3. **Build and Run Each Microservice:**
   - Ensure you have Maven installed.
   - Run mvn clean install to build the microservice.
   - Run mvn spring-boot:run to start the microservice.

4. **Setup Databases and Configuration:**
   - Configure the database settings in application.properties for each microservice as needed.
   - Ensure that the RabbitMQ server is running and properly configured.

5. **Access the Application:**
   - Once all microservices are running, you can access their respective endpoints as defined in their documentation.

## Documentation
For detailed documentation on each microservice, please refer to their respective repositories linked above. Each microservice includes its own set of documentation on available endpoints, request formats, and response formats.
