# Java Security Day 1 Exercise

## Learning Objectives
- Build an API
- Prevent unauthorised users from accessing it
- Secure the application using a simple username and password login

## Instructions

1. Fork this repository
2. Clone your fork to your machine
3. Open the project in IntelliJ

## Core Activity

Based on the activities from this morning create an API for the following with the usual CRUD endpoints. Make it so that only admin users who have successfully logged in are able to access the endpoints. Use Hibernate and JPA to manage the database connections, and whatever other tools you want to populate the tables. You may have all the dependencies you need in `build.gradle` or you may need to add more as required. 

### API (Core Version)

Create a suitable OpenAPI spec for a library to keep track of Video Games (ie you could store information such as Title, GameStudio, Age Rating, Number Of Players, Genre etc) and then implement the API for it, including the simplified security we used in the morning session, to prevent unauthorised users from accessing the endpoints of the library.

## Extension Activity

Add to the spec from the morning to include user tables (these are not the admin users who are interacting with the endpoints, api interactions are only done by the admin users -  ie the people who know how to login). These users should have some basic information stored about them, and there should be the usual CRUD endpoints to manage users. You also need to allow users to borrow games and return them, keep track of who is currently borrowing what and be able to access records on what games a user has previously borrowed along with which users have borrowed each game. Implement the Spec for this along with the code.



