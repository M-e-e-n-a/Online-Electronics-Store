# Online Electronics Store

This repository contains a Spring Boot-based microservices project for an online electronics store. The application is divided into three primary services:

1. **Order Service**: Manages customer orders.
2. **Shipping Service**: Handles shipping logistics for orders.
3. **Invoice Service**: Generates invoices for completed orders.

## Features

- **Microservices Architecture**: Each service is self-contained and communicates with others via REST APIs.
- **Spring Boot**: Simplified configuration and development.
- **Dockerized Services**: Services are containerized for easy deployment and scalability.
- **PostgreSQL Database**: Each service is connected to its own PostgreSQL database for data persistence.
- **Centralized Configuration and Service Discovery** (if applicable).

## Prerequisites

Before running this project, ensure you have the following installed:

- [Java 17](https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html)
- [Maven](https://maven.apache.org/)
- [Docker](https://www.docker.com/)

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/your-username/online-electronics-store.git
cd online-electronics-store

Build the Project
mvn clean install

Run the Application with Docker
To run all services using Docker, execute the following command:
docker-compose up

Accessing the Services
Once the application is running, you can access the services at their respective endpoints:

Order Service: http://localhost:18081
Shipping Service: http://localhost:18082
Invoice Service: http://localhost:18083

###DEMO
You can access the demo of the application at the following link: [Click here to access the demo](https://drive.google.com/file/d/1uiymQIjspPNv-Gt97dVTCYjC32mXaqSy/view?usp=drive_link)
