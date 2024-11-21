# Hello World Spring Boot Application

## Description
A simple Spring Boot application that demonstrates a REST API returning "Hello, World!". This project is designed for beginners to learn the basics of Spring Boot, including setting up a web application, creating RESTful endpoints, and implementing basic logging and error handling.

## Prerequisites
Before you begin, ensure you have the following installed on your machine:

- **Java Development Kit (JDK)**: Version 11 or later
- **Maven**: For dependency management and building the project
- **IDE**: IntelliJ IDEA, Eclipse, or any other Java IDE

## Getting Started

### 1. Clone the Repository
Clone this repository to your local machine

### 2. Build the Project
Navigate to the root directory of the project (where the `pom.xml` file is located) and run the following command to build the project:

mvn clean install

### 3. Run the Application
You can run the application using one of the following methods:

#### Method 1: Using Your IDE
- Open the project in your IDE.
- Locate the `HelloworldApplication.java` file in `src/main/java/com/example/helloworld`.
- Right-click on the file and select `Run 'HelloworldApplication.main()'`.

#### Method 2: Using the Command Line
Run the following command in the terminal:

mvn spring-boot:run

### 4. Access the REST API
Once the application is running, you can access the REST API by navigating to the following URL in your web browser or using a tool like Postman:

http://localhost:8080/hello

You should see the response:

Hello, World!

## Logging
The application uses SLF4J for logging. You can find log messages in the console output when you access the `/hello` endpoint.

## Error Handling
The application includes a global exception handler that returns a generic error message for any unhandled exceptions.

## Project Structure
helloworld/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/
│   │   │       └── example/
│   │   │           └── helloworld/
│   │   │               ├── HelloworldApplication.java
│   │   │               ├── HelloWorldController.java
│   │   │               └── GlobalExceptionHandler.java
│   │   └── resources/
│   │       └── application.properties
└── pom.xml

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- [Spring Boot Documentation](https://spring.io/projects/spring-boot)
- [Maven Documentation](https://maven.apache.org/guides/index.html)
