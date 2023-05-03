# Spring Boot dependencies

<< [Home](README.md)

To look for Spring Boot dependencies, you can use the Spring Boot project's official GitHub repository or the Maven Central Repository. The Spring Boot project provides a set of "starter" dependencies that simplify the process of adding common functionality to your Spring Boot applications, such as web services, data access, security, and more.

* `Spring Boot GitHub Repository`: You can browse the official Spring Boot GitHub repository to find starter dependencies and their documentation. The repository is located at: https://github.com/spring-projects/spring-boot
    Navigate to the `spring-boot-project` folder and then to the `spring-boot-starters` folder. Here, you can find various starter projects, each with its own README file describing its purpose and usage.

* `Maven Central Repository`: You can also search for Spring Boot dependencies on the Maven Central Repository. Visit the following URL: https://search.maven.org/  
    Type "org.springframework.boot" in the search bar to find all Spring Boot artifacts, including starter dependencies. To find a specific starter dependency, you can refine your search by including the starter name, e.g., "org.springframework.boot spring-boot-starter-web".

    Once you find the desired dependency, you can click on it to view its details and copy the dependency snippet for your build tool (Maven, Gradle, etc.). For example, to add the spring-boot-starter-web dependency to your Maven pom.xml file, you would copy the following snippet and paste it into the <dependencies> section:

```xml
<dependency>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-web</artifactId>
    <version>2.5.5</version> <!-- Replace with the desired version -->
</dependency>
```

> Note that you should replace the `<version>` element with the appropriate version for your Spring Boot application. Ideally, you should use the same version as your `spring-boot-starter-parent` to maintain consistency.

Additionally, the Spring Boot Reference Documentation (https://docs.spring.io/spring-boot/docs/current/reference/htmlsingle/) is a valuable resource for understanding the different starter dependencies and their use cases, as well as learning more about Spring Boot features and best practices.

## Commonly used Spring Boot dependencies

Here is a list of some of the most commonly used Spring Boot starter dependencies to help you get started with various features in your Spring Boot application:

* `Web`: For creating web applications and RESTful APIs using Spring MVC.
```xml
<dependency>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-web</artifactId>
</dependency>
```
* `Data JPA`: For using Spring Data JPA with Hibernate to access relational databases.
```xml
<dependency>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-data-jpa</artifactId>
</dependency>
```
* `Security`: For securing your application with Spring Security.
```xml
<dependency>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-security</artifactId>
</dependency>
```
* `Test`: For writing unit and integration tests using JUnit, Mockito, and Spring Test.
```xml
<dependency>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-test</artifactId>
    <scope>test</scope>
</dependency>
```
* `Actuator`: For adding production-ready features such as monitoring, metrics, and health checks.
```xml
<dependency>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-actuator</artifactId>
</dependency>
```
* `Thymeleaf`: For using Thymeleaf as a template engine in web applications.
```xml
<dependency>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-thymeleaf</artifactId>
</dependency>
```
* `WebSocket`: For building WebSocket-based applications.
```xml
<dependency>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-websocket</artifactId>
</dependency>
```
* `Data MongoDB`: For using Spring Data MongoDB to access MongoDB databases.
```xml
<dependency>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-data-mongodb</artifactId>
</dependency>
```
* `Data Redis`: For using Spring Data Redis to access Redis databases.
```xml
<dependency>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-data-redis</artifactId>
</dependency>
```
* `AMQP`: For using Spring AMQP and RabbitMQ.
```xml
<dependency>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-amqp</artifactId>
</dependency>
```

These starter dependencies are designed to simplify the process of configuring and setting up the necessary components for various use cases in Spring Boot applications. Simply add the desired starter dependency to your Maven pom.xml or Gradle build script to get started.

<< [Home](README.md)