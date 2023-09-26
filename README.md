# Task-1-Java-REST-API-example
In this project i have implemented an java application that provides REST-API with endpoints for searching, creating and deleting “server” objects its a CRUD operation. and i have used postman for showing how the application responds to requests for each operation.
Create a new Java project.
Add the following dependencies to your pom.xml file:
Spring Boot
Spring Data MongoDB
Postman
Create a Server model class. This class should contain the fields that you want to store in your MongoDB database.
Create a ServerRepository interface. This interface will extend JpaRepository<Server, String>.
Create a ServerService class. This class will implement the ServerRepository interface and provide methods for creating, reading, updating, and deleting servers.
Create a ServerController class. This class will handle REST requests for servers.
Create a Spring Boot application class. This class will be the entry point for your application.
Configure your Spring Boot application to connect to your MongoDB database.
Start your Spring Boot application.
