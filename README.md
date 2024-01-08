# Currency Conversion Service

Welcome to the Currency Conversion Service, a demo project powered by Spring Boot. This service is designed to facilitate currency conversion within a microservices architecture.

## Project Details

### Module: currency-conversion-service

- **Java Version:** 1.8
- **Spring Boot Version:** 2.2.1.RELEASE
- **Spring Cloud Version:** Hoxton.RC2

## Dependencies

- **spring-boot-starter-actuator:** Production-ready features for monitoring and managing the application.
- **spring-boot-starter-web:** Starter for building web applications, including RESTful services.
- **spring-cloud-starter-config:** Integrates Spring Cloud Config Server for externalized configuration.
- **spring-cloud-starter-openfeign:** Provides declarative REST clients through Feign.
- **spring-cloud-starter-netflix-eureka-client:** Integrates with Netflix Eureka for service registration and discovery.
- **spring-cloud-starter-netflix-ribbon:** Client-side load balancing for communication between microservices.
- **spring-boot-devtools:** Enhances development experience with automatic application restarts and more.
- **spring-boot-starter-test:** Dependencies for testing, excluding JUnit 4 (vintage engine).

## Build Configuration

The Maven build configuration ensures seamless integration with the Spring Boot application. The Spring Boot Maven plugin simplifies the packaging and execution of the application.

## Repository Configuration

The project includes a repository for Spring Milestones to access the required dependencies.

## Usage

This project is an essential component for currency conversion within a microservices ecosystem. To get started, clone the repository and run the application:

```bash
mvn spring-boot:run
```

Explore the capabilities of the Currency Conversion Service and leverage its integration with Eureka and Feign for seamless communication with other microservices.

## Contributions and Issues

Feel free to contribute to the project by submitting pull requests or reporting issues. Your feedback is valuable as we continue to enhance and refine the Currency Conversion Service in the world of microservices. Let's build and innovate together!
