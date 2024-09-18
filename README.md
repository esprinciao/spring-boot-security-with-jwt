# spring-boot-security-with-jwt
This project demonstrates how to secure a Spring Boot application using JSON Web Tokens (JWT). It showcases user authentication and authorization using Spring Security and JWT.

## Features

- User Registration and Login
- JWT-based Authentication
- Role-based Authorization
- Secure REST API Endpoints

## Prerequisites

- Java 11 or higher
- Maven (for dependency management)
- Spring Security Dependencies


### Add Dependencies

In your `pom.xml`, include the following dependencies:

```xml
<dependency>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-security</artifactId>
</dependency>
<dependency>
    <groupId>io.jsonwebtoken</groupId>
    <artifactId>jjwt</artifactId>
    <version>0.9.1</version>
</dependency>
<dependency>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-web</artifactId>
</dependency>

