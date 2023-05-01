# g-hello

## Details
This is a simple Spring Boot application written in Java 17 and built using Gradle. It exposes a REST endpoint at /hello which returns a simple greeting message.

## Requirements
- [Java 17](https://adoptium.net/)

## Usage
To build, test and run the application using the Gradle wrapper, follow these simple steps:

1. Clone the repository to your local machine.
1. Open a terminal window and navigate to the root directory of the project.
1. To build the application, run the following command:
    ```
    ./gradlew build
    ```
    - This will download all the required dependencies, compile the code and generate an executable jar file in the `build/libs` directory.
1. To run the tests, run the following command:
    ```
    ./gradlew test
    ```
    - This will execute all the unit and integration tests in the project.
1. To run the application, run the following command:
    ```
    ./gradlew bootRun
    ```
    - This will start the application and make it accessible at `http://localhost:8080/hello`.
1. Alternatively, you can run the application by executing the jar file directly:
    ```
    java -jar build/libs/g-hello-0.0.1-SNAPSHOT.jar
    ```
    - This will start the application and also make it accessible at `http://localhost:8080/hello`.