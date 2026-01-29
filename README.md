# Sample Repo

This repository was converted into a minimal Java Spring Boot Maven project.

Quick start:

```bash
# Build
mvn -v            # verify Maven is installed
mvn clean package

# Run
mvn spring-boot:run

# Test the sample endpoint
# open http://localhost:8080/api/hello
```

Files added:

- `pom.xml` — Maven project file with Spring Boot dependencies
- `src/main/java/com/example/demo/DemoApplication.java` — main application
- `src/main/java/com/example/demo/controller/HelloController.java` — sample REST controller
- `src/main/resources/application.properties`


