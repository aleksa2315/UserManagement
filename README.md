Java Spring Boot application used for managing users and their orders using REST API.

Backend is implemented in Java using Spring Boot, it manages users, different permissions that they have, dishes and orders that they make. 
Error handler is implemented for catching errors that may appear during order processing.
Authentification is done through JWT and authentication is done through custom AuthGuard on frontend. 
Also order processing logic is done with scheduling and using thread polling. 

Fronted is implemented in Angular.
It has pages to view and alter users, dishes, orders and errors. 
Authentication is done through custom AuthGuard that goes through users permissions. 
Styling is done using Tailwind framework
