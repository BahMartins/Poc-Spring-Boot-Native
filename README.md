# Poc-Spring-Boot-Native

This build a Spring Boot Native application using the GraalVM native.

If you want to know more about Spring Boot Native, please visit its website: https://docs.spring.io/spring-native/docs/current/reference/htmlsingle/#overview


## Packaging and running the application
The application can be package using:
```
$ mvn -Pnative -DskipTests package
```

## Running the application
You can run your application using:
```
$ target/{PROJECT-NAME}
```

## Test the application
The application can be tested using:
```
$ mvn -Pnative test
```

