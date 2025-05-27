# airbnb-clone-project

# Description

  ## Objective
     The backend for the Airbnb Clone project is designed to provide\
     a robust and scalable foundation for managing user interactions,\
     property listings, bookings, and payments. This backend will\
     support various functionalities required to mimic the core\
     features of Airbnb, ensuring a smooth experience for users and hosts.

  ## Project Goals
  
   1. User Management: Implement a secure system for user registration, 
   authentication, and profile management.
   2. Property Management: Develop features for property listing creation, 
   updates, and retrieval.
   3. Booking System: Create a booking mechanism for users to 
   reserve properties and manage booking details.
   4. Payment Processing: Integrate a payment system to handle 
   transactions and record payment details.
   5. Review System: Allow users to leave reviews 
   and ratings for properties.
   6. Data Optimization: Ensure efficient data 
   retrieval and storage through database optimizations.
  ## Tech stack 
 _This project will phocas on_:
   +  __Django__
   +  __Django Rest Framework__
   +  __Postegresql__
   +  __Graphql__ 
   +  __Celery__ 
   +  __Redis__ 
   +  __Docker__
   +  __CI/CD Pipelines__ 

# Team Roles 
  +  __Backend Developer__: Responsible for implementing   
  API endpoints, database schemas,  and     business logic.
  +  __Database Administrator__: Manages database design, 
  indexing, and optimizations.
  +  __DevOps Engineer__: Handles deployment, monitoring, 
  and scaling of the backend services.
  +  __QA Engineer__: Ensures the backend functionalities 
  are thoroughly tested and meet quality standards.

 # Technology Stack 
  +  __Django__: A high-level Python web framework used for building the RESTful API.
  +  __Django REST Framework__: Provides tools for creating and managing RESTful APIs.
  +  __PostgreSQL__: A powerful relational database used for data storage.
  +  __GraphQL__: Allows for flexible and efficient querying of data.
  +  __Celery__: For handling asynchronous tasks such as sending    
                 notifications or processing payments.
  + __Redis__: Used for caching and session management.
  +  __Docker__: Containerization tool for consistent development and deployment environments.
  +  __CI/CD Pipelines__: Automated pipelines for testing and deploying code changes.

  # Database Design

    +  __User__
      + user_id: Primary Key, UUID, Indexed
      + first_name: VARCHAR, NOT NULL
      + last_name: VARCHAR, NOT NULL

    +  __Property__
      + property_id: Primary Key, UUID, Indexed
      + host_id: Foreign Key, references User(user_id)
      + name: VARCHAR, NOT NULL

    +  __Booking__
      + property_id: Primary Key, UUID, Indexed
      + host_id: Foreign Key, references User(user_id)
      + name: VARCHAR, NOT NULL
    
  # Feature Breakdown
    +  _User Authentication_
    +  _Property Management_
    +  _Booking System_
    +  _Payment Processing_
    +  _Review System_

  # Api Security 

  This Project use diferrent methods of authentication and authorization  
  to grant access to user to ensure their data and privacy are protected.
  Also it needs to ensure that payment that are made are secured and doesn't
  expose user credentials and their credit cards information.


