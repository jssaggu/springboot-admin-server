# SpringBoot Admin Server

Simply start the server and add the following code in client repos so they can connect.

## application.yml
```yaml
spring:
  boot:
    admin:
      client:
        url:  http://localhost:9090
        enabled: true
        auto-registration: true
```

## Maven Dependency 

```xml
    <dependency>
        <groupId>de.codecentric</groupId>
        <artifactId>spring-boot-admin-starter-client</artifactId>
        <version>3.0.0-M5</version>
    </dependency>
```