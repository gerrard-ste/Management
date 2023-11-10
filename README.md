# school
The project is structured with the following key components:

Entities: Represented by the Filiere, Role, and Student classes, these are the core data structures that map to the underlying database tables.

DAO (Data Access Object): The Impl class implements the Localschool interface, providing methods for creating, retrieving, updating, and deleting entities. This class interacts with the underlying database through JPA (Java Persistence API) and manages the business logic associated with school management.

Client Application: The EJBClient is a simple Java SE client application that showcases how to interact with the EJBs deployed on a Java EE server. It demonstrates basic CRUD (Create, Read, Update, Delete) operations for filières, roles, and students.

Usage
Build the Project:

Ensure you have the necessary build tools installed (e.g., Maven).
Build the project using the provided pom.xml file.
Run the Client Application:

Run the EJBClient application to interact with the EJBs deployed on a Java EE server.
Update the connection details in the client code (EJBClient.java) and the jboss-ejb-client.properties file as needed.
