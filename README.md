# Spring Microservices Demo

## Setup 

1. pull down the 5 projects
2. build them all locally to run `./gradlew clean bootJar`

## Run Order

1. start up Eureka
2. start up the Admin Client
3. start up the other services

## Demonstration

1. Administration --> http://localhost:7999/wallboard
2. Discovery --> http://localhost:8761
3. REST on a DB --> http://localhost:8080/api/db-via-rest
4. Microservice using other services --> http://localhost:8080/api/be-service/people
5. Dynamic Gateway Discovery --> http://localhost:8080/actuator/gateway/routes
