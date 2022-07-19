# 🚕Taxi service🚕
![image](https://user-images.githubusercontent.com/83237769/179720964-77c19113-635a-4b06-80d4-b89fdfa225fa.png)

## 👨‍💻General description
This is simple web-application that supports authentication, registration and other CRUD operations. Taxi service has 3-layer design:
* Controllers
* Service
* DAO

Also, when we run this application, we must to do authentication (or registration). This will allow us use all functions of this app.

## 💻Used technogologies

* Java 11+
* MySQL 8.0.29
* Maven
* JDBC
* JSTL 1.2
* JAVA Servlet API
* Tomcat 9.0.64

## ⚙Implementations

* Registration
* Authentication
* Display all drivers
* Display all cars
* Display all manufacturers
* Create new car
* Create new manufacturer
* Add driver to car

## How run this project

* Download and install MySQL, Apache TomCat, Maven, JDK 11+
* Clone project from this repository
* Add DB to project(coppy all from init_db.sql) and configurate TomCat
* Create connection to your DB
* Run application with TomCat

## Database structure

![join-db-diagram](https://user-images.githubusercontent.com/83237769/179726132-271a887d-1503-4f4a-8d4b-117942da4f1f.png)