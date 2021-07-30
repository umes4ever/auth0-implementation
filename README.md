# Auth0 Implementation made easy with Spring Boot and React.

[Spring Boot Application](https://github.com/umes4ever/auth0-implementation/tree/master/auth0-spring-boot)

[React App](https://github.com/umes4ever/auth0-implementation/tree/master/reactapp-auth0)

Configure application.properties in Spring Boot Application

```
auth0.audience=
spring.security.oauth2.resourceserver.jwt.issuer-uri=
```


Configure config.json in React App

```

{
    "domain": "",
    "clientId": "",
    "audience": "",
    "scope": "read:current_user"
}
```

Know how these values can be obtained in Medium Story.


To run Spring Boot Application:

For Windows:
```
gradlew.bat build
gradlew.bat bootRun
```

For Linux/Mac:
```
./gradle build
./gradle bootRun
```

To run React App:
```
npm i
npm start (This is for Development)
```
