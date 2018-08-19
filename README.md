
# Spring Boot, Apache Derby , JPA, Hibernate Rest API 

Build Restful CRUD API for a simple Note-Taking application using Spring Boot, Mysql, JPA and Hibernate.

## Requirements

1. Java - 1.8.x

2. Maven - 3.x.x


## Steps to Setup

**1. Clone the application**

```bash
git clone https://github.com/callicoder/spring-boot-mysql-rest-api-tutorial.git
```

**2. Build and run the app using maven**

```bash
mvn package
java -jar target/course-api-data-1.0.0.jar
```

Alternatively, you can run the app without packaging it using -

```bash
mvn spring-boot:run
```

The app will start running at <http://localhost:8080>.

## Explore Rest APIs

The app defines following CRUD APIs.

    GET /topics
    Get All Topics
    
    POST /topics
    Adding Topics to Database
    
    GET /topics/{id}
    Get Specific Topic
    
    PUT /topics/{id}
    Update Topic
    
    DELETE /topics/{id}
    Deleting Topic

You can test them using postman or any other rest client.


