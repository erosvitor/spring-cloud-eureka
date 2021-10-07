## About
The project shows how to implement a service discovery using the Spring Cloud Netflix Eureka.

## Technologies
The following tools were used in this project:

* [Java Oracle](https://www.oracle.com/java/)
* [Apache Maven](https://maven.apache.org/)
* [Spring Boot](https://spring.io/projects/spring-boot)
* [Spring Cloud Netflix Eureka](https://spring.io/projects/spring-cloud-netflix)
* [IDE Eclipse](https://www.eclipse.org/)

## Requirements
Before starting this project you need to have Git, JDK Oracle, Maven and Eclipse IDE installed.

## Starting the project

### Clonning the project
```
$ git clone https://github.com/erosvitor/spring-cloud-eureka.git

$ cd spring-cloud-eureka
```

### Testing the project
**Step 1:** Start the microservices using Eclipse IDE or by Maven command line
* EurekaServer
* ServiceOne
* ServiceTwo

**Step 2:** Access Eureka Dashboard

```
http://localhost:8761
```

![](references/eureka-dashboard.png)

## License
This project is under license from MIT. For more details, see the LICENSE file.

## Release History
* 1.0.1 (2021-08-03)
    * Spring Boot updated to 2.5.3
    * Spring Cloud updated to 2020.0.3
    * Section 'references' added
* 1.0.0 (2021-05-15)
    * First version
