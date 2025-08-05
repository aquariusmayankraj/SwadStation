# SwadStation
SwadStation is a smart and interactive Food Ordering Web Application developed using Spring Boot, Thymeleaf, and MySQL, allowing users to search, order, and track food items, while admins manage the backend operations efficiently.

<img width="1908" height="912" alt="homePage" src="https://github.com/user-attachments/assets/a4112e0f-de97-4157-8afb-5a1e2c233215" />

<img width="1511" height="684" alt="productPage" src="https://github.com/user-attachments/assets/cf59db46-ae9b-46e0-b1a2-263fc0d6b88b" />

<img width="1495" height="728" alt="locationPage" src="https://github.com/user-attachments/assets/d018d1e0-edee-4daf-8b64-b4e32f8b8465" />

<img width="1494" height="820" alt="aboutPage" src="https://github.com/user-attachments/assets/664a3cfa-656a-4c48-92d6-b5d037fd581e" />

<img width="1483" height="675" alt="loginPage" src="https://github.com/user-attachments/assets/4bdc7411-e4bf-4b86-81ab-beceac9c0ea2" />


## Features

- **Customer Management**: Easily add, update, and delete customer information.
- **Inventory Management**: Keep track of your inventory items, including stock levels and pricing.
- **Order Management**: Manage customer orders, including order creation, updates, and status tracking.
- **User Authentication**: Secure login and authentication for admin and staff members.
- **Role-Based Access Control**: Define roles and permissions for different user types.
- **Thymeleaf Templates**: Utilizes Thymeleaf for dynamic HTML templates.
- **Database Integration**: Integrated with MySQL for data storage and retrieval.

# Technology 

- **Backend**: Spring Boot, Java 8, Spring MVC, Spring Data JPA (Hibernate)
- **Frontend**: Thymeleaf, HTML, CSS, JavaScript
- **Database**: MySQL
- **IDE**: VsCode

```bash
src/
├── main/
│   ├── java/
│   │   └── com.example.foodfrenzy/
│   │       ├── controller/      # Contains all controllers
│   │       ├── model/           # Contains entity classes
│   │       ├── repository/      # Repository interfaces for database interaction
│   │       └── service/         # Service layer with business logic
│   ├── resources/
│   │   ├── templates/           # Thymeleaf templates for views
│   │   ├── static/              # Static assets (CSS, JavaScript)
│   │   └── application.properties  # Project configuration
│   └── webapp/
│       └── WEB-INF/
│           └── views/           # Additional view files
└── test/                        # Test cases for unit testing

