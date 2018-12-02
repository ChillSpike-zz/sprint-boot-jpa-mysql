# Spring Boot, MySQL, JPA, Hibernate Rest API Tutorial

## Build REST CRUD API for a simple Note-Taking application using Spring Boot, Mysql, JPA and Hibernate.

## Requirements

1. Java - 1.8.x

2. Maven - 3.x.x

3. Mysql - 5.x.x

4. POSTMAN

## Steps to Setup

**1. Clone the application**

```bash
git clone https://github.com/ChillSpike/sprint-boot-jpa-mysql.git
```

**2. Create Mysql database**
```bash
create database java_security
```

**3. Change mysql username and password as per your installation**

+ open `src/main/resources/application.properties`

+ change `spring.datasource.username` and `spring.datasource.password` as per your mysql installation

**4. Open Eclipse IDE and import the project as existing maven project**

## The app will start running at <http://localhost:8084>.

## Explore Rest APIs

The app defines following CRUD APIs.

    GET /api/notes
    
    POST /api/notes
    
    GET /api/notes/{noteId}
    
    PUT /api/notes/{noteId}
    
    DELETE /api/notes/{noteId}

You can test them using postman or any other rest client.
