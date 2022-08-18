# :oncoming_taxi: Taxi Service :oncoming_taxi:
### Project description:
This is Taxi service web application with the basic UI interface that allows you to create cars, manufacturers, drivers and attach drivers to the cars.
### Features:
- registration as a driver
- authentication as a driver
- create/update/remove a manufacturer
- create/update/remove a car
- create/update/remove a driver
- display a list of all manufacturers
- display a list of all cars
- display a list of all drivers
- display a list of all cars by current driver
- add a driver to the car
### Project structure (3-layer architecture):
- DAO - data access layer
- Service - application logic layer
- Controllers - presentation layer
### Used technologies and libraries:
- Java 11
- Git
- Apache Maven
- Apache TomCat
- Apache log4j 2
- MySQL
- JDBC
- Javax Servlet
- JSTL
- HTML/CSS
- Checkstyle plugin
- Project lombok
### Steps to run the program on your computer:
- Install MySQL
- Install 9.0.54 version TomCat.
- Fork this project and clone it.
- To get the actual parameters of the database tables, run the script from the resources/init_db.sql file in the Workbench.
- Add your information to ConnectionUtil located in util (URL, login, password, JDBC driver) to be able to connect to your database.
- Configure your Tomcat (your application context needs to be as "/").
- Run this project using Tomcat's local server.
