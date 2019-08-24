# Web Systems Architecture POC
Respository to group the components of web systems architecture POC implementation.
It's necessary to configure the environment(ip address, server port, database etc) to run the architecture properly

# Discovery Service
Spring Boop Netflix Eureka Service Discovery
https://github.com/erinaldosouza/eureka-business-service-discovery

# Business Service
Spring Boot User service API business operations
https://github.com/erinaldosouza/users-microservices
PS: It's necessary a Eureka Server up and running.

# Persistence Service - Relational
Spring Boot User persistence service API with CRUD operations
https://github.com/erinaldosouza/users-persistence-microservices
PS: It's necessary a RabbitMQ Server, Eureka Server and PostgreSQL up and running

# Persistence Service - Non-relational
NodeJS, Express and MongoDB with non-relational model CRUD operations
https://github.com/erinaldosouza/documents-persistence-service
PS: It's necessary a RabbitMQ Server, Eureka Server and MongoDB up and running

# Authenticator Manager
Python + Django applicaion used to manager user access control
https://github.com/erinaldosouza/django-auth-manager
PS: It's necessary MySQL Server and Eureka Server up and running

# Authenticator
Spring Boot Security application responsable for users authentication with login and password and  access token generation
https://github.com/erinaldosouza/authenticator
PS: It's necessary MySQL Server and Eukrea Server up and running

# Authorizer
Spring Boot application responsable for access authorization to resources
https://github.com/erinaldosouza/authorizer
PS: It's necessary a Eureka Server up and running

# Nginx Api Gateway
Nginx Api Gateway configuration files
https://github.com/erinaldosouza/nginx-api-gateway

# Sys Monolithic
Monolithic implementation used to analyse performance between the architectures
https://github.com/erinaldosouza/sys-monolithic
PS: It's necessary PostgreSQL Server up and running

# Test Scripts - JMeter and Selenium IDE





