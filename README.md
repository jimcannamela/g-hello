# g-hello

## Details
A Java 17 Gradle Spring Boot App responding on /hello at default port 8080

Navigate/send request to http://localhost:8080/hello to test running app.
## Requirements
- [Java 17](https://adoptium.net/)

## Usage
- Build
  ```
  ./gradlew build
  ```
  - Output directory: `build/libs`
- Run
  ```
  ./gradlew bootRun
  ```
  or
  ```
  java -jar build/libs/g-hello-0.0.1-SNAPSHOT.jar
  ```
- Test
  ```
  ./gradlew test
  ```