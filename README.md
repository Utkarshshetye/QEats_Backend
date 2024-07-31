# QEats_Backend
QEats is a popular food ordering app that allows users to browse and order their favorite dishes from nearby restaurants

-> During the course of this project,

-I had build different parts of the QEats backend which is a Spring Boot application.
-Several REST API endpoints were implemented to query restaurant information and place food orders.
-Along with this, I improved the app performance under large load scenarios as well as included an advanced search feature in the app. 

-> Retrieve restaurant data for a given user location

* Scope of Work
-Implemented GET /API/v1/restaurants and the corresponding request handler and response methods.
-Used Mockito to enable the development of the relevant MVCS layers independently.
-Retrieved a list of restaurants from MongoDB based on a user location.

Skills used
Spring Boot, Spring Data, REST API, Jackson, Mockito, JUnit, MongoDB

-> Replicate performance issues and solve them using caching strategies

* Scope of Work 
-Employed JMeter or load testing to expose performance issues.
-Identified DB queries contributing to degradation in performance.
-Used a Redis cache to alleviate read performance.

-> Perform search operations using custom attributes

* Scope of Work
-Used MongoDB queries to enable users to search for restaurants using attributes like name, cuisine, dish, and price.
-Used multithreading to increase the number of concurrent searches that can be performed.

Skills used
MongoDB querying, Multithreading
