# Spring Boot Microservices with Spring Cloud

This repository contains an example project demonstrating the use of microservices architecture with Spring Boot and Spring Cloud. The microservices in this project interact with each other using Eureka for service discovery, Spring Cloud Config for centralized configuration management, and Spring Cloud Gateway for API routing.

## Microservices Included

1. **Product Service**: A service that exposes a REST API for managing products.
2. **Config Service**: A centralized service for managing configuration files for all microservices.
3. **Proxy Service**: A gateway service that routes requests to the appropriate microservice and performs load balancing.
4. **Discovery Service**: A service that registers and manages instances of the other microservices for dynamic service discovery.

## Architecture

The system is built using the following technologies:
- **Spring Boot** 3.0.0 or higher
- **Spring Cloud** 2022.0.0 or higher
- **Java** 17
- **Maven** 4.0.0
- **IntelliJ IDEA** (Ultimate Edition)
- **H2 Database** for the Product Service
- **Eureka** for service discovery

## Features
- **Service Discovery**: Using Netflix Eureka to register and discover services.
- **Centralized Configuration**: Spring Cloud Config provides a centralized place for managing configurations across microservices.
- **API Gateway**: Spring Cloud Gateway acts as the reverse proxy, forwarding requests to the appropriate service.
- **Load Balancing**: Proxy Service automatically balances the load between multiple instances of Product Service.

## Setup

### Prerequisites
- Java 17
- Maven 4.0.0
- IntelliJ IDEA (or your preferred IDE)
