## Authorization-server-demo

This is a simple example of oauth2 OIDC authorization server

This example is just a minimum setup with everything hardcoded in the application.yml. 

The redirect URL is set to http://localhost:8081/auth, which supposed to be the FE auth code handling endpoint.

## To run this Spring Boot application
```
mvn spring-boot:run
```