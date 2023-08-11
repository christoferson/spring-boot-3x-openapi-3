# spring-boot-3x-openapi-3
Spring Boot 3x with OpenApi 3

## Maven Dependency Setup

Spring Boot 3x requires OpenApi 2.x

```(xml)
<dependency>
    <groupId>org.springdoc</groupId>
    <artifactId>springdoc-openapi-starter-webmvc-ui</artifactId>
    <version>2.1.0</version>
</dependency>
```

## SpringDoc OpenApi Maven Plugin

mvn verify

https://github.com/springdoc/springdoc-openapi-maven-plugin

-----------------------------------------------------------------------------------------------------------------------------

## Open Swagger UI

http://localhost:8080/swagger-ui/index.html

## OpenAPI Description Path

http://localhost:8080/v3/api-docs

http://localhost:8080/v3/api-docs.yaml

## swagger-ui Properties

```
# Specify the path of the OpenAPI documentation
springdoc.api-docs.path=/api-docs

# Specify the path of the Swagger UI
springdoc.swagger-ui.path=/swagger-ui.html

# Enable or disable Swagger UI
springdoc.swagger-ui.enabled=true
```

-----------------------------------------------------------------------------------------------------------------------------

