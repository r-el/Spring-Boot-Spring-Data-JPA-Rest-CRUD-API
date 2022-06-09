# Spring-Boot-Spring-Data-JPA-Rest-CRUD-API
_Spring Boot Rest CRUD API example with Maven that use Spring Data JPA to interact with MySQL database._


- configure Spring Data, JPA, Hibernate to work with Database
- Data Models and Repository interfaces
- Spring Rest Controller to process HTTP requests
- Spring Data JPA to interact with MySQL Database

## Overview
Spring Boot JPA Rest CRUD API for a Tutorial application in that:
- Each Tutotial has id, title, description, published status.
- Apis help to create, retrieve, update, delete Tutorials.
- Apis also support custom finder methods such as find by published status or by title.

These are APIs: 

| Methods | Urls | Actions |
| ------ | ------ | ------ |
POST | /api/tutorials |	create new Tutorial |
GET	| api/tutorials |retrieve all Tutorials |
GET	| api/tutorials/:id	| etrieve a Tutorial by *:id* |
PUT	| api/tutorials/:id | update a Tutorial by *:id* |
DELETE| / api/tutorials/:id | delete a Tutorial by *:id* |
DELETE| / api/tutorials | delete all Tutorials |
GET |	/api/tutorials/published |	find all published Tutorials |
GET |	/api/tutorials?title=[keyword] |	find all Tutorials which title contains *keyword* |

## Technology
- Java 17
- Spring Boot 2.7.0 (with Spring Web MVC, Spring Data JPA)
- MySQL
- Maven 3.8.5