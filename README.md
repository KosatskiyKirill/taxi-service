# :taxi: Taxi Service :taxi:
![taxi](https://fainaidea.com/wp-content/uploads/2017/01/taxi.jpg)

The goal of this project is to create a taxi service with authentication system, custom injector, annotations and all the features that might come in handy while managing the app:

* During the first launch you will be redirected to a login page where you have two opportunities:
    * register a new driver
    * login as a previously registered driver
* To use all features you need to create new driver and authenticate
* Driver can add himself to different cars
* All of the remaining functionality you can find by starting the app
## Implementation details and technologies :clipboard:
Project based on 3-layer architecture:
* Presentation layer (controllers)
* Application layer (services)
* Data access layer (DAO)
## Technologies :wrench:
* Apache Tomcat
* Servlet
* JDBC
* MySQL
* JSTL
* HTML, CSS
* JSP
## Setup :computer:
1. Configure Apache Tomcat
2. Install MySQL and MySQL Workbench
3. Create a schema and all the necessary tables by using the script from resources/init_db.sql in MySQL Workbench
4. In the /util/ConnectionUtil.java class change the "user" and "password" properties to the ones you specified when installing MySQL
5. Start the application
