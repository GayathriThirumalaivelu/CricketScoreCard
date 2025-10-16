# CricketScoreCard
A Spring Boot and MySQL-based web application for managing and displaying cricket match details, including teams, innings, and player statistics. Fully containerized with Docker for easy deployment and testing
It provides RESTful APIs to perform CRUD operations and fetch match data dynamically.
# Features
Add, update, and retrieve cricket match details
Maintain records for batsmen, bowlers, and innings
Connects to a MySQL database for persistent storage
Dockerized for easy setup and deployment
Follows REST API design principles

# Tech Stack
Backend: Spring Boot (Java 17)
Database: MySQL 8
Build Tool: Maven
Containerization: Docker
ORM: Hibernate / JPA

# How to Run
Clone the repository
  # Build the project:
    ./mvnw clean package -DskipTests
  # Run MySQL and the Spring Boot app using Docker:
     docker-compose up
  # Access the application at:
    http://localhost:8080
