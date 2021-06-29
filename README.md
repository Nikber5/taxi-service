# Taxi service app
Simple web app based on the RDBMS **MySQL**, using **JDBC**, **Servlets** and **JSP**'s.
The project follows **SOLID** principles, **N-tier architecture** (DB, DAO layer, Service layer, Controller layer) and authentication implemented using filter. Dependency inversion principle realized through custom injector class.

After registration, or login with existing account user (driver and user are the same) can view all drivers, manufacturers and cars, as well as create them. The driver can also connect cars to himself, as well as view all cars connected to him. There is also a logout function.  

Technologies used:
-
- Backend: Java, JDBC, Servlets 
- Frontend: HTML, CSS, JSP, JSTL 
- Database: MySql, MySQLWorkbench, Remote MySQL
- Web-server: Tomcat
- Packaging: Apache Maven

To view the project you need:
-
Follow the link: https://polar-tor-20305.herokuapp.com/login

Login as: bob, password: 1234 or register new user

Or you canA:
- clone the project to your local repository 
- create MySQL database by import from init_db.sql file
- setup ConnectionUtil class by replacing mock values of constants with your own.
- configure Tomcat Server
- run a project