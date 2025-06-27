**Table of Contents**

[TOCM]

[TOC]

#H1 header
##H2 header
###H3 header
####H4 header
#####H5 header
######H6 header

# Spring Security
- Spring Security is a powerful and highly customizable security framework that is often used in springboot applications to handle authentication and authorization.
## Authentication
- The process of verifying user's  identity. (e.g. username and password)
## Authorization
- The process of granting or denying access to specific resources or actions based on authenticated user's roles and permissions.
  
## Dependency
```bash
<dependency>
            <groupId>org.springframework.boot</groupId>
            <artifactId>spring-boot-starter-security</artifactId>
</dependency>
```
- Once the dependency is added , Spring Boot's auto-configuration feature will automatically apply security to the application.
- By default, Spring Security uses HTTP Basic authentication.
