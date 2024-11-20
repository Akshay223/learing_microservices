# learing_microservices

In this project, I have developed and learned to implement two separate microservices: Product Microservice and Review Microservice.

Product Microservice: I learned how to create a RESTful service for managing product-related data, using Spring Boot to handle CRUD operations. I configured MySQL to store product information and learned how to interact with the database using Spring Data JPA.

Review Microservice: I implemented a similar service for managing reviews related to products. I gained experience in setting up a separate microservice with its own database (also MySQL), and exposing APIs to handle review-related data.

Inter-Service Communication: I learned how to integrate the two microservices by using RestTemplate to make HTTP calls between the Product Microservice and the Review Microservice. When fetching product details, I used RestTemplate to call the Review Microservice, retrieve the reviews, and combine both product and review data in a DTO (ProductWithReviews).

This project provided me with valuable hands-on experience in creating independent microservices, ensuring communication between them, and managing data with Spring Boot and MySQL. Additionally, I learned how to effectively handle data flow between services and test API endpoints using Postman.
