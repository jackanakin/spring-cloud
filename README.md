# Spring Boot Microservices with Spring Cloud
> https://www.udemy.com/course/spring-boot-microservices-with-spring-cloud-beginner-to-guru

* Develop Microservices with Spring Boot
* Deploy and manage Spring Boot Microservices with Spring Cloud
* Deconstruct a monolith into Spring Boot Microservices
* Best Practices for Developing RESTFul APIs with Spring MVC
* Consuming RESTFul APIs using Spring RestTemplate
* Using Java Bean Validation with Spring Boot
* Using Project Lombok and MapStruct to reduce boiler plate code
* Generate API documentation with Spring REST Doc
* Configure Jackson for JSON processing with Spring Boot
* Using JMS for messaging between Spring Boot Microservices
* Using Spring State Machine to Apply the Saga Pattern with Microservices

## 0.Final Project


## 1.simple-rest
> Very basic spring REST API with Lombok and api versioning

## 2.integration-test
> Integration test using spring's RestTemplate against the above REST API

## 3.nio-http-client
> RestTemplateCustomizer with: Non blocking (DefaultConnectingIOReactor) vs Blocking for integration test

## 4.validation-and-controller-advice
> Bean Validation and Controller Advice for exception handler

## 5.mapstruct-lombok
> MapStruct for Dto <-> Entity conversion + Lombok to elimante getters and setters boiler code

## 6.restdocs
> Spring REST Docs to generate documentation snippets

## 7.json-processing
> Using Jackson for Custom @JsonSerialize(using), @JsonDeserialize(using), @JsonFormat(pattern,shape), @JsonProperty("customField")

## 8.jms
> Sample using Apache MQ to send and receive messages through an Apache MQ Server on a docker container `docker run --rm -p 8161:8161 -p 61616:61616 vromero/activemq-artemis`

## 9.state-machine
> Sample using Spring State Machine with Actions, States, Guards and Interceptors
