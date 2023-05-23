# microservices
Technologies:
- Spring Boot 3
- Java 17

This repository contains a demo project that showcases a practical microservices-based application. It helps users gain hands-on experience and understand microservices architecture. The project includes key components like an API Gateway, Config Server, Discovery Server, and two microservices: Student and School.

- The API Gateway acts as a central entry point, handling client requests and effectively routing them to the appropriate microservices. It serves as a crucial component for managing and coordinating communication between clients and the microservices ecosystem.

- The Configuration Server serves as a centralized hub for managing configuration settings across all microservices. It simplifies application maintenance and ensures consistency in configurations across different environments.

- The Discovery Server provides service registration and discovery capabilities within the microservices ecosystem. It enables seamless communication and interaction between microservices by allowing them to locate and connect with each other dynamically.

- The Student Microservice is responsible for managing student-related data and operations. It includes functionalities such as adding, and retrieving student records.

- The School Microservice handles school-related data and operations like adding and retrieving school records.

Inter-Service Communication: OpenFeign is utilized in this project to demonstrate inter-service communication within the microservices ecosystem. OpenFeign is a declarative REST client that simplifies the process of communicating between services, making it easier to establish and manage communication channels.

Distributed Tracing: The project incorporates Zipkin for distributed tracing purposes. By using Zipkin, the system gains the ability to trace and monitor requests as they traverse across different microservices. This enhances application observability by providing insights into request flows, latency, and potential issues. Zipkin enables the visualization and troubleshooting of latency issues, helping to identify and resolve performance bottlenecks within the system.
