# CRaC Spring Boot starter

This artifact is intended to provide OpenJDK CRaC support for Spring Boot applications before the support is integrated to Spring Boot, or for versions that did not have that integrated yet.

The application should not require modifications in its code, only inclusion of this artifact as a dependency.

## Usage

```
<dependency>
    <groupId>io.github.crac.org.springframework.boot</groupId>
    <artifactId>crac-spring-boot-starter</artifactId>
    <version>3.4.3</version>
</dependency>
```

Please note that the application should add `org.crac:crac` dependency as well.
