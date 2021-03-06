# TAXI-SERVICE

## Contents
___
- [Description](#Description)
- [Features](#Features)
- [Project structure](#Project-structure)
- [Technologies](#Technologies)
- [How to run a project](#How-to-run)

___
<a name="Description"></a>
## Description
This project is the simple taxi service application's analog with driver's authentication.

___
<a name="Features"></a>
## Features
* registration / creating a new driver
* logging in with login and password
* creating a new car manufacturer
* creating a new car
* adding a specific driver to the car
* displaying all cars / manufacturers / drivers
* deleting driver from the specific car
* deleting specific car / manufacturer / driver from database

___
<a name="Project-structure"></a>
## Project structure
This project is built by 3-tier architecture:

- Controllers - Presentation layer
- Service - Application layer
- DAO - Data access layer

### Table relations
![relation](src/main/resources/images/diagram.png)
___
<a name="Technologies"></a>
## Technologies
- Java 11
- MySql
- JDBC
- JSP, JSTL
- HTML, CSS
- Apache Tomcat (v. 9.0.50)
- Maven

___
<a name="How-to-run"></a>
## How to run this project
1. Install MySQL
2. Install Tomcat 9.0.50 version
3. Fork this project to your repository
4. Clone it using one of the "Code" options, which is more suitable for you
5. In resources directory you can find init_db.sql file. Use it to initialize your database
6. Go to the ConnectionUtil class located in src/main/java/taxi/util and add your url to DB, login, password and JDBC driver there.
7. Configure your Tomcat. (P.S. Your application context needs to be as "/")
8. Run this project using Tomcat's local server
