# Dockerized Spring Boot Applications

This project includes two Dockerized Spring Boot applications, `RestDemoDocker` and `student-app`, designed to demonstrate the basics of setting up and running Spring Boot applications within Docker containers.

## 1. RestDemoDocker:

A REST-based Spring Boot application with a Dockerfile for containerization.
Contains standard Spring Boot structure, including source files, a pom.xml, and a target directory with a compiled JAR file.

## 2. student-app:

Another Spring Boot project, also set up for Docker with both a Dockerfile and a docker-compose.yml.
Includes components like Student.java, StudentController.java, StudentRepo.java, and an application.properties file, as well as data.sql for initializing data.

## Project Structure

- **RestDemoDocker**: A simple REST API created with Spring Boot, demonstrating a Docker setup.
- **student-app**: Another Spring Boot application, configured with Docker and Docker Compose to manage containers and initialize data.

### Prerequisites

- **Docker**: Ensure Docker is installed and running on your system. [Install Docker](https://docs.docker.com/get-docker/)
- **Docker Compose** (for `student-app`): Required for multi-container applications. [Install Docker Compose](https://docs.docker.com/compose/install/)

