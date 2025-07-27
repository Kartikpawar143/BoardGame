# BoardgameListingWebApp

## Description

**Board Game Database Full-Stack Web Application.**
This web application displays lists of board games and their reviews. While anyone can view the board game lists and reviews, they are required to log in to add/ edit the board games and their reviews. The 'users' have the authority to add board games to the list and add reviews, and the 'managers' have the authority to edit/ delete the reviews on top of the authorities of users.  

## Technologies

- Java
- Spring Boot
- Amazon Web Services(AWS) EC2
- Thymeleaf
- Thymeleaf Fragments
- HTML5
- CSS
- JavaScript
- Spring MVC
- JDBC
- H2 Database Engine (In-memory)
- JUnit test framework
- Spring Security
- Twitter Bootstrap
- Maven

## Features

- Full-Stack Application
- UI components created with Thymeleaf and styled with Twitter Bootstrap
- Authentication and authorization using Spring Security
  - Authentication by allowing the users to authenticate with a username and password
  - Authorization by granting different permissions based on the roles (non-members, users, and managers)
- Different roles (non-members, users, and managers) with varying levels of permissions
  - Non-members only can see the boardgame lists and reviews
  - Users can add board games and write reviews
  - Managers can edit and delete the reviews
- Deployed the application on AWS EC2
- JUnit test framework for unit testing
- Spring MVC best practices to segregate views, controllers, and database packages
- JDBC for database connectivity and interaction
- CRUD (Create, Read, Update, Delete) operations for managing data in the database
- Schema.sql file to customize the schema and input initial data
- Thymeleaf Fragments to reduce redundancy of repeating HTML elements (head, footer, navigation)

## How to Run

1. Clone the repository
2. Open the project in your IDE of choice
3. Run the application
4. To use initial user data, use the following credentials.
  - username: bugs    |     password: bunny (user role)
  - username: daffy   |     password: duck  (manager role)
5. You can also sign-up as a new user and customize your role to play with the application! 😊

## Output

<img width="1920" height="1080" alt="Screenshot 2025-07-27 032819" src="https://github.com/user-attachments/assets/fddf01d3-b154-41e5-900e-4e0b13d98048" />
<img width="1920" height="1080" alt="Screenshot 2025-07-27 033024" src="https://github.com/user-attachments/assets/16c46eb8-25de-4141-b887-7b9f8b84b4e6" />
<img width="1920" height="1080" alt="Screenshot 2025-07-27 032749" src="https://github.com/user-attachments/assets/62a1d7ba-e4d7-42e5-a9f9-d0b1e0297ab4" />
<img width="1920" height="1080" alt="Screenshot 2025-07-27 032730" src="https://github.com/user-attachments/assets/0451689a-9a4d-44a2-bf9c-4651fc990aee" />
<img width="1920" height="1080" alt="Screenshot 2025-07-27 033901" src="https://github.com/user-attachments/assets/74f1f2c4-b9a4-4a63-920e-8c367b8ad344" />
<img width="1920" height="1080" alt="Screenshot 2025-07-27 022031" src="https://github.com/user-attachments/assets/752dcf1a-0b81-4e99-929e-bce92a924089" />
<img width="1920" height="1080" alt="Screenshot 2025-07-27 032716" src="https://github.com/user-attachments/assets/8517e0dc-54fe-4497-8d7f-6edb57a684ca" />
<img width="1920" height="1080" alt="Screenshot 2025-07-27 021931" src="https://github.com/user-attachments/assets/6fb3f10c-2435-469d-bc58-5fad0af7673a" />
<img width="1920" height="1080" alt="Screenshot 2025-07-27 032707" src="https://github.com/user-attachments/assets/c9f9c5d2-87a5-43cf-8804-79082a6ec331" />
<img width="1920" height="1080" alt="Screenshot 2025-07-27 032652" src="https://github.com/user-attachments/assets/078d6e8d-6eb0-4059-8268-32d093bfcde8" />
