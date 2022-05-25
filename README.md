# gateway
___
### Spring Boot Application

---
This project helps us to navigate between microservices. 
It recives the requests from the client and based on the url, 
it forwards the request to the dedicated microservice.

The transaction-service and account-service are the microservices that
this api-gateway communicates two different microservices. 
Please see the microservices as follows. By executing their

transaction-service
https://github.com/KaymakciCem/transaction-service

account-service
https://github.com/KaymakciCem/transaction-service

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

### Run on local k8s
deploy.yaml file is for kubernetes and it will automatically pick up the configuration
to do this execute
kubectl apply -f deploy.yaml

Navigate to the url http://localhost:30020
Then you can call the openAccount and retrieve customer information by using the following endpoints




### Docker
to create the docker image execute the following commands
mvn clean package
mvn docker:build
