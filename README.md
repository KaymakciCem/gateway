# gateway
___
### Spring Boot Application

---
This project helps us to navigate between microservices. 
It recives the requests from the client and based on the url, it forwards the request to the dedicated microservice.

### Tech Stack

---
- Java 11
- Spring Boot
- Docker
- K8s files

### Prerequisites

---
- Maven

### Run & Build

first go to the terminal and open up the project directory. "~/account-service/"

### Run the tests

mvn test

### Run project

mvn spring-boot:run

### Docker
to create the docker image execute the following commands
mvn clean package
mvn docker:build
