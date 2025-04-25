# Order Analyser

A Spring Boot application for analyzing and managing orders.

## Prerequisites

- Java 17 or higher
- Maven 3.6 or higher

## Getting Started

1. Clone the repository
2. Navigate to the project directory
3. Build the project:
   ```bash
   mvn clean install
   ```
4. Run the application:
   ```bash
   mvn spring-boot:run
   ```

The application will start on `http://localhost:8080`

## Features

- RESTful API endpoints for order management
- H2 in-memory database
- JPA for data persistence
- Swagger UI for API documentation (coming soon)

## Project Structure

```
src/
├── main/
│   ├── java/
│   │   └── com/
│   │       └── increff/
│   │           └── orderanalyser/
│   │               ├── controller/
│   │               ├── service/
│   │               ├── repository/
│   │               ├── model/
│   │               └── OrderAnalyserApplication.java
│   └── resources/
│       └── application.properties
└── test/
    └── java/
        └── com/
            └── increff/
                └── orderanalyser/
```

## Development

- The application uses H2 in-memory database which can be accessed at `http://localhost:8080/h2-console`
- Default database credentials:
  - JDBC URL: `jdbc:h2:mem:orderdb`
  - Username: `sa`
  - Password: `` (empty)

## License

This project is licensed under the MIT License.