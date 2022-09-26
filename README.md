# Taxi-Service

I implemented this project, as a demonstration of technologies that I own. 

## Functionality list:
* Authorisation and authentication of user (Driver)
* Adding new driver (registration)
* Creating car manufacturers
* Creating cars
* Securing cars for drivers
* Deleting cars/drivers/manufacturers/drivers from car

## Used Technologies
* Java (ver. 11)
* Maven
* Tomcat
* JSP
* JDBC
* MySQL Database

## Used Patterns
* SOLID
* DAO
* N-tier architecture

# Things you should do if you want to try it yourself 
1. Fork this repo
2. Clone to your IDE 
3. Run script from init_db.sql to create needful database
4. Edit ConnectionUtil class. Set your parameters here:
```java
    private static final String URL = "DATABASE URL";
    private static final String USERNAME = "USERNAME";
    private static final String PASSWORD = "PASSWORD";
    private static final String JDBC_DRIVER = "JDBC DRIVER";
```
5. Install and configure Tomcat version 9.0.50
6. Run

